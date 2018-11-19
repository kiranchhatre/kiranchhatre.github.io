---
title: ""
permalink: /Research/
tags: [machine learning, data science, neural network]
header:
classes: wide
mathjax: "true"
---

## Data Science

>   **Mini Thesis** at Institute of General Mechanics at RWTH Aachen University, Germany. (*September 2018 – Present*)

-   Constitutive Viscoplastic Modeling using Aritificial Neural Networks.

>   **Navier-Stokes Equations using Python**

-   [Code](https://github.com/kiranchhatre/Navier_Stokes_Equations)

>   **Word2Vec using TensorFlow using dummy data**

![image-right]({{ site.url }}{{ site.baseurl }}/assets/images/word2vec.png){: .align-right}

-   [Code](https://github.com/kiranchhatre/Word2vec)

>   **Softmax Linear Classifier using 2 NN for visual recognition**

-   Cross Entropy Loss Function
-   [Code](https://github.com/kiranchhatre/Convolutional_Neural_Network_Visual_Recognition)
-   Math: $$−(ylog(p)+(1−y)log(1−p))$$

![image-right]({{ site.url }}{{ site.baseurl }}/assets/images/vision.png){: .align-right}

>   **Recommendation System**

-   Recommendation System: Collaborative and Content-based; NumPy,SciPy, LightFM, OpenMP, Weighted Approximate-Rank Pairwise,
    Gradient Descent, Compressed Sparse Row Format; MovieLens: GroupLens Research Site (University of Minnesota)
-   [Code](https://github.com/kiranchhatre/lightfm_recommendation_algorithm)
-   https://movielens.org/

'''python

        def sample_recommendation(model, data, user_ids):
        # number of users and movies in training data
        n_users, n_items = data['train'].shape
        # generate recommendations for each user we input
        for user_id in user_ids:
            # movies they already like
            known_positives = data['item_labels'][data['train'].tocsr()[user_id].indices]

            # movies our model predicts they will like
            scores = model.predict(user_id, np.arange(n_items))

            # rank them in order of most liked to the least
            top_items = data['item_labels'][np.argsort(-scores)]

            # print out the results
            print('User %s' % user_id)
            print('Known positives:')

            for x in known_positives[:3]:
                print('        %s' % x)

            print('Recommended:')

            for x in top_items[:3]:
                print('         %s' % x)
'''

>   **Supervised learning with 5 layer deep neural network using ReLU for image classification.**

-   [Code](https://github.com/kiranchhatre/L_layer_deep_neural_network)


![image-right]({{ site.url }}{{ site.baseurl }}/assets/images/DNN.png){: .align-right}


>   **Kaggle competition**





