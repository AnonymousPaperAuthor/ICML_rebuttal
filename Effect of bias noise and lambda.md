## Effect of bias variance $\sigma^2_b$

![](/images/effect_of_bias_variance.png)

The generalization performance (accuracy) is not significantly affected by the bias variance. Moreover, the larger bias variance degrades the generalization performance in CIFAR10.

## Effect of the ridge parameter $\lambda$
![](/images/effect_of_lambda.png)

The generalization performance (MSE) for different choices of $\lambda$ (each row). 
As shown above, the larger ridge parameter $\lambda$ makes the sparser NNGP kernels perform even better than the non-sparse counterpart.
This observation is pronounced and consistent. 
