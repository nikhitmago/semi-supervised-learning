# Semi Supervised Learning using Active learning, Passive Learning and Monte Carlo Simulations

The data set can be found [here](https://archive.ics.uci.edu/ml/datasets/banknote+authentication)

- Objective is to implement Active Learning and Passive Learning using L1 penalized SVMs (LinearSVC)
- Active Learning implemented by finding a sample of 10 data points closest to the margin of the SVM (As these have the most contradction)
- Passive Learning implemented by finding the sample randomly
- The Monte Carlo Simulation shows how the error descends quickly for active learners as compared to passive learners
