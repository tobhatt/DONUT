# DONUT
This is the code for "Deep Orthogonal Networks for Unconfounded Treatments" from "Estimating Average Treatment Effects via Orthogonal Regularization".

The paper can be found here: https://dl.acm.org/doi/10.1145/3459637.3482339

Abstract:

Decision-making often requires accurate estimation of treatment effects from observational data. This is challenging as outcomes of alternative decisions are not observed and have to be estimated. Previous methods estimate outcomes based on unconfoundedness but neglect any constraints that unconfoundedness imposes on the outcomes. In this paper, we propose a novel regularization framework for estimating average treatment effects that exploits unconfoundedness. To this end, we formalize unconfoundedness as an orthogonality constraint, which ensures that the outcomes are orthogonal to the treatment assignment. This orthogonality constraint is then included in the loss function via a regularization. Based on our regularization framework, we develop deep orthogonal networks for unconfounded treatments (DONUT), which learn outcomes that are orthogonal to the treatment assignment. Using a variety of benchmark datasets for estimating average treatment effects, we demonstrate that DONUT outperforms the state-of-the-art substantially.
