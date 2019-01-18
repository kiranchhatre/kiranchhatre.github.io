---
title: ""
permalink: /Research/
tags: [machine learning, data science, neural network]
header:
classes: wide
mathjax: "true"
---

>   **Mini Thesis** at Institute of General Mechanics at RWTH Aachen University, Germany.

-   Constitutive Viscoplastic Modeling using Aritificial Neural Networks.

>   **TensorFlow implementation to decipher sign language**

-   [Repository](https://github.com/kiranchhatre/Tensorflow-decipher_sign_language)

![tfsign](/assets/images/tfsign.png)


>   **Navier-Stokes Equations using Python**

-   [Repository](https://github.com/kiranchhatre/Navier_Stokes_Equations)

![ns](/assets/images/ns.png)

>   **Optimization: Mini batch gradient descent with momentum and Adam mode**

-   [Repository](https://github.com/kiranchhatre/Optimization_algorithms/blob/master/Optimization%20algorithms.ipynb)

>   **Word2Vec using TensorFlow using dummy data**

-   [Repository](https://github.com/kiranchhatre/Word2vec)

![w2v](/assets/images/w2v.png)

>   **He et al (2015) Initialization for Neural Networks**

-   [Repository](https://github.com/kiranchhatre/Initialization_techniques/blob/master/Initialization%20techniques.ipynb)

>   **Gradient Checking Algorithm**

-   [Repository](https://github.com/kiranchhatre/Gradient_Checking_Algorithm/blob/master/Gradient%20Checking%20Algorithm.ipynb)

>   **Poppy Humanoid Robot**

-   Contribution to the open source platform of interactive 3D printed humanoid robots.
-   [https://www.poppy-project.org](https://www.poppy-project.org)

-   ***Video***:<br/>
<a href="http://www.youtube.com/watch?feature=player_embedded&v=F8lEnWRMn9g
" target="_blank"><img src="http://img.youtube.com/vi/F8lEnWRMn9g/0.jpg"
alt="IMAGE ALT TEXT HERE" width="380" height="250" border="10" /></a>


>   **Football Corporation Goalkeeper Position Recommendation**

-   [Repository](https://github.com/kiranchhatre/French-Football-Corporation-Goalkeeper-Position-Recommendation-/blob/master/French%20Football%20Corporation%20Goalkeeper%20Position%20Recommendation%20.ipynb)

>   **ABB IRB 7600-340 Robot visualization in VR and 3D mode using JavaScript** (Ongoing)


>   **Logistic regression to recognize cats**

-   [Repository](https://github.com/kiranchhatre/Logistic_Regression)

>   **Softmax Linear Classifier using 2 NN for visual recognition**

-   Cross Entropy Loss Function
-   [Repository](https://github.com/kiranchhatre/Convolutional_Neural_Network_Visual_Recognition)

![Vision](/assets/images/Vision.png)

>   **Recommendation System**

-   Recommendation System: Collaborative and Content-based; NumPy,SciPy, LightFM, OpenMP, Weighted Approximate-Rank Pairwise,
    Gradient Descent, Compressed Sparse Row Format; MovieLens: GroupLens Research Site (University of Minnesota)
-   [Repository](https://github.com/kiranchhatre/lightfm_recommendation_algorithm)
-   [https://movielens.org/](https://movielens.org/)




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


>   **Supervised learning with 5 layer deep neural network using ReLU for image classification.**

-   [Repository](https://github.com/kiranchhatre/L_layer_deep_neural_network)

>   **Planar data classification**

-   [Repository](https://github.com/kiranchhatre/Planar_data_classification/blob/master/Planar%20data%20classification%20with%20one%20hidden%20layer.ipynb)

![pdc](/assets/images/pdc.png)

>   **Dymola Systems Simulation of a Washing Machine**

-   ***Video***:<br/>
<a href="http://www.youtube.com/watch?feature=player_embedded&v=vp25SSnMDRw
" target="_blank"><img src="http://img.youtube.com/vi/vp25SSnMDRw/0.jpg"
alt="IMAGE ALT TEXT HERE" width="380" height="250" border="10" /></a>







