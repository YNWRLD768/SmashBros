# What is artificial intelligence (AI)?
---

Artificial intelligence (AI) is technology that enables computers and machines to simulate human learning, comprehension, problem solving, decision making, creativity and autonomy.

Applications and devices equipped with AI can see and identify objects. They can understand and respond to human language. They can learn from new information and experience. They can make detailed recommendations to users and experts. They can act independently, replacing the need for human intelligence or intervention (a classic example being a self-driving car).

But in 2024, most AI researchers, practitioners and most AI-related headlines are focused on breakthroughs in generative AI (gen AI), a technology that can create original text, images, video and other content. To fully understand generative AI, it’s important to first understand the technologies on which generative AI tools are built: machine learning (ML) and deep learning.

We have all used AI, and have seen how powerful it can be but do we really know what it consists of, below we will try our best to explain that.

## AI Technologies Include:
* Autonomous vehicles         
* Biometrics
* Chatbots      
* Facial and voice recognition 
* Image generation 
* Digital Assistants 
* Generative AI tools 
* GPS navigation 
* Personalized marketing and many more

---
---

## Fundamental Components of AI

**Data: -** AI systems learn and make decisions based on data, and they require large quantities of information to train effectively, especially for machine learning (ML) models.

**Algorithms: -** Algorithms are the sets of rules AI systems use to process data and make decisions. Machine learning algorithms, for instance, learn and make predictions and decisions without explicit programming.

**Computing Power: -** AI algorithms often need significant computing resources to process large quantities of data and run complex algorithms.

* As we seen above AI needs data to learn and be capable to make small decisions or give us answers to the prompts we put. There are multiple ways of to train AI, but we will look at the major three ones:-
---
* But first we need to know what training AI actually means; We can compare an AI with a child on how it trains to understand things:-
---
| AI | A Child |
| --- | --- |
| *Given a massive amount of data to amke it remember* | *Exposed to an environment of people and materials* |
| *Decrease or increase the volume based on performance* | *Given postive reinforcement evrytime it does something good* |

* Modern LLMs (large language models), like ChatGPT, use what's called reinforcement learning from human feedback, RLHF, to train a reward model which then is used to train the language model.

* Basically, we attempt to instill an untrained model with weights selected through human preference (which looks more like a cat? which sentence is more polite?). This then automates the process and scales it to superhuman levels which are capable of training massive models like ChatGPT with hopefully something close to what the humans initially intended.

* AI training is the computational process of teaching an AI model to recognize patterns and logic within data. It transforms raw information like text, code, or images into intelligence, enabling the AI to perform tasks it wasn't explicitly programmed for-such as reasoning, problem-solving, and content generation.

* AI models have varied intelligence, but it is not just model specific, it also happens within different versions of a model based and we classify it as:-

    ##                     1. Narrow AI(Weak AI).

* Weak AI, or Artificial Narrow Intelligence (ANI), refers to those systems that are designed to perform specific tasks or solve particular problems within a defined scope—they cannot think or make decisions beyond them. Unlike humans, who can apply intelligence across different situations, Narrow AI operates under set constraints without general cognitive abilities.

* A great exaple would be the algorithm that recommends us the videos we watch.

    ##                      2. General AI(Strong AI),

* Unlike the previous one, this one posseses the ability to think to apply previous information to a new situation it stumbles on.

* The amusing thing is still a concept and hasn't been made yet.

    ##                      3. Superintelligent AI.

* This introduces a level of intelligence that surpasses human intelligence, and we be able to solve most of everything.

* This is also hypothetical.

---

* Also we classify AI based on fuctionalities, as: -

    ##                      1. Reactive Machines.

* Reactive machine AI refers to the most basic level of artificial intelligence. These systems respond to specific inputs with predetermined outputs without the ability to store data or learn from past experiences. They are designed to react in real time, making them effective for straightforward tasks. 

* A great example for these will also be YouTube's search engine.

    ##                      2. Limited Memory AI.

* Unlike the previous one this model will be able to store data to help it "evolve" or learn.

* Self-driving cars are under this category of AI.

    ##                      3. Theory of Mind AI

* This is an AI in the works with an aim of to understand human cues and emotions.

* If someone yells at Google Maps out of frustration, it will still deliver the same traffic updates without offering reassurance or support. However, advancements like ChatGPT are beginning to improve in this regard.

    ##                      4. Self-Aware AI.

* This a stage of AI that we see in movies or read about in books, where an AI model would possess cosciousness.
___
___

* **There are three stages of AI training where the AI slowly develops: -**

    ##                                     1. Pre - Training Phase.

* Pre training is the initial, large-scale learning phase in which a model is trained on massive, general-purpose datasets-such as text, images, audio, or video-to learn broad patterns and representations. This phase draws heavily on advances in machine learning theory and large-scale distributed systems.

* At this stage the AI gets the basic knowledge it has, such as understanding different languages, recognizing images, and it will be able to identify any relationship between datas. This stage looks a lot like how child grows into his/her environment.

* This stage is resource-intensive and only done once to build the foundation or the base. 

* At this stage the AI can do most of the things it is suppose to do, and one of maybe the most usefull ones is, token-prediction, where the AI predicts the next word or character helping the process be faster.

    ##                                     2. Post - Training Phase.

* Post training is the refining period where we suit the AI for a specific task or domain. At this point the only thing we need to do is fine-tuning where we add restrictions, TOS, and customer service.

* The AI is given human-crafted prompts to tune its conversation capability and safety.

* If pretraining is like teaching a model foundational skills in school, post-training is job training. For example, a large language model can be post-trained to perform sentiment analysis, translation, or understanding of domain-specific language in fields like healthcare, law, or finance.

    ##                                     3. Reinforcement Learning From Human Feedback(RLHF).

* Humans rank different AI responses. A reward model uses these rankings to teach the AI which answers are accurate, helpful and safe.
---

* But while doing this there are three methods to train the AI, which are: -

    ##                                      1. Supervised Learning.

* This a machine learning technique where an algorithm is trained from labeled data, like a flashcard that says "This is a person eating corn" matching inputs to known outputs.

* The machine learns mapping first where it maps the input and the outputs using a mathematical expression y=f(x), to map inputs "x" to outputs "y".

* The model compares its predictions against the ground truth lables and adjusts its internal parameters to minimize errors. We call this error adjustment.

* After this training is done the model uses its learned relations ships to predict and produce an output for a new, unseen data. We call this generalization.

---
---

* There are two main types of supervised learning: -

    ### 1. Classification.

* This predicts categorical discrete labels (male vs female, dog vs cat).

* When there are only two possible classes, we call it binary classification, when there is more than two classes we call it, multiclass classification.

* We use classification in email spam detection, image and object recognition and etcetra.

* As an example of supervised learning, consider an image classification model created to recognize images of vehicles and determine which type of vehicle they are. Such a model can power the CAPTCHA tests many websites use to detect spam bots.

    ### 2. Regression.

* Regression is used to understand the relationship between dependent and independent variables. In regression problems, the output is a continuous value, and models attempt to predict the target output.

* So basically its main goal is to predict a value or a quantity.

* It predicts and produces and value for a house price and salaries, etcetra.

* Supervised learning uses multiple alogorithms, those are : -

    #### 1. Linear and Logistic Regressions.

* Linear regression predicts continuous numerical values along a straight line, while logistic regression predicts categorical (binary) probabilities along an S-shaped curve.
    
    * Linear regression uses a continuous metric output (like price, temperature, or salary).
    * Logistic regression uses a categorical or binary output (like yes/no, pass/fail, or spam/not spam).

    #### 2. Decision Tree and Random Forest.

* **Decision tree** is a single model, while a random forest is an ensemble model made up of many individual decision trees working together.

* Decision tree starts from a single node and splits it to the feature that provides the cleanest separations until it reaches a leaf node which then gives the final prediction. It is easy to visualize and kind of mimics human decision making but it is also prone to overfitting and makes up new data.

* A **Random Forest** fixes the flaws of a single decision tree by creating a "forest" of many independent trees (often hundreds) and aggregating their answers. It relies on the concept that a collective crowd of average models will outperform a single "expert" model.

    * **Bootstrapping (Bagging): -** Each tree is trained on a random sample of the rows from the dataset, sampled with replacement.
    * **Feature Randomness: -** When a tree splits a node, it is only allowed to choose from a random subset of features (columns) rather than evaluating all of them.

* Random forest is highly accurate and immune to overfitting but yet so complicated.

    #### 3. Support Vector Machines (SVMs).

* It seoarates different classes of data in an N-dimensional space while maximizing the distance between the classes.

    * **Hyperplane: -** This is the decision boundary that divides the data classes. In a 2D space, the hyperplane is a simple line; in a 3D space, it is a 2D plane; and in higher dimensions, it becomes an N-dimensional hyperplane.

    * **Support Vectors: -** These are the data points that lie closest to the hyperplane. They are the most critical points in the dataset because they define the orientation and position of the decision boundary. If you remove these points, the position of the hyperplane changes.

    * **Margin: -** This is the distance between the hyperplane and the nearest data points (the support vectors). SVM aims to achieve a maximum-margin hyperplane, meaning it maximizes this gap to ensure the model generalizes well to new, unseen data.

    #### 4. K-Nearest Neighbours.

    * It assumes that similar data points exist close to one another in a feature space.

    * So it measure the distance between the query point and every stored training example using a chosen distance metric.

    * It identifies the k training examples closest to the query point. And after that it will make a prediction.

    #### 5. Gradient Boosting.

    * It builds a sequential models to fix the errors prior iteriations.

    * Basically this builds a strong predictive model by leaving the errors and mistakes(psudo-residuals) of the previous model.

    ## Unsupervised Learning.

* It is a machine learning method where algorithms discover patterns, structures and identify relationships with unlabeled data or predefined outputs without human intervention.


* Unlike supervised learning, in unsupervised learning an algorithm is made to find hidden patterns and relationships based on inherent similarities or even differences.

* The algorithm is given a massive amount of data, without any predefined lables or categories. After that, the algorithm looks for small intricit similarities or hidden patterns within the given set of data so it can match them.

* **There are three algorithms for unsupervised learning.**
 ### 1. Clustering.

* Clustering is a techinique in unsupervised learning where that groups unlableded data to groups based on their similarities.

* Its biggest job is to let us understand a data structure for a later use.

    ### 2. Association Based Learning.

* It is a techinique in unsupervised learning that is rule-based, where it finds interesting relationships between large datasets.

* It identifies patterns interms of if-then rules, showing how the presesnce of one implies the presence of the others.

* So, a person is buying shoes, it is highly likely that the person will buy socks too.

    ### 3. Dimensionality Reduction.

* It is a process of decreasing the number of variables in a dataset while still retaining the original information. This method avoids redundancey and speedup computation time.

* It is really helpful in spotting suspicious actions like fraud and the similar by spotting the odd one out of a dataset.

* It is also really helpful in customer segmentation, where the algorithm classifies the customer base through their demographics and purchasing habits.

* **Unsupervised learning is really useful when it comes to saving time but also really challenging since the model can pickup noises rather than real data from the dataset leading to overfitting.**


    # Machine Learning.

* A simple way to think about AI is as a series of nested or derivative concepts that have emerged over more than 70 years:

* Directly underneath AI, we have machine learning, which involves creating models by training an algorithm to make predictions or decisions based on data. It encompasses a broad range of techniques that enable computers to learn from and make inferences based on data without being explicitly programmed for specific tasks.

* The central premise of machine learning (ML) is that if you optimize a model’s performance on a dataset of tasks that adequately resemble the real-world problems it will be used for—through a process called model training—the model can make accurate predictions on the new data it sees in its ultimate use case.

* Nowadays many AI models are used for extensive kind of things from really useful tasks to weridly as "companions", this is where ML comes in handy.

* Training itself is simply a means to an end: generalization, the translation of strong performance on training data to useful results in real-world scenarios, is the fundamental goal of machine learning. In essence, a trained model is applying patterns it learned from training data to infer the correct output for a real-world task: the deployment of an AI model is therefore called AI inference.

* **AI Inference: -** Is the operatioanl phase where an AI model processes a new unseen data to generate real time predictions, classifiactions or texts. This is explained extensively above.

* Machine learning is also associated with several other artificial intelligence subfields: -

    ##                      Deep Learning.

* It is a specialized subset of machine learning that uses multilayered artificial neural networks to automatically learn complex patterns and representations from raw, unstructured data.

* The term **"Deep"** refers to the multitiude of hidden layers used, ranging from three to hundreds to thousands that allow computersto solve intricate problems without manual feature engineering.

    ##                      Natural Language Processing.

* Natural language processing is a field of machine learning in which machines learn to understand natural language as spoken and written by humans, instead of the data and numbers normally used to program computers. This allows machines to recognize language, understand it, and respond to it, as well as create new text and translate between languages. Natural language processing enables familiar technology like chatbots and digital assistants like Siri or Alexa.

    ##                      Neural Network.

* A neural network is a machine learning model that stacks simple "neurons" in layers and learns pattern-recognizing weights and biases from data to map inputs to outputs.

* While today’s deep neural networks (DNNs) power systems as complex as transformers and convolutional neural networks (CNNs), the origins of neural networks trace back to simple models such as linear regression and how the human brain digests, processes and decides on the information presented to it.

* On a high level, the inspiration for neural networks comes from the biological neurons in the human brain, which communicate through electrical signals.

* A neural network can be understood through a simple example: spam detection. An email is fed into the network, and features such as words or phrases like “prize,” “money,” “dear” or “win” are used as inputs. The early neurons in the network process the importance of each signal, while later layers combine this information into higher-level cues that capture context and tone.

* In essence, the network learns how to transform raw features into meaningful patterns and use them to make predictions. This process is powered by two fundamental concepts: weights and biases.

* **Weigths: -** Weights act like dials that control how strongly each input feature influences the decision—a word like “prize” may be given more weight than a common word like “hello.”

* **Biases: -** These are built-in values that influence the decision threshold allowing a neuron to activate even if the inputs are weak.

* Together, these model parameters determine how each neuron contributes to the overall computation. By adjusting these values during training, the network gradually learns to make accurate predictions. For example, it woll be able to determine if an email is really a phishing email or a legitimate one, that why sometimes even legitimate emails end up the smap or junk folder.

* A neural netwrok is composed of: -

     **Input Layer: -** This holds the raw features.
     **Hidden Layes: -** Consists of artificial neurons (or nodes) that transform inputs into new representations. This is where the linear transformation between input and output happens.
     **Output Layer: -** After performing the linear transformation in the hidden layer, a final prediction is made.

* A neural network has a "neuron" for each input (each of the pixels of the images) and a neuron for each output (each of the 10 possible digits).

* A basic neural network just connects each input neuron to each output neuron, and so each input effectively votes directly for which output it thinks is right. For recognizing digits, a pixel right in the center being "on" could be a lot of things, but is almost certainly not a 0.

* So, the connection between the pixel and the zero is weighted low, and is weighted something higher for the rest of the outputs.

* The real beauty of machine learning is that we let it figure stuff out and if it correctly guesses or predicts, we give it some kind of reinforcement, slightly increasing those weigthed votes, and if it gets it wrong we correct it so it can lower those weighted votes.

* The different thing about Neural Nework is, we can actually ramp it up, unlike the other learning approaches, by increasing the number of hidden layers which basically means adding more computing resources to it.

* The downside lies on the complexity of the result they give us, it is a complext combination of numbers which can lead a person to solve a problem they don't understand, with a solution that they don't understand.

*   But for a model to learn from data it need three core steps: -

    ###                     1. Forward Propagation

*   Data flows forward from the input layer, through hidden layers, to the output layer.

*   So first the model performs **Linear Combiantion**, where each neuron calculates a weighted sums of the inputs and adds the bias.

*   Then it performs **Activation Function**, where a non-linear function like the ReLU, Sigmoid or Tanh are added to the sum to introuduce non-linearity and generate the neuron's output (activation).

| ReLu | Sigmoid | Tanh |
| :--- | :--- | :--- |
| Outputs the input directly if it is positive, if not the output is zero. | Compresses real valued numbers into probability-like scale between 0 and 1. | Concentrarted the value around zero in an shaped curve so it will be easier for weight updates, since the convergence will be around zero. |

* Lastly, it gives us a **Final Output**, where the process repeats again and again until the final layer produces a predicition.

    ###                     2. Loss Calculation.

* This is the stage where error measurment is performed. At this stage the model measures compares its predicted output( let's call it y') to the true target output(y) using a loss function or cost function to quantify its deviation from the true output or how wrong it is.

* The entire training objective is to minimize this loss value.

    ###                     3. Backpropagation.

* At thi stage what happnes is backpropagation moves backwards to see how much each weight and bias contributed to the error.

* This pinpoints where it got it wrong so it will be easier to minimize it on the next rodeo.

    ###                     Tyoes Of Neural Networks.

* **Convolutional neural networks (CNNs or convnets): -** Designed for grid-like data such as images. CNNs excel at image recognition, computer vision and facial recognition thanks to convolutional filters that detect spatial hierarchies of features. 

* **Recurrent neural networks (RNNs): -** Incorporate feedback loops that allow information to persist across time steps. RNNs are well-suited for speech recognition, time series forecasting and sequential data. 

* **Transformers: -** A modern architecture that replaced RNNs for many sequence tasks. Transformers leverage attention mechanisms to capture dependencies in natural language processing (NLP) and power state-of-the-art models like GPT. 

* Regardless of architecture, all of the above rely on core principles: - *Artificial Neurons, nonlinear activations and optimization algorithms.*

##                          How Deep Learning Works.

* We have see the Artificial Neural Networks(ANNs) above but lets expand on the others too: -

* **Hierarchial Feature Learning: -** The early layers detect the smaller details like edges and pixels, the middle layers combine those to make shapes or textures, and deep layers recognize high-level concepts like faces and objects.

* As we mentioned above models also train via backpropagation which is really useful in detecting mistakes by literally back-tracking and trying to pinpoint them.

* But one of teach and money savy operation is: - **Hardware Acceleration,** it is basically using massive amounts of specialized GPUs and processors to perform tasks that are repetative and making the process of the neural netwrok faster than standard CPUs.

* This process is really important in speeding up processes like forward propagation, loss calculation and backproagation since they need to be done million, if not billions of times.


* Now lets get to the fun part, have you ever imagined how an AI models approaches human intelligence. It is all about mimicking the human brain but not about replecating it, so there must be a way or two or even three to mimic human intelligence, however great it is. The next part walks us through one of the approaches a model mimic human intelligence.

