### Ensemble Learning
#### Boosting
- Learn over a subset of data -> rule
  - uniformly randomly pick data
  - apply a learner
  - hardest examples (more weights on ones got wrong)
- Combine
  - mean / bagging -> weighted mean
- Error
  - Number of mismatch, Pr_D[h(x)!=c(x)]
  - "Weak Learner": Does better than chance always. Pr_D[.] <= 1/2 - ε

#### Summary
- Ensembles are good.
- Bagging is good.
- Combines simple -> complex.
- Boosting is **really** good. => agnostic.
- Weak leaners.
- Error. D.
