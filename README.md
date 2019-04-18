# GradientDescentVariants
Visualizing the convergence of all three variants of gradient descent.

## Batch Gradient Descent
Computes the gradient of the cost function w.r.t parameters for the entire dataset. We update the parameters only once per epoch.

<img src="https://github.com/utkarshchawla/GradientDescentVariants/blob/master/resources/bgd.gif?raw=true">

## Stochastic Gradient Descent
Stochastic gradient descent (SGD) in contrast performs a parameter update for each training example. SGD performs frequent updates with a high variance that cause the objective function to fluctuate heavily.

<img src="https://github.com/utkarshchawla/GradientDescentVariants/blob/master/resources/sgd.gif?raw=true">

## Mini Batch Gradient Descent
Mini-batch gradient descent finally takes the best of both worlds and performs an update for every mini-batch of "bs" training examples.

<img src="https://github.com/utkarshchawla/GradientDescentVariants/blob/master/resources/mbgd.gif?raw=true">
