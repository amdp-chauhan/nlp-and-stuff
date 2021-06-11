# Chat bot projects:

1. QA Bot:
	
	- Dataset:
		We are using (Babi Data Set from Facebook Research)[https://research.fb.com/downloads/babi/]
	
	- Followed Paper: 
		"Towards AI-Complete Question Answering: A Set of Prerequisite Toy Tasks",
		http://arxiv.org/abs/1502.05698
		By - Jason Weston, Antoine Bordes, Sumit Chopra, Tomas Mikolov, Alexander M. Rush
  
	- Network used:
		End-to-End Memory Network[https://arxiv.org/pdf/1503.08895v4.pdf] 
		Created using RNN and Multiple Layers.
		By - Sainbayer Sukhbaatar, Arthur Szlam, Jason Weston, Rob Fergus
		
	- Working:
		- Model takes a discrete set of inputs x1, x2, ..., xn that are to be stored in the memory, a query 'q', and outputs and answer 'a'.
		- Each of the 'x', 'q', and 'a' contains symbols coming from a dictionary with 'V' number of words.
		- The model writes all x to the membory up to a fixed bugger size, and then finds a continious representation of the 'x' and 'q'.

	- Model Components:
		- Input Memory Representation.
		- Output Memory Representation.
		- Generating Final Prediction.

	
	- Architecture:
		Put Image
		
		
		
		
		
		