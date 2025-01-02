# Explainable-and-Reliable-Prediction

A user of a machine-learning system has to be able to decide whether to trust any individual
prediction provided by the system. To make this possible, the system has to provide an
explanation and a reliability information for the prediction. The explanation will contribute
to a user’s trust in a cognitive sense while the reliability information to a user’s trust in a
statistical sense. For example, if the reliability information is a precise confidence level in
the prediction, the user can accept/reject the prediction on an acceptable significance level
ε, thus, guaranteeing that the overall prediction error of the machine-learning system is
bounded by ε.

At present, machine learning systems achieve explainable and reliable prediction using two
separate sub-systems: one for reliable prediction and second for explanation. The goal of
this Master-project proposal is to propose an algorithm capable of learning predictors that
provide simultaneously explanation and reliability information for each individual case. The
key idea is to combine explanation-based predictors (e.g. lazy trees) with reliable predictors
(e.g. conformal predictors). Possible combinations have to be applicable for single-output
and multi-output classification and regression.
