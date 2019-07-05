DP + {Fairness, Interpretability}
=====================
This set of notes will be about a bunch of papers that
look at satisfying differential privacy at the same time as
fairness properties, and or interpretability.



### DP + Fairness (Badasaryan & Shmatikov, 2019 and Jagielski et. al. 2019)

<img src="https://raw.githubusercontent.com/adebayoj/papers/master/figures/dp_reading_group_summer_2019/hyperparams_bs_fairness.png" width="700"> 


<img src="https://raw.githubusercontent.com/adebayoj/papers/figures/dp_reading_group_summer_2019/hyperparams_bs_fairness.png" width="700"> 

Saliency methods have emerged as a popular tool to highlight
features in an input deemed relevant for the prediction of a 
learned model. Several saliency methods have been proposed, often 
guided by visual appeal on image data. In this work, we propose 
an actionable methodology to evaluate what kinds of explanations 
a given method can and cannot provide. We find that reliance, 
solely, on visual assessment can be misleading. Through extensive
experiments we show that some existing saliency methods are 
independent both of the model and of the data generating process.
Consequently, methods that fail the proposed tests are 
inadequate for tasks that are sensitive to either data or model,
such as, finding outliers in the data, explaining the 
relationship between inputs and outputs that the model learned,
or debugging the model. We interpret our findings through an 
analogy with edge detection in images, a technique that requires 
neither training data nor model. Theory in the case of a 
linear model and a single-layer convolutional neural network
supports our experimental findings.
 

### Saliency Map Examples for CNNS.
<img src="https://raw.githubusercontent.com/adebayoj/sanity_checks_saliency/master/doc/figures/saliency_methods_and_edge_detector.png" width="700">