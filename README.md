![Ironhack logo](https://i.imgur.com/1QgrNNw.png)

# Machine Learning Day

## Introduction
In the same way as in the Analysis Day, today you will face a case with your team and then you will share it with your partners.
The idea is to know a little bit better three fields that Machine Learning covers:
* Neural networks - a specific family of algorithms that we are sure you have heard about them.
* Natural language processing - the algorithms that try to understand our language.
* Graphs algorithms - a mathematical concept useful to understand social networks.

Your team will be assigned to one of the topics and you will go through a lesson and a basic project. After that, you will present both to your partners so they understand a little bit the theory and how did you put it into practice.
Don't hesitate to go further and do some research!

Also, you will use new specific python libraries, this is very important to:
* Know for what those libraries are built.
* Have an introduction to them.

In total you have 3 hours until you have to present.

## The topics
### Neural networks
You will be introduced to this famous field through the [Martin Gorner talk](https://www.youtube.com/watch?v=u4alGiomYP4), from Google. It's about an hour long and it covers also Convolutional Neuran Networks and deep mathematical concepts so arrive until the point you want.
Also, he uses the Tensorflow library so you can see all the possibilities it has.
After seeing the video, you will do your first image classification with TensorFlow following the [tutorial in TF](https://www.tensorflow.org/beta/tutorials/keras/basic_classification).


### Natural language processing (NLP)
You will be introduced to this well known field through the [Chris Manning's lecture](https://www.youtube.com/watch?v=OQQ-W_63UgQ) in Stanford University. It's about an hour and it covers deep mathematical concepts in the end so don't go crazy and stop whenever you need to.
After that, you will be driven through a [sentiment analysis](https://towardsdatascience.com/a-practitioners-guide-to-natural-language-processing-part-i-processing-understanding-text-9f4abfd13e72) thank to Dipanjan (DJ) Sarkar. Don't do the scrapping part, just download the dataset form his repository (you have the link in the end of the article)



### Reinforcement learning
You will be introduced to this amazing field with the [David Silver's lecture](https://www.youtube.com/watch?v=2pWv7GOvuf0) from DeepMind. You will only need to see the first 40' (in the rest he starts with deep mathematical concepts so just leave it for the future if you want).
After that, you will teach a taxi how to drop-on and off passengers with the [Satwik Kansa and Brendan Martin tutorial](https://www.learndatasci.com/tutorials/reinforcement-q-learning-scratch-python-openai-gym/)

Note: in the code, you may have an error in this cell:
```from IPython.display import clear_output
from time import sleep

def print_frames(frames):
    for i, frame in enumerate(frames):
        clear_output(wait=True)
        print(frame['frame'].get_values()
        print(f"Timestep: {i + 1}")
        print(f"State: {frame['state']}")
        print(f"Action: {frame['action']}")
        print(f"Reward: {frame['reward']}")
        sleep(.1)
        
print_frames(frames)
```

To fix it, just remove the `get_values` function

## The presentation
* You have 10 minutes to present and 10 minutes for questions/debate
* As a schema for your presentation you will cover:
  * A simple explanation of your topic 
  * A use case (your tutorial)
  * Some examples of applications
  * Some companies that use it and how
  * Limitations 
  * Technologies, libraries used
  * Resources, articles you read

## Further readings

[(RL) Solving the gridworld task](https://towardsdatascience.com/reinforcement-learning-rl-101-with-python-e1aa0d37d43b)
[(RL) Various algorithms](https://towardsdatascience.com/introduction-to-various-reinforcement-learning-algorithms-i-q-learning-sarsa-dqn-ddpg-72a5e0cb6287)
