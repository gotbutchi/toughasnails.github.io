# Linear Classifiers and Generalization

In a classification problem we need to take $R^d$, $d$ is a dimension space, and divide it into some subspace that we call positive, and some subspace that we call negative. The simplest way to do that is by putting a linear separator in there.
The linear classifier has this form: 

$h(x;\theta, \theta_0) = sign(\theta \cdot x + \theta_0)$

Training data can be graphically depicted on a (hyper)plane. Classifiers are mappings that take feature vectors as input and produce labels as output. A common kind of classifier is the linear classifier, which linearly divides space(the (hyper)plane where training data lies) into two. Given a point $x$ in the space, the classifier $h$ outputs $1$ if  if $\theta \cdot x + \theta_0 >0$ or $-1$ otherwise, depending on where the point $x$ exists in among the two linearly divided spaces.

![Linear Classifier](https://github.com/gotbutchi/toughasnails.github.io/blob/gh-pages/Linear%20CLF/images_L1Classifier.jpeg)



Each classifier represents a possible “hypothesis" about the data; thus, the set of possible classifiers can be seen as the space of possible hypothesis.
