# Project II 2023 Prof. Manevitz  .
Kohonen  (SOM) Algorithm   Try to get both Part A and Part B in by June 20, however the penalties for lateness are as indicated..
## Part A  (Due June 20)  
(-5 points by June 27,  -15 by July 4 additional -10 for each week afterwards).PLEASE SUBMIT ON TIME.
This project requires you to implement the Kohonen (SOM) algorithm.   You should use your own code. You are responsible for experimenting with and finding the appropriate parameters that make it work well.  You may submit with a partner.  You can not share code between groups, but you can discuss the problem freely on the forum or whatsapp group. In your Reports be sure to present h pictures of evolution of the maps, your codes and relevant statistics.

 1. Implement the Kohonen algorithm and use it to fit a line of neurons
to a square.  (That is, the data set is {(x,y) |  0 <= x <= 1, 0<=y<=1} for  which the distribution is uniform while the Kohonen level is linearly ordered.) Do this when you use only a few neurons (20) , when
you use many (200)? 

What happens as the number of iterations of algorithm increases?

Do the same with at least two non-uniform distributions on the square. For example, when the likelihood of picking a point in the data set is proportional to the size of x, but uniform to the size of y.)

You should report with snapshots of the space as the Kohonen map evolves as the number of iterations grows..

2. Now do the same experiments as above for fitting a circle of neurons on a "donut" shape i.e. {<x.y> | 4<= x^2 +y^2 <= 16}.  The circle of neurons has 300 neurons.
Be sure to report on the results of your different attempts. .(Give snapshots as the map evolves over iterations.)

## Part  B  
#### (Due June 30 ,  -10 if done by July 7, -20 if done by July 14 (last submission time;.)  You may find it helpful to look over the diagrams in the chapter at 
Now reproduce the experiment on the "monkey hand" as described in class.  For this part you can use your own code or the Kohonen algorithm in a package (like the SOM package in Matlab).   Be sure to state what code you are using 
In more detail:  
https://www.ks.uiuc.edu/Services/Class/PHYS498TBP/spring2002/neuro_7.pdf


1. Given a diagram  like the following; where the data is <x,y> is  inside the "hand" which is located as a subset of {<x,y> |  0<= x <= 1,  0<=y <= 1} and the Kohonen space is 400 neurons arranged in a 20 x 20 mesh.   [That means data points are only within the "hand" .].  Show how the mesh is superimposed on the plane that contains the hand and how it changes over iterations.    (You can use any "hand like" figure  with 4 "fingers" you wish,) 

2.   Now "cut off a finger" (i.e. data points come only from the "hand with 3 fingers" and then continuing from the stopping point in the previous section. Show over snapshots how the mesh is rearranged.

IN your Reports be sure to present both pictures of evolution of the maps, 
Your codes, and appropriate statistics.

