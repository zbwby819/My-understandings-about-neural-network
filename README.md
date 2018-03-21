# My-understandings-about-neural-network
  I write my understandings about deep learning in this repository.  
  Convlayers are learnable mapping fuctions which map the data within raw redundant pixel input space to lower-level contractive feature space. Well trained conv layers will cluster image data with same labels condensedly in the feature space at the same time introduce invariance within intra and equivariance externally . (Invariance: a man face left/right is man Equivariance: a man in the left/right part of the image)      
    
  Currently I focus on AGI and understanding the limitations on neural networks.Even though deep learning has achieved astonishing achievements we can't imagine ten years ago, and it seems to be the most likely path leading to AGI currently. But as I dive deeper to it, I find AGI is far more beyond deep learning and more worthy for me to pursuit.   
  
  One sentence conclusion: Neural network is a nonlinear mapping of Y=f(X), where X can be anything(Images,Voice,Words,etc) described by data with Y as corresponding labels and the function f can be learned autonomously with back-propagation,during testing a sample X'(same/similar to X) will be mapped to the label Y using learned function f.  
  
 
  Limitations:  
  • Very data hungry (The Curse of dimensionality) Check link:http://www.visiondummy.com/2014/04/curse-dimensionality-affect-classification/   
  • Computationally intensive to train and deploy (tractably requires GPUs)  
  • Easily fooled by adversarial examples  
  • Finicky to optimize: non-convex, choice of architecture, learning parameters  
  • Often require expert knowledge to design, fine tune architectures  
  
  Frontiers:  
  • Bayesian neural network  
  • Learning to learn  
  
