# Introduction to AI/ML Toolkits with Kubeflow (LFS147x) Repo
## Environment Details
This repo should be publicly available. To develop these examples we used the Google Cloud Platform Distribution running Kubeflow version 1.8. The KFP version was kfp 2.4.0. The notebook image we used was kubeflownotebookswg/jupyter-scipy:v1.8.0
## Using this repo
The containers are all hosted in Dockerhub, but we provide the docker files and component files required to build these components yourself. To use this code simply create a Jupyter notebook in your Kubeflow 1.8 environement using the jupyter-scipy:v1.8.0 image. Then, clone this git repo. Once the repo has been cloned to your local environment, navigate to the directory of your choice based on the component you'd like to explore, click on the Jupyter Notebook (I.E. hello_kubeflow), read the notebook, and launch each cell in order. 

## Issue with Code
If you run into issues with code and examples please either submit an issue to the repo directly or make a comment on the forums. We are more than 
## Walkthrough videos 
Each example has a walkthrough video as part of the course. If you are stuck a good first step is to check out the walkthrough video that applies to the example you are working through. 
## Containers, Components, and Security.
The containers we built are for education and testing purposes only. We highly discourage deploying the components and containers in production environments without scanning and hardening. We also guarantee no support around the code or images provided beyond their specific course purpose. 
