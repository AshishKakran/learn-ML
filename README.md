# learn-ML
Introduction to Machine learning (based on [CS229](https://cs229.stanford.edu/) from stanford university)<br>

<ul>
	<li> <a href="https://cs229.stanford.edu/"> Course website </a> </li>
<li><a href="https://www.youtube.com/playlist?list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU"> Video lectures </a> </li>
<li><a href="https://see.stanford.edu/Course/CS229"> vintage version of cs229 </a>  </li>
</ul>

## Supervised learning
<table>
<tr>
<th> Concept </th>
<th> lecture </th>
<th> applications</th>
<th> extras </th>
</tr>
<tr>
	
<td> 
	<p> Linear models 
<ul>
	<li> <a href="ordinary_linear_reg_grad_descent.ipynb"> linear regression (gradient descent) </a> </li>
	<li>  <a href="ord_linear_reg_stochastic_GD.ipynb"> linear regression (stochastic GD) </a> </li>
	<li> <a href="Polynomial_regression.ipynb"> Polynomial regression </a> </li>
	<li> <a href="newton_raphson_log_reg.ipynb"> Logistic regression </a> </li>
	<li> <a href="multiclass_classification_softmax.ipynb"> Softmax regression(multiclass) </a> </li>
	<li> <a href="plot_poisson_regression_non_normal_loss.ipynb"> Poisson regression </a> </li>
	<li> <a href="plot_tweedie_regression_insurance_claims.ipynb"> GLM </a>	</li>
    </ul></p>
</td>
<td>
<ul>
<li> <a href="https://www.youtube.com/watch?v=4b4MUYve_U8&list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU&index=2"> ML problem setup </a> </li>
<li> <a href="https://www.youtube.com/watch?v=4b4MUYve_U8&list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU&index=2"> LR and GD </a> </li>
<li> <a href="https://www.youtube.com/watch?v=het9HFqo1TQ&list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU&index=3"> Weighted & Logistic regression </a> </li>
<li> <a href="https://www.youtube.com/watch?v=iZTeva0WSTQ&list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU&index=4"> GLMs & cross-entroy min </a> </li>

</ul>
 </td>
<td> <ul>
	<li> <a href="pred_diabetes_progress.ipynb"> Predicting diabetes progression</a> </li>
	</ul>
</td>
<td>
<ul>
<li> <a href="https://towardsdatascience.com/assumptions-of-linear-regression-fdb71ebeaa8b"> assumptions of LR </a> </li>
<li> <a href="https://dl.acm.org/doi/10.1162/neco.1996.8.7.1341"> No free lunch </a> </li> 
<li> <a href="https://static.googleusercontent.com/media/research.google.com/fr//pubs/archive/35179.pdf"> data effects </a> </li>
<li> <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3164764"> case study: GLM </a> </li>
 </ul>
 </td>
</tr>
<tr> 
<td>	<ul>
<li> <a href="Naive_bayes.ipynb"> Naive Bayes </a> </li>
</ul>
</td>
<td>
<ul>
<li> <a href="https://www.youtube.com/watch?v=nt63k3bfXS0&list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU&index=5"> GDA and Naive Bayes </a> </li>
</ul>
</td>
<td>
<ul> <li> <a href="spam_classification.ipynb"> Spam classification using NB </a></li> </ul>
</td>
<td>
<ul> <li> <a href="https://mathformachines.com/posts/discriminant-analysis/"> discriminant analysis </a> </li> </ul>
</td>
</tr>
<tr> 
 <td>
   <ul>
 <li> <a href="SVM_classifiers.ipynb">Support Vector Machines </a></li>
   </ul>
 </td>
 <td>
  <ul>
   <li> <a href="https://www.youtube.com/watch?v=lDwow4aOrtg&list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU&index=6"> Support Vector Machines </a> </li>
   <li> <a href="https://www.youtube.com/watch?v=8NYoQiRANpg&list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU&index=7"> Kernels </a> </li>
</ul>
</td>
<td> <ul> <li> <a href="MNIST_svm.ipynb"> Digit recognition (clf) </a> </li>
<li> <a href="Predicting_house_prices.ipynb"> Housing price prediction (reg) </a> </li> </ul>
</td>
<td> <ul> <li> <a href="https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/tr-98-14.pdf"> SMO algorithm </a> </li>
<li> <a href="https://dl.acm.org/doi/10.1145/1390156.1390208"> Dual coordinate descent </a></li>
<li> <a href="https://proceedings.neurips.cc/paper/2000/file/155fa09596c7e18e50b58eb7e0c6ccb4-Paper.pdf"> Online learning </a> </li>
<li> <a href="https://jmlr.org/papers/volume6/bordes05a/bordes05a.pdf"> Fast Kernels </a> </li>
</ul>
</td>
</tr>
<tr>
<td>  <p> Nonparametric methods
<ul> <li> <a href="decision_trees.ipynb"> Decision Trees </a> </li>
<li> <a href="ensemble.ipynb"> Ensemble learning </a> </li>
 </ul>
 </p></td>
<td> <ul> <li> <a href="https://youtu.be/wr9gUr-eWdA"> DT & Ensemble methods </a> </li> </ul></td>
<td> <ul> <li>  <a href="MNIST_ensemble.ipynb"> MNIST ensemble </a> </li> </ul> </td>
<td> <ul>
<li> <a href="https://www.stat.berkeley.edu/~breiman/bagging.pdf"> Bagging predictors </a> </li>

<li> <a href="https://en.wikipedia.org/wiki/Bootstrap_aggregating"> Bootstrapping </a> </li>
<li> <a href="https://dl.acm.org/doi/10.1023/A:1007563306331"> pasting </a> </li>
<li> <a href="https://link.springer.com/chapter/10.1007/978-3-642-33460-3_28"> random patches </a> </li>
<li> <a href="https://dl.acm.org/doi/10.1109/34.709601"> random subspaces </a> </li>
<li> <a href="https://dl.acm.org/doi/10.5555/844379.844681"> random decision forests </a> </li>
<li> <a href="https://link.springer.com/article/10.1007/s10994-006-6226-1"> extremely randomized trees </a> </li>
<li> <a href="https://www.sciencedirect.com/science/article/pii/S002200009791504X"> boosting </a> </li>
<li> <a href="https://hastie.su.domains/Papers/SII-2-3-A8-Zhu.pdf"> multiclass adaboost </a> </li>
<li> <a href="https://www.jstor.org/stable/2699986"> Gradient boost </a> </li>
<li> <a href="http://www.machine-learning.martinsewell.com/ensembles/stacking/Wolpert1992.pdf"> stacking </a> </li>
 </ul> </td>
 </tr>
<tr>
<td> <p> Learning theory
<ul> <li> <a href="https://cs229.stanford.edu/notes2022fall/bias-variance.pdf"> Bias, variance and ERM </a></li>
 </ul> </p> </td>
<td> <ul> <li> <a href="https://www.youtube.com/watch?v=rjbkWSTjHzM&list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU&index=8"> Data Split, Models & CV </a> </li>
<li> <a href="https://www.youtube.com/watch?v=iVOxMcumR4A&list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU&index=9"> Estimation Error and ERM </a> </li>
</ul>  </td>
<td> </td>
<td> <ul> <li> <a href="https://epubs.siam.org/doi/10.1137/20M1336072"> Double Descent phenomenon </a> </li> </ul> </td>
 </tr>
<tr>
<td> Neural Networks
 <ul> <li> <a href="neural_networks.ipynb"> Introduction to NN </a> </li>
<li> <a href="notes_chapter_Neural_Networks.pdf"> Optimizing NNs </a> <li>
</ul>
</td>
<td> <ul> <li> <a href="https://youtu.be/MfIjxPh6Pys"> Introduction </a> </li>
<li> <a href="https://youtu.be/zUazLXZZA2U"> Improving NNs </a> </li>
 </ul> </td>
<td> <ul> <li> <a href="fashion_MNIST.ipynb"> MNIST fashion clf </a> </li>
<li> <a href="MNIST_MLP.ipynb"> MNIST digit MLP clf </a> </li>
</td>
<td> </td>
</tr>
</table>


## Unsupervised learning

<table>
<tr>
<th> Concept </th>
<th> lecture </th>
<th> applications</th>
<th> extras </th>
</tr>

<tr> <td> Dimensionality Reduction 
 <ul> <li> <a href="dimensionality_red.ipynb"> SVD & PCA </a>  </li> </ul>
</td>
 <td> </td>
 <td> <ul> <li> <a href="compressing_MNIST.ipynb"> Visualising MNIST </a> </li> </ul> </td> 
<td> <ul> <li> <a href="https://www.tandfonline.com/doi/abs/10.1080/14786440109462720"> PCA </a> </li> 
<li> <a href="https://link.springer.com/chapter/10.1007/BFb0020217"> Kernel PCA </a> </li> 
<li> <a href="https://www.science.org/doi/10.1126/science.290.5500.2323"> LLE </a> </li> </ul> </td> </tr>

<tr>
<td> <ul>
 <li> <a href="clustering.ipynb"> K-means </a> </li> 
 <li> <a href="dbscan.ipynb"> DBSCAN </a> </li>
 <li> <a href="gaussian_mixture.ipynb"> Gaussian Mixtures </a> </li>
</ul> </td>
<td> </td>
<td> <ul> <li> <a href="clustering_applications.ipynb"> Image segmentation </a> </li>
<li> <a href="face_similiarity.ipynb"> Clustering faces in Olivetti dataset </a> </li>
 </ul> </td>
<td> <ul> 
<li> <a href="https://ieeexplore.ieee.org/document/1056489"> KMeans </a> </li>
<li> <a href="https://dl.acm.org/doi/10.5555/3041838.3041857"> Elkan's algorithm </a> </li>
<li> <a href="https://dl.acm.org/doi/10.1145/3132847.3133091"> Fast Kmeans </a> </li>
<li> <a href="https://theory.stanford.edu/~sergei/papers/kMeansPP-soda.pdf"> Kmeans++ </a> </li>

</ul>
 </td>
</tr>
</table>



