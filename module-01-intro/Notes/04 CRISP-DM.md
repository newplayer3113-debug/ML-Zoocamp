<img width="711" height="672" alt="image" src="https://github.com/user-attachments/assets/436ad7be-f3a6-4f19-a196-f9904df92aaa" />

CRISP-DM consists of Business Understanding, Data Understanding, Data Preparation, Modelling, Evaluation, Deployment

Business Understanding
In this part you ask questions, define your goal
What is your problem? How impactful is it? Is using ML the right way or is there other easier alternatives?
Define your goal, and use measurements 'Reduce spam reports by 50%'

Data Understanding
In this part you analyze the data you got and decide whether or not you need more data
You ask questions like: "Is the data reliable? or did peolpe missclick?"
You identify the data source (You get to know your data) and you may need to change your original goal 

Data Preparation
In this part you need to clean your raw data
Ex. make a pipeline that transforms your raw data into clean usable data
After cleaning you need to order the data into a tabular format which can be used in machine learning

Modelling
In this part this is where we actually train the model
You try many different models and use the best one
Models ex. Logistic regression, decision tree, neural network
Sometimes, we may need to add more features to the model to give it a better picture or you might need to fix some issues so you might go back to the data preparation step

Evaluation
In this part you ask yourself 'Did you reach the goal?' and evaluate how much you succeeded or failed
You will know if the goal you set was achievable or not

Deployment
In this part you deploy it online and live users use it 
In this part you focus on the engineering part of the ML (Monitoring, Maintaining quality and sustainability)

After the Deployment you go back to the Business Understanding again and do the entire thing again after many iterations until you get a satisfiable result
