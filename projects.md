---
layout: default
title: Projects.
---

[Home](/)

## Projects

### reco
*--Recommender Systems library*

A comprehensive python library of Recommender Systems with core modules of 
Collaborative Filtering, SVD, Factorization Machines, Wide and Deep
Networks, etc. 

Most of the underlying algorithms and processing has been written in cython for
maximum speed up. At the time of implementation, it had a faster runtime among its
counterparts of collaborative filtering, svd and factorization machines. 

Published package downloaded over 11k times on pypi.

[[code]](https://github.com/mayukh18/reco) [`Python`, `Numpy`, `Cython`, `Scipy`, `Tensorflow`]


### BlindChat 
*-- Flask based chat app on FB Messenger*

Built and launched a complete chat app in Flask on top of Facebook’s messenger APIs. 
Implemented server backend in Python and Flask with user data stored in SQL databases.
 
 It had over 1/2 million messages exchanged in 2017. Had to shut it down since it was getting
 too big to manage by myself.
 
 [[code]](https://github.com/mayukh18/BlindChat) [`Python`, `Flask`, `SQL`, `HTML`, `CSS`]


### CovidExplore 
*— exploring impacts of COVID*

Developed a minimalistic website that demonstrates the impacts of COVID through interactive
 visualizations based on bokeh. Scraped the data from various online resources reflecting
  the impact of COVID on different aspects of the world and environment.
  
  A related [medium article](https://towardsdatascience.com/assessing-the-impact-of-the-coronavirus-lockdown-on-our-environment-through-data-2905535da51e)
   that I wrote which gave me the idea for creating this.
   
 [[code]](https://github.com/mayukh18/covidexplore) [`Python`, `Flask`, `Plotly`, `Javascript`, `HTML`, `CSS`] 

### DeepGazePointer
*— Gaze prediction with Deep Learning*

Created a system to estimate a person’s point of gaze on a computer screen by using machine learning and
 traditional image processing techniques in real-time from a captured live feed. This
 POC influenced one half of my gaze-estimation based content recommender that I developed
 at Samsung. The training mechanism of the gaze estimator was completely influenced by this
 project.
 
 [[code]](https://github.com/mayukh18/deepgazepointer) [`Python`, `OpenCV`, `Keras`, `PIL`] 

