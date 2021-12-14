# Q-Learning Mountain Car

## Description
The Q-Learning Mountain Car is an example of Q-Learning in the OpenAI Gym environment. The value
learning method of argmax Q(s1, s2, a) is used to iteratively determine the Deep Q Learning method
to achieve the desired state (assuming it meets the criteria within the specified number of epochs).
Essentially in the example, the cart initially takes random values to set Q and randomly selects the 
first action to take to which it takes the reward. The reward is then taken and utilized to adjust
the current Q and the cycle continues. 

The Q-Learning Algorithm can be summarized as:
1. Initialize the parameters to which Q(s1, s2, and a) as random values
2. Observe the discrete state of the cart relative to the observation space
3. Based on a random number, decide a random action or take an action based on value learning of 
  argmax Q( s1, s2, a ) to determine the next action
4. Take the action and observe the result
5. Calculate the reward  
6. Check if the criteria is met to stop the algorithm
7. Adjust the Q(s1, s2, a) accordingly based on the learning rate, reward, and discount. 
8. Re-iterate through the steps of taking actions from Step 2 until Step 6 is met in which the 
   cart meets the goal or the maximum number of epoch have been taken

## Reference
https://towardsdatascience.com/getting-started-with-reinforcement-learning-and-open-ai-gym-c289aca874f 
