# My-understandings-about-neural-network
  I write my understandings about deep learning in this repository. Most works are in the 'Some understandings about neural networks.pdf' file. 
  Currently I focus on adverisarial samples and the explainations of the limitations on neural network.Even though deep learning has achieved astonishing achievements we can't imagine ten years ago in many fields, and seems to be the most likely path leading to AI currently. But as I dive deeper to it, I can't convence myself anymore that DL = AI.   
  
  One sentence conclusion: Neural network is a nonlinear mapping of Y=f(X), where X can be anything(Images,Voice,Words,etc) described by data with Y as corresponding labels and the function f can be learned autonomously with back-propagation,during testing a sample X'(same/similar to X) will be mapped to the label Y using learned function f.  
  
 
  Limitations:  
  • Very data hungry (eg. often millions of examples)  
  • Computationally intensive to train and deploy (tractably requires GPUs)  
  • Easily fooled by adversarial examples  
  • Poor at representing uncertainty (how do you know what the model knows?)  
  • Uninterpretable black boxes, difficult to trust  
  • Finicky to optimize: non-convex, choice of architecture, learning parameters  
  • Often require expert knowledge to design, fine tune architectures  
  
  Frontiers:  
  • Bayesian neural network  
  • Learning to learn  
  
