# Common interview questions asked in Machine Learning interviews:
A repository to prepare machine learning interview, involving most of the questions asked.
## Difference between Supervised and Unsupervised Learning?
Supervised learning is when you know the outcome and you are provided with the fully labeled outcome data while in unsupervised you are not 
provided with labeled outcome data. Fully labeled means that each example in the training dataset is tagged with the answer the algorithm should 
come up with on its own. So, a labeled dataset of flower images would tell the model which photos were of roses, daisies and daffodils. When shown a new image, the model compares it to the training examples to predict the correct label.
## What is Reinforcment Learning and how would you define it?
A learning differs from supervised learning in not needing labelled input/output pairs be presented, and in not needing sub-optimal actions to be 
explicitly corrected. Instead the focus is on finding a balance between exploration (of uncharted territory) and exploitation (of current 
knowledge) .Semisupervised learning is also known as Reinforcment learning, in reinforcment learning each learning steps involved a penalty 
criteria whether to give model positive points or negative points and based on that penalizing the model.
## What is Deep Learning?
Deep learning is defined as algorithms inspired by the structure and function of the brain called artificial neural networks(ANN).Deep learning 
most probably focuses on Non Linear Analysis and is recommend for Non Linear problems regarding Artificial Intelligence.
## Difference between Machine Learning and Deep Learning?
Since DL is a subset of ML and both being subset of AI.While basic machine learning models do become progressively better at whatever their 
function is, they still need some guidance. If an AI algorithm returns an inaccurate prediction, then an engineer has to step in and make 
adjustments. With a deep learning model, an algorithm can determine on its own if a prediction is accurate or not through its own neural network.
## Difference between Bias and Variance?
Bias is definned as over simpliciation assumption assumed by the model, Variance is definned as ability of a model to learn from Noise as well, making it highly variant.There is always a tradeoff between these both, hence its recommended to find a balance between these two and always use cross validation to determine the best fit.
## What is Linear Regressions? How does it work?
 Fitting a Line in the respectable dataset when drawn to a plane, in a way that it actually defines the correlation between your dependent
variables and your independent variable. Using a simple Line/Slope Formulae. Famously, representing f(X) = M(x) + b.Where b represents bias
X represent the input variable (independent ones) f(X) represents Y which is dependent(outcome).
The working of linear regression is Given a data set of n statistical units, a linear regression model assumes that the relationship between the 
dependent variable y and the p-vector of regressors x is linear. This relationship is modeled through a disturbance term or error variable ε — an 
unobserved random variable that adds "noise" to the linear relationship between the dependent variable and regressors. Thus the model takes the 
form Y = B0 + B1X1 + B2X2 + ..... + BNXN
This also emplies : Y(i) = X(i) ^ T + B(i)
Where T : denotes Transpose
X(i) : denotes input at the I'th record in form of vector
B(i) : denotes vector B which is bias vector.

## What is Logistic Regression? How does it work?
Logistic regression is a statistical technique used to predict probability of binary response based on one or more independent variables. 
It means that, given a certain factors, logistic regression is used to predict an outcome which has two values such as 0 or 1, pass or fail,
yes or no etcLogistic Regression is used when the dependent variable (target) is categorical.For example,To predict whether an email is spam (1) or (0)Whether the tumor is malignant (1) or not (0)Whether the transaction is fraud or not (1 or 0)The prediction is based on probabilties of specified classes  Works the same way as linear regression but uses logit function to scale down the values between 0 and 1 and get the probabilities.

## What is Logit Function? or Sigmoid function/ where in ML and DL you can use it?
The sigmoid might be useful if you want to transform a real valued variable into something that represents a probability. While the Logit functionis to map probaliticvalues from -Inf to +inf to either real numbers representing True or False towards 1 or 0 (real number). This is commonly used in Classification having base in  Logistic Regression along with Sigmoid based functions in Deep learning used to find a nominal outcome in alayer or output of a layer.

