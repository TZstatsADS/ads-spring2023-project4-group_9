# Project 4: Machine Learning Fairness

### [Project Description](doc/project4_desc.md)

Term: Spring 2023

+ Team 9
+ Projec title: Implementation and comparison of two ML fairness algorithms
+ Team members
	+ Liu, Yunfan 
	+ Shi, Mingrui 
	+ Tang, Qingyang 
	+ Zhang, Haoyu 
	+ Zhang, Zerui 
+ Project summary: In this project, we implemented fairness algorithms in two papers:Fairness-aware Classifier with Prejudice Remover Regularizer (A5) and Handling Conditional Discrimination(A6). We applied the algorithms to COMPAS dataset to see which algorithm has a higher accuracy and also gives fairer results. The result shows that Local messaging (A6 LM) performs best in accuracy and calibration trade off and is generally the best one. Prejudice Remover Regularizer (A5) reduces calibration to nearly 0, but sacrifices too much accuracy. It can be used when calibration is extremely important.




	

**Contribution statement**: [default] All team members contributed equally in all stages of this project. All team members approve our work presented in this GitHub repository including this contributions statement. 

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
