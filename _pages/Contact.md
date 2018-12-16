title: "Contact"
permalink: /Contact/
published: true
process:
    markdown: true
child_type: default
routable: true
cache_enable: true
visible: true
form:
    name: contact
    fields:
        -
            name: name
            label: Name
            placeholder: 'Your Name'
            autofocus: 'on'
            autocomplete: 'on'
            type: text
            validate:
                required: true
        -
            name: email
            label: E-Mail
            placeholder: 'Your eMail address'
            type: email
            validate:
                required: true
        -
            name: message
            label: Message
            placeholder: 'Your message'
            type: textarea
            validate:
                required: true
        -
            name: privacyAccepted
            label: 'I consent that this personal data will be processed according to our [privacy notice](/legal/privacy).'
            type: checkbox
            style: 'float: left; margin-top: 6px;'
            validate:
                required: true
                message: 'Permission to use the given data must be granted!'
        -
            name: privacyDescription
            label: 'You may withdraw this consent at any time via eMail to [me@somewhere.com](mailto:me@somewhere.com).'
            type: display
            markdown: true
            content: null
    buttons:
        -
            type: submit
            value: Submit
        -
            type: reset
            value: Reset
    process:
        -
            email:
                subject: '[somewhere.com Contact form] {{ form.value.name|e }}'
                body: '{% include ''forms/data.html.twig'' %}'
        -
            save:
                fileprefix: contact-
                dateformat: Ymd-His-u
                extension: txt
                body: '{% include ''forms/data.txt.twig'' %}'
        -
            message: ''
        -
            display: thankyou
---

# Contact form

Please describe your concerns, I will answer as soon as possible.
Direct contact: [me@somewhere.com](mailto:me@somewhere.com)
