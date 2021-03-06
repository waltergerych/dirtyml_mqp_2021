## ``Dirty Machine Learning" MQP

**Advisor**: Elke Rundensteiner, **Mentor**: Walter Gerych

Incomplete, messy data is ubiquitous in real-world applications. The focus of this MQP is on generative methods to combat this issue and “fill in” incomplete data. Specifically, we will be focusing on developing novel training strategies for generative models in order to achieve this task. 

This is your MQP and provides an opportunity to show off your skills. Whether your goal is industry or academia, the MQP is useful for applications. The Advisor and Mentor serve as guides during the MQP. While we will provide support and a general direction, we want all of you to bring your own ideas and seek out new directions. 

**Acknowledgments**: This page borrows heavily from resource created by ML Tlachac. 

------------------------------------------

### Expectations

-	15 to 20 hours per week of work
-	Two formal meetings per week: one with advisor and one with mentor. Prepare slides for both meetings 
-	**At least** one peer meeting per week
-	Stay in communication with team (slack)
-	Teach team members as requested
-	Experience with being term leader and/or note taker. Leader ensures all team members are on time with term deliverables. Note taker records ideas for each meeting to share with team

### Deliverables

-	MQP report, improved each term
    - includes literature review
    - write one part, edit one part
    - cite all sources 
    - write succinctly (less can be more!)
    - include appendix with your term contributions
    - Potential to extend MQP report to full conference paper
-	Weekly update slides and presentation (for both advisor meeting and mentor meeting)
    - Include setup (don’t assume we remember!), what you did, and what you plan to do
    - Always include your conclusions and/or proposed next steps as appropriate
    - Complete slides and include written summary if unavailable to meet
    - **Send draft of advisor slides 1 to mentor 1 day early**
-	Weekly meeting notes
-	Final presentation in D-term (poster or video as announced by the departments)
-	Term personal and team evaluations

### Evaluation

You will receive an individual grade. There are tangible and intangible contributions to the MQP team. You will be assessed on your ability to:
1.	define and meet project and personal goals
2.	problem solve and use feedback
3.	work independently and collaboratively
4.	communicate
5.	synthesize information and make conclusions

Further, we want you to demonstrate:
-	leadership and teamwork
-	academic integrity

### Important dates

- Advisor meetings
    - A term: 9am every Tuesday in Beckett conference room
- Mentor meetings
    - A term: 9am every Thursday in DS Innovation Lab (AK 013) 

### Resources 

Below you will find links to various resources that may aid in your MQP. We will periodically update this as the MQP progresses. 

**Relevant papers**
- Original GAN paper: https://arxiv.org/pdf/1406.2661.pdf
    - See videos on GANs in videos section prior to reading
- Conditional GAN: Mirza, Mehdi, and Simon Osindero. "Conditional generative adversarial nets.": https://arxiv.org/pdf/1411.1784.pdf
    - Generating data with specific properties 
- Controllable GANs:  Lee, Minhyeok, and Junhee Seok. "Controllable generative adversarial network.": https://arxiv.org/pdf/1708.00598.pdf
    - An improvement over conditional GANs
- Shoshan, Alon, et al. "GAN-Control: Explicitly Controllable GANs.": https://arxiv.org/pdf/2101.02477.pdf
    - Another controllable GAN paper
- Geometric GAN: Lim, Jae Hyun, et al. "Geometric GAN": https://arxiv.org/pdf/1705.02894.pdf
    - A loss function based off of SVM properties
- Invertible Conditional GANs for image editing: Guim Perarnau, Joost van de Weijer, Bogdan Raducanu, and Jose M. Álvarez. https://arxiv.org/pdf/1611.06355.pdf
    - Allows the reconstruction and modifications of real face images conditioning on arbitrary attributes
- Literature Compilation and Review: Mescheder, Lars, et al. "Which Training Methods for GANs do actually Converge?": https://arxiv.org/pdf/1801.04406.pdf
    - Review of loss functions / training methods published in previous GAN research (2018 and earlier) 
- Tseng, P. "Convergence of a Block Coordinate Descent
Method for Nondifferentiable Minimization": https://link.springer.com/content/pdf/10.1023/A:1017501703105.pdf
    - Heavily cited paper of properties about gradient descent. 
- Bohm, Axel, et. al. "Two steps at a time — taking GAN training in stride
with Tseng’s method": https://arxiv.org/pdf/2006.09033v1.pdf
    - Quantifying the convergence of GAN training methods under specfic conditions.
- Jayagopal, Tarun Narain (2021) VICE-GAN: Video Identity-Consistent Emotion Generative Adversarial Network.: http://essay.utwente.nl/88376/1/Jayagopal_MA_EEMCS.pdf
- Progressive Growing GANs: https://arxiv.org/abs/1710.10196
    - Stable training of image-generating GANs by steadily increasing the sizes of the images generated
- Lin, Tianyi, et al. "On Gradient Descent Ascent for Nonconvex-Concave
Minimax Problems": https://arxiv.org/pdf/1906.00331.pdf
    - Proof based convergence Analysis
- Dauphin, Yann, et al. "Identifying and attacking the saddle point
problem in high-dimensional non-convex optimization": https://ganguli-gang.stanford.edu/pdf/14.SaddlePoint.NIPS.pdf
- Multi-Agent Diverse GANs: Arnab Ghosh, Viveka Kulharia, Vinay P. Namboodiri, Philip H.S. Torr, Puneet K. Dokania; Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2018, pp. 8513-8521 https://openaccess.thecvf.com/content_cvpr_2018/html/Ghosh_Multi-Agent_Diverse_Generative_CVPR_2018_paper.html

**Relevant blog posts**

**Relevant videos** 
- Basics of machine learning: https://www.youtube.com/watch?v=ukzFI9rgwfU
- Basics of GANs: https://www.youtube.com/watch?v=-Upj_VhjTBs
- Overview of original GAN paper
    - https://www.youtube.com/watch?v=8L11aMN5KY8
    - https://www.youtube.com/watch?v=Gib_kiXgnvA

**Tutorials**
- Jupyter Tutorials
    - https://www.youtube.com/watch?v=HW29067qVWk
- Machine learning in Python
    - https://machinelearningmastery.com/machine-learning-in-python-step-by-step/
    - https://jakevdp.github.io/PythonDataScienceHandbook/05.02-introducing-scikit-learn.html
- Learning PyTorch
    - https://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html
- Building simple GAN in PyTorch
     - https://towardsdatascience.com/build-a-super-simple-gan-in-pytorch-54ba349920e4
- Building a conditional GAN in PyTorch: https://machinelearningmastery.com/how-to-develop-a-conditional-generative-adversarial-network-from-scratch/

**Tools** 
- Anaconda: https://www.anaconda.com/
    - Common Python distribution 
- Jupyter: https://jupyter.org/
    - For Deep Learning in Python
- Scikit-Learn: https://scikit-learn.org/stable/
    - Common Machine Learning package for Python
- Google scholar: https://scholar.google.com/
    - Great for literature reviews
    - Google Scholar button for quickly citing papers: https://chrome.google.com/webstore/detail/google-scholar-button/ldipcbpaocekfooobnbcddclnhejkcpn?hl=en

**Code Resources**
- PyTorch implementations of many types of GANs: https://cvnote.ddlee.cc/2019/09/25/gans-pytorch

------------------------------------------

### Tasks
Below we will lists tasks. Every student that should perform the task will have their name as a sub bullet under the task. Students should ~~strikethrough~~ their names after they have completed the task. Students are expected to add to this list of tasks themselves. 

- Watch Anaconda tutorial (in  Videos)
    - ~~Kyle~~
    - ~~Alek~~
    - ~~Ryan~~

- Install Anaconda
    - ~~Kyle~~
    - ~~Alek~~
    - ~~Ryan~~
    
- Install PyTorch
    - ~~Kyle~~
    - ~~Alek~~
    - ~~Ryan~~
    
- Do PyTorch 60 Minute Blitz Tutorial
    - ~~Kyle~~
    - ~~Alek~~
    - ~~Ryan~~

- Do "Machine Learning in Python" tutorials
    - Kyle
    - Alek
    - ~~Ryan~~

- Read original GAN paper
    - ~~Kyle~~
    - ~~Alek~~
    - ~~Ryan~~
    
- Create GitHub Repo for future code
    - ~~The team has decided to use this existing GitHub Repo.~~

- Create Slack page
    - ~~Kyle~~

- Organize existing GAN training code
    - ~~Josh~~
   
- Create slideset + documentation + tutorial for novel GAN training method
    - ~~Josh~~

- Create documentation + tutorial for novel GAN training method
    - ~~Josh~~ 

- Create slideset for Thursday Sep. 2nd meeting with Mentor. Summarize progress, give overview of papers read + coding tasks completed 
    - ~~Kyle~~
    - ~~Alek~~
    - ~~Ryan~~
    - ~~Josh~~
