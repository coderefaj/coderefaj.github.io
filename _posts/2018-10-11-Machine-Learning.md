# Machine Learning 

Machine learning is about making computers modify or adapt their actions (whether these actions are making predictions, or controlling a robot) so that these actions get more accurate, where accuracy is measured by how well the chosen actions reflect the correct ones.

Machine learning is making computers to learn by past data ( results ) and to predict the new input . In otherwords machine learning is the process of teaching the machine by itself without being explicitly programmed . 

### Types : 

<b> Supervised learning : </b>
	<h5>
	In Supervised Learning , we are able to oversee both the input data and the output data . With these , algorithm trains the model . This is also called learning from exemplars.

Supervised is been Classified into 
1. Classification :
	<p> 
		In classification, the goal is to predict a class label, which is a choice from a predefined list of possibilities. Classification is sometimes separated into binary classification, which is the special case of distinguishing between exactly two classes, and multiclass classification, which is classification between more than two classes. You can think of
		binary classification as trying to answer a yes/no question. Classifying emails as either spam or not spam is an example of a binary classification problem. In this binary classification task, the yes/no question being asked would be “Is this email spam?”

	The iris example, on the other hand, is an example of a multiclass classification problem. Another example is predicting what language a website is in from the text on the website. The classes here would be a pre-defined list of possible languages.
	</p>

	Handwriting Digit Recognition , Character Recognition , Classify between cats and dogs , Image Classification , Diagnostics , Identity Fraud Detection , Email Spam filtering are some of classification projects . 

	We will soon cover all of these . 

#### Classification Algorithms : 
		1. Logistic Regression ( Don't Confuse with regression )
		2. Naive Bayes 
		3. Stochastic Gradient Descent 
		4. K-Nearest Neighbour
		5. Decision Tree 
		6. Random Forest 
		7. Support Vector Machine (Mostly Preferred.)[Both classification and regression]

2. Regression : 

	<p>
	Regression is to predict a continuous number, or a floating-point number in programming terms (or real number in mathematical terms). Predicting a person’s annual income from their education, their age, and where they live is an
	example of a regression task. When predicting income, the predicted value is an amount, and can be any number in a given range. Another example of a regression task is predicting the yield of a corn farm given attributes such as previous yields,weather, and number of employees working on the farm. The yield again can be an arbitrary number. 
	</p>

	Market Forecasting , Price Prediction , Population Growth Prediction are some of applications for regression model .

	1. Linear Regression 
	2. Lasso Regression 
	3. Support Vector Machines 
	4. Multivariate Regression Algorithm
	5. Multiple Regression Algorithm 


<b> Unsupervised learning :</b> 

<p>
In Unsupervised Learning , the input data are not been labelled , which means they donot have any expected output for each input . Rather the the algorithms are left to themselves to discover interesting structures in the data .Correct responses are not provided, but instead the algorithm tries to identify similarities between the inputs so that inputs  that have something in common are categorised together. The statistical approach to unsupervised learning is known as density estimation.</p>


Unsupervised learning is been split into 
<br>
1.  Clustering .
		<p> Clustering , means identifying the identical features from the given data and grouping together . 
		Therby forming many groups and labelling it . 

	<center>
	!["classification"]( /images/ml/classification_example.jpeg "Classification Image Sample" =50x50)</center>
	<br>
	In the above image, the image to the left is raw data where the classification isn’t done, the image in the right is clustered(the data is classified based on its features). When an input is given which is to be predicted then it checks in the cluster it belongs based on it’s features, and the prediction is made.

	Various Clustering Algorithms 
			1. K means Clustering 
			2. One Hierarchial Clustering 
			3. Agglomerative Hierarchial Cluatering 
</p>

<b>Reinforcement learning :</b>

<p>
This is somewhere between supervised and unsupervised learning. The algorithm gets told when the answer is wrong, but does not get told how to correct it. It has to explore and try out different possibilities until it works out how to get the answer right. Reinforcement learning is sometime called learning with a critic
because of this monitor that scores the answer, but does not suggest improvement .

Reinforcement Learning is a type of Machine Learning, and thereby also a branch of Artificial Intelligence. It allows machines and software agents to automatically determine the ideal behaviour within a specific context, in order to maximize its performance. Simple reward feedback is required for the agent to learn its behaviour; this is known as the reinforcement signal.
</p>

For Reference : [Reinforment Learning ](https://towardsdatascience.com/introduction-to-various-reinforcement-learning-algorithms-i-q-learning-sarsa-dqn-ddpg-72a5e0cb6287)

</h5>


