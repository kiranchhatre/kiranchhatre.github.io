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

>   **Fawkes Robot Software Framework**

-   Fawkes is a component-based Software Framework for Robotic Real-Time Applications for various Platforms and Domains.

<a href="http://www.youtube.com/watch?feature=player_embedded&v=pt4CqpuaVxE
" target="_blank"><img src="http://img.youtube.com/vi/pt4CqpuaVxE/0.jpg"
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

It is developed and used for cognitive robotics real-time applications such as soccer, domestic service, or industrial mobile robots. It supports fast information exchange and efficient combination and coordination of different components to suit the needs of mobile robots operating in uncertain environments.<br/>
Today, Fawkes consists of an efficient communication middleware with a hybrid blackboard and messaging design, a flexible set of software libraries to make developing robotic functionalities reasonably simple, and a coherent development and run-time environment with tools that make integrating and running robotic applications achievable. But Fawkes also comprises a large set of plugins, software components that implement typical robot functionality like self-localization, path planning, perception, or behavior execution and monitoring. Several robot platforms like the Robotino, Nao, or Roomba are supported out-of-the-box. Fawkes also integrates with other software frameworks like ROS or Player and integrates third party software like MongoDB, Prometheus, CLIPS, or OpenNI. By using ideas from aspect-oriented programming, and run-time requirement assertion by the framework, it is easy to access these resources with only a few lines of code.
-   [Repository](https://github.com/carologistics)
-   [Wiki](https://trac.fawkesrobotics.org/)

![fawkes](/assets/images/fawkes.png)

>   **Navier-Stokes Equations using Python**

-   [Repository](https://github.com/kiranchhatre/Navier_Stokes_Equations)

![ns](/assets/images/ns.png)

>   **Optimization: Mini batch gradient descent with momentum and Adam mode**

-   [Repository](https://github.com/kiranchhatre/Optimization_algorithms/blob/master/Optimization%20algorithms.ipynb)

>   **Word2Vec using TensorFlow using dummy data**

-   [Repository](https://github.com/kiranchhatre/Word2vec)

![w2v](/assets/images/w2v.png)

>   **He et al Initialization for Neural Networks**

-   [Repository](https://github.com/kiranchhatre/Initialization_techniques/blob/master/Initialization%20techniques.ipynb)

>   **Gradient Checking Algorithm**

-   [Repository](https://github.com/kiranchhatre/Gradient_Checking_Algorithm/blob/master/Gradient%20Checking%20Algorithm.ipynb)

>   **Football Corporation Goalkeeper Position Recommendation**

-   [Repository](https://github.com/kiranchhatre/French-Football-Corporation-Goalkeeper-Position-Recommendation-/blob/master/French%20Football%20Corporation%20Goalkeeper%20Position%20Recommendation%20.ipynb)

>   **ABB IRB 7600-340 Robot visualization in VR and 3D mode**


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

>   **Kaggle competition**





