# toughasnails.github.io
Review Machine Learning basic concepts.

The main focus of machine learning is *making decisions or predictions based on data*.
The conceptual basis of learning from data is the problem of *induction*: Why do we think
that previously seen data will help us predict the future? This is a serious philosophical
problem of long standing. We will operationalize it by making assumptions, such as that
all training data are IID (independent and identically distributed) and that queries will be
drawn from the same distribution as the training data, or that the answer comes from a set
of possible answers known in advance.

In general, we need to solve these two problems:
• **estimation**: When we have data that are noisy reflections of some underlying quan-
tity of interest, we have to aggregate the data and make estimates or predictions
about the quantity. How do we deal with the fact that, for example, the same treat-
ment may end up with different results on different trials? How can we predict how
well an estimate may compare to future results?
• **generalization**: How can we predict results of a situation or experiment that we have
never encountered before in our data set?

We can describe problems and their solutions using six characteristics, three of which
characterize the problem and three of which characterize the solution:
1. **Problem class**: What is the nature of the training data and what kinds of queries will
be made at testing time?
2. **Assumptions**: What do we know about the source of the data or the form of the
solution?
3. **Evaluation criteria**: What is the goal of the prediction or estimation system? How
will the answers to individual queries be evaluated? How will the overall perfor-
mance of the system be measured?
4. **Model type**: Will an intermediate model be made? What aspects of the data will be
modeled? How will the model be used to make predictions?
5. **Model class**: What particular parametric class of models will be used? What criterion
will we use to pick a particular model from the model class?
6. **Algorithm**: What computational process will be used to fit the model to the data
and/or to make predictions?
Without making some assumptions about the nature of the process generating the data, we
cannot perform generalization.

MIT 6.036
