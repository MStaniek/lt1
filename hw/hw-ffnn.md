# LT1 Homework: Feedforward Neural Networks


Please email your solution to langtech1saarlandws1617@gmail.com with the subject header **Exercise FFNN**, by **15:00, January 18, 2016**.

## Task A: Basics
...


## Task B: Tensorflow Playground
Go to [Tensorflow Playground](http://playground.tensorflow.org) and play around with it for a little while.  You can start training by pressing the big 'play' button on the top left.  On simple datasets it should converge quickly, so you can pause training by pressing the same button.

1.  Starting with [this configuration](http://playground.tensorflow.org/#activation=tanh&batchSize=10&dataset=gauss&regDataset=reg-plane&learningRate=0.03&regularizationRate=0&noise=0&networkShape=4,2&seed=0.21483&showTestData=false&discretize=false&percTrainData=50&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=classification&initZero=false&hideText=false), try to find the smallest network that correctly classifies the data.
Notice that you can adjust the number of hidden layers, as well as the number of neurons within each layer, as well as the activation function, and others.
What are the main hyperparameters that you set?
You can additionally optionally share a link to the URL containing your setup.
How long did it take to converge?

2. Now change the dataset (in the middle-left of the page) to the *exclusive-or* dataset (top-left).
What is the smallest network architecture you can use to correctly classify the data?
What are the main hyperparameters that you set?
How long did it take to converge?

3. Same for the *circle* dataset.
What is the smallest network architecture you can use to correctly classify the data?
How long did it take to converge?
How does changing the activation function affect the results?
How does changing the batch size affect the results?
How does changing the learning rate affect the results?
How does changing the noise affect the results?

4. Same for the *spiral* dataset.  Also, what is the best test loss that you saw?
How stable is it using different restarts (button to the left of the play button)?
How does changing the activation function affect the results?
How does changing the batch size affect the results?
How does changing the learning rate affect the results?
How does changing the regularization & regularization rate affect the results?


## Task C: Software
...