# Meeting Notes 9/9/21

Attendees:
- Walter Gerych
-  Ryan Astor
-  Kyle Costello
- Joshua DeOliveira
- Alek Lewis

## Last Week’s Summary

Last meeting we discussed the team's progress installing Anaconda, Jupyter notebooks, and pyTorch. Now, the team overall has a good understanding of how to ustilize these packages, war tensors are, and where to find documentation for reference. 

Everyone has read the papers on the original and conditional GAN, and was introduced to one proposed training method: dynamic training. Our plans were to finish reading the reamaining assigned papers (controllable & explicitly controllable GANs) and begin a more in-depth literature review of GAN architectures and the novel training strategies proposed for these methods.

## This Week's Accomplishments
### PyTorch Blitz Tutorial & GAN Implementation
The team is in the process of completing the pyTorch tutorial.
### Literature Review
GANs have been growing in attention by proxy of the more and more papers that are coming out in recent years. These papers focus on different architectures, loss functions, overall training strategy, measurement of generation quality, and analysis of convergence to better understand GANs in various applied and theoretical settings. Two papers we specifically discussed were the Geometric GAN: an architecutre in which the loss function is styles through the perspective of max/min the margin of a soft-margin SVM, and the Progressive GAN: an architecture for image synthesis in which the generator iteratively generates larger images by appending an iteratively larger fully connected layer onto the end of it while training. 

One well cited (+600) paper from 2018 served as a review of GAN training strategies by compiling the most notable approaches since 2014 and comparing them under different synthetic data sets as well as studying their convergent properties. This paper can serve as a role model for how to structure experiments comparing of training strategies emprically, explaining the high-level takeaways from the experiments, as well as the structure for proving and/or analysing the a method's convergence (ie. a lot of math).  

[Mescheder, Lars, et al. "Which Training Methods for GANs do actually Converge?](https://arxiv.org/pdf/1801.04406.pdf) 


_See the "Relevant Papers" section in README.md in the root directory for a full list of the papers our team plans on examining further_.  

 Walter also mentioned looking into Maximum Discrepency GANS as well as Bregmen Divergence GANs (requires looking into "density ratio distributions").

## Next Steps
   - Prepare presentation for Elke by next Tuesday
   - Implementing a simple GAN from scratch. A GAN implementation tutorial is also available online using pyTorch as well as an example GAN in the _demo_  directory.
   - Categorize novel GAN training strategies for better understanding of the approaches and/or independence of these strategies.
	   - Where does dynamic training fit into this?
	- Complete reading the background papers as well as continue reading the newly discovered papers in the beginning of the literature review.  
