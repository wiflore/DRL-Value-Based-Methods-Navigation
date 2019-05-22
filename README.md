# DRL-Value-Based-Methods-Navigation
Deep Learning agent that navigate in a virtual world and collect as many yellow bananas as possible while avoiding blue bananas in a large, square world. 

<img src="https://s3.amazonaws.com/video.udacity-data.com/topher/2018/June/5b1ab4b0_banana/banana.gif" alt="" width="400px" class="index--image--1wh9w">

### Project Overview  
For this project, you will train an agent to navigate (and collect bananas!) in a large, square world.

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:  


<ul>
<li><strong><code>0</code></strong> - move forward.</li>
<li><strong><code>1</code></strong> - move backward.</li>
<li><strong><code>2</code></strong> - turn left.</li>
<li><strong><code>3</code></strong> - turn right.</li>
</ul>

The task is episodic, and in order to solve the environment, The agent get an average score of +13 over 100 consecutive episodes.

### Instructions

<ol>
<li>
<p>Download the environment from one of the links below.  You need only select the environment that matches your operating system:</p>
<ul>
<li>Linux: <a href="https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip" rel="nofollow">click here</a></li>
<li>Mac OSX: <a href="https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip" rel="nofollow">click here</a></li>
<li>Windows (32-bit): <a href="https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip" rel="nofollow">click here</a></li>
<li>Windows (64-bit): <a href="https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip" rel="nofollow">click here</a></li>
</ul>
<p>(<em>For Windows users</em>) Check out <a href="https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64" rel="nofollow">this link</a> if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.</p>
<p>(<em>For AWS</em>) If you'd like to train the agent on AWS (and have not <a href="https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md">enabled a virtual screen</a>), then please use <a href="https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip" rel="nofollow">this link</a> to obtain the environment.</p>
</li>
<li>
<p>Place the file in the DRLND GitHub repository, in the <code>p1_navigation/</code> folder, and unzip (or decompress) the file.</p>
</li>
</ol>

Once you setup the enviroment open the Navigation.ipynb file. This file has five parts:

  1. Start the Environment
  2. Examine the State and Action Spaces 
  3. Take Random Actions in the Environment  
  4. Train the Agent with DQN  
  5. Test Smart Agent!  
  

if you want to see check the results run part 1, 2, 3 and 5. If you want to train the agent you must run also part 4. 

Enjoy it. 

## Potential improvement  
Implement Rainbow and double DQN, a dueling DQN, and/or prioritized experience replay.

## Licensing, Authors, Acknowledgements, etc.
MIT

