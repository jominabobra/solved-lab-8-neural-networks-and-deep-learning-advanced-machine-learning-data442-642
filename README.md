Download Link: https://assignmentchef.com/product/solved-lab-8-neural-networks-and-deep-learning-advanced-machine-learning-data442-642
<br>
<strong>Exercise 1</strong>

Consider a two-dimensional class problem that involves two classes <em>ω</em><sub>1</sub>(+1) and <em>ω</em><sub>2</sub>(−1). Each one of them is modeled by a mixture of equiprobable Gaussian distributions. Specifically, the means of the Gaussians associated with <em>ω</em><sub>1 </sub>are [−5<em>,</em>5]<sup>&gt; </sup>and [5<em>,</em>−5]<sup>&gt;</sup>, while the means of the Gaussians associated with <em>ω</em><sub>2 </sub>are [−5<em>,</em>−5]<sup>&gt;</sup><em>,</em>[0<em>,</em>0]<sup>&gt;</sup>, and [−5<em>,</em>−5]<sup>&gt;</sup>. The covariances of all Gaussians are <em>σ</em><sup>2</sup><strong>I</strong>, where <em>σ</em><sup>2 </sup>= 1.

<ul>

 <li>Generate and plot a data set <em>X</em><sub>1 </sub>(training set) containing 100 points from <em>ω</em><sub>1 </sub>(50 points from each associated Guassian) and 150 points from <em>ω</em><sub>2 </sub>(again 50 points from each associated Gaussian). In the same way, generate an additional set <em>X</em><sub>2 </sub>(test set).</li>

 <li>Based on the training set <em>X</em><sub>1</sub>, train a train a two-layer neural network with two nodes in the hidden layer, each one having the rectified linear activation function or ReLU and a single output node with linear activation function using the standard backpropagation algorithm for 6000 iterations and step size equal to 0.01. Compute the training and test errors, based on <em>X</em><sub>1 </sub>and <em>X</em><sub>2 </sub> Also, plot the test points as well as the decision lines formed by the network.</li>

 <li>Repeat step (b) for step size equal to 0.0001 and comment on the results.</li>

 <li>Repeat step (b) for step size equal to 0.0001 and <em>k </em>= 1<em>,</em>4<em>,</em>20<em>,</em>50 hidden layer nodes and comment on the results.</li>

</ul>