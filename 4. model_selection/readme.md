You could get overwhelmed by the choice of algorithms available for classification. To summarise—

Start with logistic regression. Using a logistic regression model serves two purposes: 1) It acts as a baseline (benchmark) model. 2) It gives you an idea about the important variables.

Then, go for decision trees and compare their performance with the logistic regression model. If there is no significant improvement in their performance, then just use the important variables drawn from the logistic regression model.

Finally, if you still do not meet the performance requirements, use support vector machines. But, keep in mind the time and resource constraints, because it takes time to find an appropriate kernel for SVM. Also, they are computationally expensive.