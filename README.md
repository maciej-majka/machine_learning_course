# Excersises in Machine Learning and Neural Networks

This is a selection of projects, which I wrote for the course [Machine Learning for Physicist](https://pad.gwdg.de/s/Machine_Learning_For_Physicists_2021) by Florian Marquardt from FAU. (I could not recommend enough this course for its great learning materials and professionally recorded [lectures at YT](https://www.youtube.com/watch?v=qMp3s7D_8Xw&list=PLemsnf33Vij4eFWwtoQCrt9AHjLe3uo9_)!) The course makes heavy use of _NumPy_ (especially fast array operations and random number generation), _matplotlib_ for visualization, and _Keras_ for construction of Neural Networks (NN)

* ## Backpropagation
  This is implementation of NN and its teaching 'by hand', using NumPy's fast array operations. An image is probed randomly to generate teaching data. After enough teaching, NN can recreate the image on the regular mesh of points. Major components: 
  * implementatin of backpropagation algorithm
  * implementation of stochastic gradient descent + ADAM
  * visualizations

* ## Reinforced Learning
  In this code an agent is supposed to learn how to move through a maze in order to maximize the number of treasures found in the maze. A NN is used to determine the best move at the current position of the agent. NN is updated depending on the outcomes of previous runs of the agent. Major components:
  * implementation of maze generation algorithm (Wilson's loop-erasing algorithm)
  * simulation of agent movements through the maze
  * Neural Network teaching module
  * visualization of agent's path
    
_Although the code is working, it performs poorly. There may be bugs, which I did not find yet, the task needs the differnt structure of NN or maybe the concept itself is too simplistic._
  
