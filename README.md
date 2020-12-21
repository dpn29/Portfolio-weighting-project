# Portfolio-weighting-project

Please read the pdf file for the project description.

Based on a discussion I had about the topic after completing the project, the following points seem important to mention:

* Possibly most of the alpha comes from being long-momentum. Implementing on Quantopian on otherwise computing exposure factors would be interesting. It could also be interesting to just equally-weight the 10 highest-momentum stocks and see if optimal portfolio weighting outperforms that in terms of Sharpe ratio.
* Related to the above point, the strategy did suffer a larger drawdown than the index during March 2020. If 2001 was in the sample, the performance difference would likely be smaller.
* The mean vector and covariance matrix were estimated by the historical (previous trading year) average. This is an intuitive, but not necessarily justified estimator; it would be interesting to see how the results change if we use shrinkage or Marchenko-Pastur denoising.
