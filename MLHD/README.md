# Data-Science/MLHD
Here I am going to practice some concept of Machine Learning specially Regression techniques.

<h3>Steps to build this project</h3>
<ul>
	<li>Data acquisition</li>
	<li>EDA</li>
	<li>Regression model building</li>
	<li>Model Testing</li>
	<li>Deployment</li>
</ul>

<h3>Data Acquisition</h3>
I am only practicing Machine learning algorithms. So, I have generated the whole data using Python. I have used Random functions to generate the whole data.
The directory <a href="https://github.com/pythonpioneer/Data-Science/tree/master/MLHD/Horse%20Data">Horse data</a> contain all the information about data generation and you can find the dataset <a href="https://www.kaggle.com/datasets/hritikkumarsinha/horse-dataset">here</a>.

<h3>Exploratory Data Analysis</h3>
The dataset conataining some columns like serial number, horse id, horse height, horse weight, horse gender and the horse is a racer horse or not. From here, we can simply see that the data doesn't containing any different or new information. So, we can simply drop null values from the dataset. Or, we can also fill it with some other information like mean, median and mode. And the data show that the height and weight relation is based on their breed but the breed column is not here. This is our task is to predict the weight of horses based on their height.<br>
We can also drop some columns like horse id, racer horse and serial number because these columns doesn't effect the model. We can also drop horse gender because we know that gender doesn't effect the height and weight of horses. So, here we are left with only horse height and horse weight.

<h3>Regression model building</h3>





