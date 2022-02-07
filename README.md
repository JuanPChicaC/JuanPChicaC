
<div>
  <h2 align = "center" id = "heading" font-weight =  bold>Hi, I'm Juan Pablo 👋</h2>
  <h4 align="center" id="heading">Data Scientist, Developer and Economist</h4>
</div>


```Python
import json

class Resume():

  def __init__(self, name = "Juan Pablo", last_name = "Chica Castrillón", ""):
  
    self.code = [
        "Python", "R", "SQL","NoSQL"
        ]
    
    self.ask_me_about = [
        "Data Science", "Machine Learning", "Optimization", "Games Theory"
        ] 
    
    self.knowledge = {

        "Unsupervised Learning" : {
            "topics" : ["PCA", "K-Means", "hierarchical clustering", "KNN"],
            "Fraameworks & Libraries" :["scikit-Learn"]
            },

        "Supervised Learning" : {
            "Topics": ["Deep Learning", "NLP",  "Convolutional NN", "Recurrent NN", "LSTM NN",
                       "Multi layer perceptron", "Linear Regression","Support vector machine",
                       "Decision Trees", "ARIMA models"],
            "Fraameworks & Libraries": ["TensorFLow","PyTorch", "Scikit-Learn","Keras","statsmodels"]
            },

        "Reinforcement Learning" : {
            "Topics": ["classic control", "Robotics", "Algorithms", "Finance"],
            "Fraameworks & Libraries": ["Keras RL", "TensorFlow RL","Stable-baselines"]
            },

        "Optimization" : {
            "Topics": ["Static Optimization", "Dynamic Optimization"],
            "Fraameworks & Libraries": ["Gekko", "Scipy"]
            }
        }

    self.databases = [
        "mongo", "MySql", "sPostgreSQL","Netezza", "SQL Server"
         ]

    self.backend = [
          "Flask", "FastAPI"
           ]

    self.misc = [
          "Spark","DataBricks","Selenium", "BeautifulSoup", "NLTK", "Pandas", "Numpy", "SqlAlchemy", "DASH" 
            ]

    self.architecture = [
          "Web Services", "Lambda (Serverless)"
          ]

    self.cloud_technoliges = [
          "AWS", "Azure"
          ]

    self.learning_goals = [
          "NEAT", "Transformers", "UX", "UI", "JavaScript"
          ]

  def __str__(self):

      consolidated_resume =  {
          "Ask Me About" : self.ask_me_about,
          "Code Knowledge" : self.code,
          "Topics Knowledge" : self.knowledge,
          "Databases Knowledge": self.databases,
          "Backend Knowledge" : self.backend,
          "Architecture Knowledge" : self.architecture,
          "Cloud Knowledge" : self.cloud_technoliges,
          "Miscellaneous" : self.misc,
          "Learning Goals" : self.learning_goals
          }
      return json.dumps(
          consolidated_resume,
          indent = 4
          )
           

print(
    Resume()
    )
 
```

<h2 align = "center" font-weight =  bold> My Projects 💬 </h2>


<h3 font-weight =  bold align = "center"> Optimal Portfolio Delivery Service  💵📈 </h3>
<h3 font-weight =  bold> Topics: </h3>
<p>
  <span>
    <span style = "pading : 2px; display: inline;">
      <img src="https://img.shields.io/badge/-Optimization-black" />
    </span>
    <span style = "pading : 2px; display: inline;">
      <img src="https://img.shields.io/badge/-Financial Markets-critical" />
    </span>    
    <span style = "pading : 2px; display: inline;">
      <img src="https://img.shields.io/badge/-Web Service-success" />
    </span>
    <span style = "pading : 2px; display: inline;">
      <img src="https://img.shields.io/badge/-Time Series-informational" />
    </span>

  </span>
</p>

<h3 font-weight =  bold> Stack: </h3>
<p>
  <span>
    <span style = "pading : 2px; display: inline;">
      <img src="https://img.shields.io/badge/-Python-yellow" />
    </span>
    <span style = "pading : 2px; display: inline;">
      <img src="https://img.shields.io/badge/-MySQL-blue"/>
    </span>
    <span style = "pading : 2px; display: inline;">
      <img src="https://img.shields.io/badge/-FastAPI-brightgreen" />
    </span>
    <span style = "pading : 2px; display: inline;">
      <img src="https://img.shields.io/badge/-SQLAlchemy-red"/>
    </span>
    <span style = "pading : 2px; display: inline;">
      <img src="https://img.shields.io/badge/-Pandas-blueviolet"/>
    </span>
    <span style = "pading : 2px; display: inline;">
      <img src="https://img.shields.io/badge/-Numpy-ff69b4"/>
    </span>
    <span style = "pading : 2px; display: inline;">
      <img src="https://img.shields.io/badge/-Scipy-yellowgreen"/>
    </span>
    <span style = "pading : 2px; display: inline;">
      <img src="https://img.shields.io/badge/-Yahoo Finance API-430297"/>
    </span>
    <span style = "pading : 2px; display: inline;">
      <img src="https://img.shields.io/badge/-Selenium-AAAAAA"/>
    </span>
    <span style = "pading : 2px; display: inline;">
      <img src="https://img.shields.io/badge/-BeautifulSoup-green"/>
    </span>
  </span>
</p>
<br>

<h3 font-weight =  bold> About the project </h3>
<span>
  <b>Portfolio Delivery Service</b> (PDS) is web service offered to minimize the risk-return tradeoff of an investment portfolio. Through an optimization model, based on the 
  <i>Modern Portfolio Theory</i> by Harry Markowitz (1952), and performing built-in customer risk assessment, PDS is capable to give advice about asset allocation and offers a 
  group of custom-made portfolios. Furthermore, the built-in algorithm is more time-stable and scalable than current machine learning models that are input-size and 
  training-sample dependent.  Hence, this project displays how a complex theory-based optimization model could be implemented to put into production and give real life 
  solutions for the clients.
</span> 

<h3 font-weight =  bold> Repositories: </h3>

<span>
  This list of repositories contain all the required scripts to replicate the project, the list will be presented in order to maintain the suggested track of development, but 
  each repository works independent from others in case that just one specific functionality want to be taken.
</span>
<br>

<ul>

  <li>
    <h4 font-weight = bold> 
      <a href = https://github.com/JuanPChicaC/Optimization/tree/main/Static%20Optimization/Portfolio%20Optimization%20Model#portfolio-optimization-model-folder>
        Portfolio Optimization Model
      </a>
    </h4>
    <p>
      The <b><i>Portfolio Optimization Model</i></b> repository contains all the explanation related with the <b><i>Markowitz optimization problem</i></b> that has to be solved 
      to give advice about assets participation in the portfolio. Additionally, it contains the library that generalize the usage for any possible selected portfolio. 
    </p>
  </li>

  <li>
    <h4 font-weight = bold> 
      <a href = https://github.com/JuanPChicaC/DataBases/tree/main/SQL/Portfolio%20Optimization%20DataBase>
        Portfolio optimization Database
      </a>
    </h4>
    <p>
      The <b><i>Portfolio optimization Database</i></b> repository has all the files required to create the storage instace that will support the <b><i>Optimal Portfolio 
      Delivery Service</i></b> data saving requirements, it includes:
    </p>
    <ul>
      <li>
        <a href = https://github.com/JuanPChicaC/DataBases/blob/main/SQL/Portfolio%20Optimization%20DataBase/DataBase_ERD.png>
          ERD of the database
        </a>  
      </li>
      <li>
        <a href = https://github.com/JuanPChicaC/DataBases/blob/main/SQL/Portfolio%20Optimization%20DataBase/database_model.py>
          Database codification
        </a>  
      </li>
      <li>
        <a href = https://github.com/JuanPChicaC/DataBases/blob/main/SQL/Portfolio%20Optimization%20DataBase/triggers.py>
          Triggers Codification
        </a>
      </li>
      <li>
        <a href = https://github.com/JuanPChicaC/DataBases/blob/main/SQL/Portfolio%20Optimization%20DataBase/procedures.py>
          Store Procedures codification
        </a>
      </li>
      <li>
        <a href =https://github.com/JuanPChicaC/DataBases/blob/main/SQL/Portfolio%20Optimization%20DataBase/functions.py>
          Functions definition
        </a>
      </li>
      <li>
        <a href = https://github.com/JuanPChicaC/DataBases/blob/main/SQL/Portfolio%20Optimization%20DataBase/database_update.py>
          First data update
        </a>
      </li>
    </ul>    
  </li>

  <li>
    <h4 font-weight = bold> 
      <a href = https://github.com/JuanPChicaC/Optimization/tree/main/Static%20Optimization/Portfolio%20Optimization%20Model#portfolio-optimization-model-folder>
        Yahoo Finance ETL Process
      </a>
    </h4>
    <p>
      The repository contains the data pipeline that was used to update the "asset", "type of asset" and "exchange" tables that were contained in the database. the layers are:
      <ul>
        <li>
          <p><b>Extraction Layer</b></p>
          <p>Web Scraping in 
            <a href = https://finance.yahoo.com/lookup>
            Yahoo Finance symbols list
            </a>
          </p>
        </li>
        <li>
          <p><b>Transformation Layer</b></p>
          <p>In this layer, the raw information that comes from yahoo finance is normalized to fit in database structure</p>
        </li>
        <li>
          <p><b>Load Layer</b></p>
          <p>here, the informatiuon is pushed into 
            <a href = https://github.com/JuanPChicaC/DataBases/tree/main/SQL/Portfolio%20Optimization%20DataBase>
              Portfolio Optimization DataBase
            </a>
          </p>
        </li>
    </ul>
    </p>
  </li>

</ul>




  
  
  
<br>
<br>
<br>
<h3 font-weight =  bold> Salaries Suggestion Service 💼📊 </h3>
<h4 font-weight =  bold> Stack: </h4>

<h4 font-weight =  bold> About the project </h4>




<!--
**JuanPChicaC/JuanPChicaC** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
