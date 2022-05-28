# Machine-Learning-Devops-Engineer-Syllabus

Learning how to deploy machine learning models is a challenging situation as of today the 28th of May 2022. A couple drawbacks due to lack of funds to purchase the udacity [Machine Learning Devops Engineer]('https://www.udacity.com/course/machine-learning-dev-ops-engineer-nanodegree--nd0821') course led to the creation of this repository.

This repo borrows state of the art syllable from the [Machine Learning Devops Engineer](https://www.udacity.com/course/machine-learning-dev-ops-engineer-nanodegree--nd0821) course from Udacity and spiced it up with different tutorial videos from [Youtube](youtube.com) for learning purpose.

**PS: This repo is only designed to help guide me in my journey learning MLOPs and is not in any way intended to discredit Udacity. All credit goes to Udacity for producing a well detailed syllable for learning Machine learning deployment operation and maintainance.**

## Prerequisites and Requirements

A well-prepared student will already be familiar with:


The data science process and overall workflow of building machine learning models
* Using Jupyter notebooks to solve data science-related problems
* Writing scripts using NumPy 
* Pandas 
* Scikit-learn 
* TensorFlow/PyTorch in Jupyter notebooks that clean data (as part of ETL), feed it into a machine learning model and validate the performance of the model
* Using the Terminal
* version control in Git, and using GitHub


# Module 1 <hr>
## Clean Code Principles
Develop skills that are essential for deploying production machine learning models. First, you will put
your coding best practices on autopilot by learning how to use PyLint and AutoPEP8. Then you will further
expand your Git and Github skills to work with teams. Finally, you will learn best practices associated with
testing and logging used in production settings to ensure your models can stand the test of time.

### LESSON ONE 
> **Coding Best Practices**
* Write clean, modular and well-documented code
* Refactor code for efficiency
* Follow PEP8 Standards
* Automate use of PEP8 standards using PyLint and AutoPEP8


Develop skills that are essential for deploying production machine learning models. First, you will put your coding best practices on auto-pilot by learning how to use PyLint and AutoPEP8. Then you will further expand your git and Github skills to work with teams. Finally, you will learn best practices associated with testing and logging used in production settings in order to ensure your models can stand the test of time.

### LESSON TWO
> **Working with Others Using Version Control**

* Work independently using git and Github
* Work with teams using git and Github
* Create branches for isolating changes in git and Github
* Open pull requests for making changes to production code
* Conduct and receive code reviews using best practices

### LESSON THREE Production
> **Ready Code**
* Correctly use try-except blocks to identify errors
* Create unit tests to test programs
* Track actions and results of processes with logging
* Identify model drift and when automated or non-automated retraining should be used to make model updates

# Module 2 <hr>
##  Building a Reproducible Model Workflow

This course empowers the students to be more efficient, effective and productive in modern, real-world
ML projects by adopting best practices around reproducible workflows. In particular, it teaches the
fundamentals of MLOps and how to: a) create a clean, organized, reproducible, end-to-end machine learning
pipeline from scratch using MLflow b) clean and validate the data using pytest c) track experiments, code and
results using GitHub and Weights & Biases d) select the best-performing model for production and e) deploy
a model using MLflow. Along the way, it also touches on other technologies like Kubernetes, Kubeflow, and
Great Expectations and how they relate to the content of the class.

## LESSON ONE 

> **Machine Learning Pipelines** 
* MLOps fundamentals
* Version data and artifacts
* Write a ML pipeline component
* Link together ML components
## LESSON TWO 
> **Data Exploration and Preparation**
* Execute and track the Exploratory Data Analysis (EDA)
* Clean and pre-process the data
* Segregate (split) datasets

## LESSON THREE 
> **Data Validation**
* Use pytest with parameters for reproducible and
automatic data tests
* Perform deterministic and non-deterministic data tests

## LESSON FOUR
> **Training, Validation and Experiment Tracking**
* Tame the chaos with experiment, code and data tracking
* Track experiments with W&B
* Validate and choose best-performing model
* Export model as an inference artifact
* Test final inference artifact

## LESSON FIVE 
>**Release and Deploy**
* Release pipeline code
* Options for deployment and how to deploy a model

# Module 3 <hr>
## Deploying a Scalable ML Pipeline in Production

This course teaches students how to deploy a machine learning model into production. En route to that
goal, students will learn how to put the finishing touches on a model by taking a fine-grained approach
to model performance, checking bias and ultimately writing a model card. Students will also learn how to
version control their data and models using Data Version Control (DVC). In the last piece of preparation
for deployment, students will learn Continuous Integration and Continuous Deployment accomplished
using GitHub Actions and Heroku. Finally, students will learn how to write a fast, type-checked and auto-
documented API using FastAPI.

## LESSON ONE
> **Performance Testing and Preparing a Model for Production**
* Analyze slices of data when training and testing models
* Probe a model for bias using common frameworks such as Aequitas
* Write model cards that explain the purpose, provenance and pitfalls of a model
## LESSON TWO 
> **Data and Model Versioning**
* Version control data/models/etc locally using DVC
* Set up remote storage for use with DVC
* Create pipelines and track experiments with DVC
## LESSON THREE 
> **CI/CD**
* Follow software engineering principles by automating, testing and versioning code
* Set up Continuous Integration using GitHub Actions
* Set up Continuous Deployment using Heroku
## LESSON FOUR 
> **API Deployment with FastAPI**
* Write an API for machine learning inference using FastAPI
* Deploy a machine learning inference API to Heroku
* Write unit tests for APIs using the requests module


# Module 4<hr>
## Automated model scoring and monitoring


This course will help students automate the DevOps processes required to score and re-deploy ML
models. After model deployment, you will set up regular scoring processes, learn to reason carefully about
model drift, and whether models need to be retrained and re-deployed. Students will learn to diagnose
operational issues with models, including data integrity and stability problems, timing problems and
dependency issues. Finally, students will learn to set up automated reporting with APIs.

## LESSON ONE 
> **Model Training and Deployment**
* Ingest data
* Automatically train models
* Deploy models to production
* Keep records about processes
* Automate processes using cron jobs

## LESSON TWO Model Scoring and
> **Model Drift**
* Automatically score ML models
* Keep records of model scores
* Check for model drift using several different model drift tests
* Determine whether models need to be retrained and re-deployed

## LESSON THREE
> **Diagnosing and Fixing Operational Problems**
* Check data integrity and stability
* Check for dependency issues
* Check for timing issues
* Resolve operational issues

## LESSON FOUR
> **Model Reporting and Monitoring with APIs**
* Create API endpoints that enable users to access model results, metrics and diagnostics
* Set up APIs with multiple, complex endpoints
* Call APIs and work with their results
