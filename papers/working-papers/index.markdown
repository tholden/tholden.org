---
author: Tom
comments: false
date: 2014-10-07 15:08:31+00:00
layout: page
link: http://www.tholden.org/papers/working-papers/
slug: working-papers
title: Working Papers
wordpress_id: 114
---

### Occasionally binding constraints





#### New approach



**Title: Existence and uniqueness of solutions to dynamic models with occasionally binding constraints.**
**Abstract: **We present the first necessary and sufficient conditions for there to be a unique perfect-foresight solution to an otherwise linear dynamic model with occasionally binding constraints, given a fixed terminal condition. We derive further results on the existence of a solution in the presence of such terminal conditions. These results give determinacy conditions for models with occasionally binding constraints, much as Blanchard and Kahn (1980) did for linear models. In an application, we show that widely used New Keynesian models with endogenous states possess multiple perfect foresight equilibrium paths when there is a zero lower bound on nominal interest rates, even when agents believe that the central bank will eventually attain its long-run, positive inflation target. This illustrates that a credible long-run inflation target does not render the Taylor principle sufficient for determinacy in the presence of the zero lower bound. However, we show that price level targeting does restore determinacy providing agents believe that inflation will eventually be positive.

**[View](https://github.com/tholden/dynareOBC/blob/master/TheoryPaper.pdf) [Download](https://github.com/tholden/dynareOBC/raw/master/TheoryPaper.pdf)**

**Title: Computation of solutions to dynamic models with occasionally binding constraints.**
**Abstract: **We construct the first algorithm for the perfect foresight solution of otherwise linear models with occasionally binding constraints, with fixed terminal conditions, that is guaranteed to return a solution in finite time, if one exists. We also provide a proof of the inescapability of the “curse of dimensionality” for this problem when nothing is known a priori about the model. We go on to extend our algorithm to deal with stochastic simulation, other non-linearities, and future uncertainty. We show that the resulting algorithm produces fast and accurate simulations of a range of models with occasionally binding constraints.

**[View](https://github.com/tholden/dynareOBC/blob/master/ComputationalPaper.pdf) [Download](https://github.com/tholden/dynareOBC/raw/master/ComputationalPaper.pdf)**

**Title: Tractable estimation and smoothing of highly non-linear dynamic state-space models.**
**Abstract: **We present an algorithm for tractably estimating non-linear dynamic models, such as DSGE models with occasionally binding constraints. The algorithm presents an extended skew-t, augmented-state, version of the Cubature Kalman Filter of Arasaratnam and Haykin (2009) with dynamic state space reduction, to give adequate speed, and to ensure that it can handle the large state spaces generated, for example, by pruned perturbation solutions to medium-scale DSGE models. We further extend the base algorithm to allow for alternative cubature procedures to improve the tracking of non-linearities. We illustrate that the method can solve some of the identification problems that plague linearized DSGE models. We go on to extend the algorithm to produce smoothed estimates of states, and we use this to assess which shocks caused the great recession in the model of Christiano, Motto, and Rostagno (2014).

**[View](https://github.com/tholden/dynareOBC/blob/master/EstimationPaper.pdf) [Download](https://github.com/tholden/dynareOBC/raw/master/EstimationPaper.pdf)**



#### Old approach



**Title: Efficient simulation of DSGE models with inequality constraints** (joint with Michael Paetz)

[_NEP-DGE blog featured paper, August 2012_](https://nepdge.wordpress.com/2012/08/26/efficient-simulation-of-dsge-models-with-inequality-constraints/)

**Abstract: **This paper presents a fast, simple and intuitive algorithm for simulation of linear dynamic stochastic general equilibrium models with inequality constraints. The algorithm handles both the computation of impulse responses, and stochastic simulation, and can deal with arbitrarily many bounded variables. Furthermore, the algorithm is able to capture the precautionary motive associated with the risk of hitting such a bound. To illustrate the usefulness and efficiency of this algorithm we provide a variety of applications including to models incorporating a zero lower bound (ZLB) on nominal interest rates. Our procedure is much faster than comparable methods and can readily handle large models. We therefore expect this algorithm to be useful in a wide variety of applications.

**[View](https://docs.google.com/a/tholden.org/viewer?a=v&pid=sites&srcid=dGhvbGRlbi5vcmd8cm9vdHxneDpmM2EwNGMwZTIyNmE3NjM) [Download](https://sites.google.com/a/tholden.org/root/files/zlb.pdf?attredirects=0)**



* * *





### Medium-frequency cycles





#### Work in progress on a new draft



**Title: Medium frequency cycles in a stationary world.**

**Abstract:** Existing models of endogenous growth generate implausibly large trend breaks in output when augmented with standard business cycle shocks. This paper presents a model without this deficiency, yet still capable of generating large medium-frequency fluctuations around the trend. Ensuring the robustness of the trend requires that we eliminate the strong scale effects and knife edge assumptions that plague most growth models. In our model, medium-frequency fluctuations arise from changes in the proportion of industries producing patent protected products. However, variations in the number of firms within each industry ensure that process improvement incentives remain roughly constant. An estimated version of the model matches well the observed pattern of medium frequency cycles.

**[Download](http://www.tholden.org/wp-content/uploads/2014/10/mfc4tmp.pdf)**



#### Older versions



**Title: Reconciling near trend-stationary growth with medium-frequency cycles.**

_[NEP-DGE blog featured paper, December 2010](https://nepdge.wordpress.com/2010/12/25/products-patents-and-productivity-persistence-a-dsge-model-of-endogenous-growth/), under the title “Products, patents and productivity persistence”_

**Abstract:** Existing models of dynamic endogenous growth generate implausibly large trend breaks in output when augmented with standard business cycle shocks. This paper presents a model without this deficiency, yet still capable of generating large medium-frequency fluctuations around the trend. Ensuring the robustness of the trend requires that we eliminate the scale effects and knife edge assumptions that plague most growth models. In our model, medium-frequency fluctuations arise from changes in the proportion of industries producing patent protected products. However, variations in the number of firms within each industry ensure that process improvement incentives remain roughly constant.

**[View](https://docs.google.com/viewer?a=v&pid=sites&srcid=dGhvbGRlbi5vcmd8cm9vdHxneDo1OWM5YmE3OTU5ZWNkOTA3) [Download](https://sites.google.com/a/tholden.org/root/files/mfc%20aer%201.pdf?attredirects=0)**

**Title: Data consistent modelling of medium-frequency cycles and their origins.**

**Abstract:** This paper presents four stylized facts on medium-frequency cycles, then builds and estimates a model capable of replicating both these facts and standard business-cycle ones. We show that GDP returns to trend at long lags, that aggregate mark-ups always lead output, and are only counter-cyclical at low frequencies, and that medium-frequency cycles are larger in countries with longer patent protection. Since traditional dynamic endogenous growth models generate large trend-breaks following business-cycle shocks, our model is based on that of Holden (2013a). After estimation, a financial-type shock to the stock of ideas emerges as the key driver of the medium-frequency cycle.

**[View](https://docs.google.com/viewer?a=v&pid=sites&srcid=dGhvbGRlbi5vcmd8cm9vdHxneDozOGVkNmQxZWU3NjA0NDRk) [Download](https://sites.google.com/a/tholden.org/root/files/mfc%20aer%202.pdf?attredirects=0)**

**Title: Online appendices to “Reconciling near trend-stationary growth with medium-frequency cycles” and “Data consistent modelling of medium-frequency cycles and their origins”.**

**Abstract:** This paper presents the online appendices to Holden (2013a) and Holden (2013b). We discuss the derivation of the first order and free-entry conditions, the steady state level of relative productivity of non-protected industries, and the nature of the inventor-firm bargaining procedure. We go on to present the full equations of both models considered, details of the data used for estimation, and the results of this estimation procedure.

**[View](https://docs.google.com/viewer?a=v&pid=sites&srcid=dGhvbGRlbi5vcmd8cm9vdHxneDo1OTlkMDI3MWNkYzQ3YjQ5) [Download](https://sites.google.com/a/tholden.org/root/files/mfc%20aer%203.pdf?attredirects=0)**



* * *





### Learning



**Title: [Learning from learners](http://www.tholden.org/wp-content/uploads/2014/10/learning-from-learners-release.pdf)**

**Abstract:** Traditional macroeconomic learning algorithms are misspecified when all agents are learning simultaneously. In this paper, we produce a number of learning algorithms that do not share this failing, and show that this enables them to learn almost any solution, for any parameters, implying learning cannot be used for equilibrium selection. As a by-product, we are able to show that when all agents are learning by traditional methods, all deep structural parameters of standard new-Keynesian models are identified, overturning a key result of Cochrane (2009; 2011). This holds irrespective of whether the central bank is following the Taylor principle, irrespective of whether the implied path is or is not explosive, and irrespective of whether agents’ beliefs converge. If shocks are observed then this result is trivial, so following Cochrane (2009) our analysis is carried out in the more plausible case in which agents do not observe shocks.

**[Download](http://www.tholden.org/wp-content/uploads/2014/10/learning-from-learners-release.pdf)**



* * *



**For other papers, please see [my RePEc profile](http://ideas.repec.org/f/pho254.html) or [my Google Scholar profile](http://scholar.google.com/citations?hl=en&user=vvM76xcAAAAJ).**
