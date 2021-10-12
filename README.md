# Predicting viability of Clinical Targets 
**Authors:** Gopalika Sharma  

#### Summary:

##### Problem Statement:
Develop an algorithm to predict a Target and/or Mechanism of Action that has a high probability of garnering significant scientific/financial investment and is therefore, or has the potential to be, undervalued.
<br />
##### Workflow:
1.Fit and ran a Random Forest Model. It was pickled and saved to be integrated into the application as model.pkl

2.Flask was used to write the code for prediction while integrating the pickled machine learning model into it as app.py, it is hosted on localhost because it is a developer link and to host it we need a hosting application like Heroku or as a streamlit app which is in progress.

3.Templated were designed with HTML and CSS to get the preliminary look of the app which were index.html and result.html

4.They were all combined and was executed using the command prompt window for it to run, using the function python app.py 

<br />

<br />
https://user-images.githubusercontent.com/54693803/137012081-c1b3dbc9-e582-4644-bf52-38b59a2c54e2.mov
<br />


#### References:
1.How to create an interactive Machine Learning Web Application using Flask and Heroku; https://medium.com/swlh/how-to-create-an-interactive-machine-learning-web-application-using-flask-and-heroku-5ae76a45bfc5
 
2.How to deploy your ML model in Jupyter Notebook to your Flask App; https://medium.com/techcrush/how-to-deploy-your-ml-model-in-jupyter-notebook-to-your-flask-app-d1c4933b29b5

3.Building Flask and Plotly dashboard; https://blog.heptanalytics.com/flask-plotly-dashboard/
