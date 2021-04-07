1. Assume that you want to balance a (real) ball on a (real) saddle

-Why is this hard?

Well, because I'm not clown...?

-Can you exploit this effect also for optimization algorithm

Modern deep learning use algorithm based on gradient descent to find optimum of function.
Gradient descent find optimum using gradinet, but if target function has ball shape, every points has similar gradient for every direction.
So, if target function's shape looks like a ball, it is hard to optmized.

2. What changes when we perform SGD with momentum? What happens when we use minibatch SGD with momentum

In SGD, momentum has the property of maintaining the direction by fetching the previous value when calculating the gradient of the current point. which means that, if i change the momentum, the power of maintaining the direction also change.

If we use minibatch SGD, we can comput gradient fast using gpu.
