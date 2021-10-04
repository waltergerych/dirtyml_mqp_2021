# Meeting Notes 9/28/21  
  

Attendees:  
- Elke Rundensteiner
- Walter Gerych  
-  Ryan Astor  
-  Kyle Costello  
- Joshua DeOliveira  
- Alek Lewis  
  

## Last Week’s Summary  
  

Last meeting we discussed the team's progress. 
- GAN implementation debugging
- Writing plan on-track

Elke: Bar chart describing the bar chart listing the sections and sub-sections across categories: not done, 90% done, rough draft, peer reviewed.

## This Week's Accomplishments  

### Background Introduction 

The team has brainstormed all the necessary information for finishing the background and introduction. We can send to Walter soon for a review while we write. 

- Walter and Elke can spend time giving high level advice about section addtions/removal and reordering.

### Novel GAN Training Approaches to Consider
#### Dynamic Training
The generator and discriminator alternate training based on variable intervals depedent of fpR of discriminator. See previous meeting notes for more info.

#### 2 Discriminators
The two discriminators are trained at the same when conventionally only the discriminator would learn. 
GANs have trouble converging to a stable endpoint. More, less trained discriminators may give better advice to the generator.   

Independent of architecture, loss, regularizations, and procedure (static epoch ratio, dynamic training). The two discriminators have 2 diffferent learning rates. Inspired by found paper in which multiple generators, each designed to mode collapse on a subset of the dataset, train with respect to the same discriminator. 

Elke: Separate the idea from the implementation. Make everything else simple first, compare to basecase primarily. 

Walter: Interesting. One issue of GAN training is that the discriminator can find trvial difference between real and fake data. Deciding answer on inperceptable data. A draw that synthesisis a high dimensional space than the draw, the data is going to lie on a very thin "slice" of the space.    
A slower moving discriminator has a better chance learning about the real data. 

#### F-Divergent Generators and Conjugates
See what divergence metric as a loss function works best from what we are trying to do. 
- Kullback-Leibler
- Hellinger
- Jenson-Shannon
- Pearson Square
- Chi Square
- Wasserstein
- Bregman

### Evaluation Metric
- Clock time of GAN training per epoch.
- Complexity of training time per epoch.
- Parzen Window Log Likelihood. 
- Frechet Inception Distance
