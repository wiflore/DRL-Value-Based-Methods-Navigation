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


<div class="_main--content-container--ILkoI"><div><div class="index--container--2OwOl"><div class="index--atom--lmAIo layout--content--3Smmq"><div class="ltr"><div class="index-module--markdown--2MdcR ureact-markdown "><h1 id="the-environment">The Environment</h1>
</div></div><span></span></div></div></div><div><div class="index--container--2OwOl"><div class="index--atom--lmAIo layout--content--3Smmq"><div class="ltr"><div class="index-module--markdown--2MdcR ureact-markdown "><p>Follow the instructions below to explore the environment on your own machine!  You will also learn how to use the Python API to control your agent.</p>
<h2 id="step-1-clone-the-drlnd-repository">Step 1: Clone DRLND Repository </h2>
<hr>
<p>Please follow the <a target="_blank" href="https://github.com/udacity/deep-reinforcement-learning#dependencies">instructions in the DRLND GitHub repository</a> to set up your Python environment. These instructions can be found in <code>README.md</code> at the root of the repository.  By following these instructions, you will install PyTorch, the ML-Agents toolkit, and a few more Python packages required to clone the project.  </p>
  
<p>(<em>For Windows users</em>) The ML-Agents toolkit supports Windows 10. While it might be possible to run the ML-Agents toolkit using other versions of Windows, it has not been tested on other versions. Furthermore, the ML-Agents toolkit has not been tested on a Windows VM such as Bootcamp or Parallels.  </p>

<p>Use requirement.txt file to install all libraries requires to the project  </p>

<h2 id="step-2-download-the-unity-environment">Step 2: Download the Unity Environment</h2>
<hr>
<p>For this project, you will <strong>not</strong> need to install Unity - this is because we have already built the environment for you, and you can download it from one of the links below.  You need only select the environment that matches your operating system:</p>
<ul>
<li>Linux: <a target="_blank" href="https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip">click here</a></li>
<li>Mac OSX: <a target="_blank" href="https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip">click here</a></li>
<li>Windows (32-bit): <a target="_blank" href="https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip">click here</a></li>
<li>Windows (64-bit): <a target="_blank" href="https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip">click here</a></li>
</ul>
<p>Then, place the file in the <code>p1_navigation/</code> folder in the DRLND GitHub repository, and unzip (or decompress) the file.</p>
<p>(<em>For Windows users</em>) Check out <a target="_blank" href="https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64">this link</a> if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.</p>
<p>(<em>For AWS</em>) If you'd like to train the agent on AWS (and have not <a target="_blank" href="https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md">enabled a virtual screen</a>), then please use <a target="_blank" href="https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip">this link</a> to obtain the "headless" version of the environment.  You will <strong>not</strong> be able to watch the agent without enabling a virtual screen, but you will be able to train the agent.  (<em>To watch the agent, you should follow the instructions to <a target="_blank" href="https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md">enable a virtual screen</a>, and then download the environment for the <strong>Linux</strong> operating system above.</em>)</p>
<h2 id="step-3-explore-the-environment">Step 3: Explore the Environment</h2>
<hr>
<p>After you have followed the instructions above, copy the file of this repo in the <code> p1_navigation folder </code>, then open the file <code>Navigation.ipynb</code> and follow the instructions. This file has five parts:

  1. Start the Environment
  2. Examine the State and Action Spaces 
  3. Take Random Actions in the Environment  
  4. Train the Agent with DQN  
  5. Test Smart Agent!  
  

if you want to see check the results run part 1, 2, 3 and 5. If you want to train the agent you must run also part 4. 

Enjoy it. 

  
  
  
  </p>
</div></div><span></span></div></div></div></div>

## Potential improvement  
Implement Rainbow and double DQN, a dueling DQN, and/or prioritized experience replay.

## Licensing, Authors, Acknowledgements, etc.
MIT

