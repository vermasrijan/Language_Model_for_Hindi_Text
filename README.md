# Language_Model_for_Hindi_Text

![](https://cdn57.androidauthority.net/wp-content/uploads/2017/06/gboard_multiple_prediction_1.gif)

Word-Based Neural Language Model in Python with Keras (for hindi sentences). <br/>
To be able to predict the next set of words, given some input of hindi words .<br/>

## Specification of the Keras Model Used: - <br/>
1. One embedding layer, vector size = 10

2. One hidden layer, having 'LSTM' functionality. It has 50 neurons.

![](https://cdn-images-1.medium.com/max/1600/1*n-IgHZM5baBUjq0T7RYDBw.gif)

Explanation of LSTM given in [this](https://towardsdatascience.com/illustrated-guide-to-lstms-and-gru-s-a-step-by-step-explanation-44e9eb85bf21) blog is really good!

3. One dense layer having 'softmax' activation.

4.  Keras [Sequential()](https://keras.io/getting-started/sequential-model-guide/) Model is used .

## Acknowledgements
A big Thank you to the whole team of [Messy Fractals](https://messyfractals.wordpress.com/), especially [Dhanya P](https://www.linkedin.com/in/dhanyap/?originalSubdomain=in) and [Arvind Sivdas](https://www.linkedin.com/in/arvindsivdas/?originalSubdomain=in) for letting me work under them, for this project . <br/>

## References
This code has been inspired from the blog given [here](https://machinelearningmastery.com/develop-word-based-neural-language-models-python-keras/). Thank you [Jason Brownlee](https://machinelearningmastery.com/about/)!
