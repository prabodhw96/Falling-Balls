# Falling Balls + Q-Learning
## Overview
A demo of DQN agent that learns to dodge falling balls.<br>
Every frame, the agent senses the environment through raycasting.<br>
It receives a reward of +1 for surviving and -1 for dying.<br>
<center><img src="https://raw.githubusercontent.com/prabodhw96/Falling-Balls/master/dqn.gif" width="500" height="400" /></center>
## Dependencies
* [Matter.js](http://brm.io/matter-js/) is a 2D rigid body JavaScript physics engine for the web.
* [Tensorflow.js](https://js.tensorflow.org/) is used for building neural network.
## References
[Webpage](http://web.sfc.keio.ac.jp/~t15704yn/falling/index.html)
## Credits
The credit for this code goes to [sean999](https://github.com/seann999/dodge_tfjs). This is my try to learn to use tensorflow.js to define, train and run machine learning models entirely in the browser.