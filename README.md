# Deploying-term-frequency-application-in-Kubernetes

This project was developed as part of my Masters course study in Cloud Computing and Distributed Systems.

Contributions: Prudhviraj Sheela, Nandhini Veluswamy, Fei Liang 

The main motive of this project is to port the PySpark application for finding Term Frequency (TF) to Kubernetes through the concept of containerization using Docker.

Softwares Used: Docker, Kubernetes

IDE Used: Jupyter Notebook

Dataset Used: Wikipedia Articles

Description about the files:

1)Dockerfile: This helps in installing the necessary operating system and also contains the required dependencies to be downloaded in the system such as Python and Spark as part of my project developed.

2)run.sh: This shell script contains all the commands to run the python script as well as all the basic python and linux commands to create folders and move files into it.

3)Parse_wikipedia_data.py: Python script required to parse the downloaded wikipedia articles to text files

4)TF1.py: PySpark program written to preprocess the text files and creates a log-weighted term frequency for the terms in the document.

5)TF1_query.py: PySpark program written to query the documents on the index created to retrieve relevant files matching the query.

6)Sample.txt: Contians the user inputs to be queried on the created index.

7)test_PySpark_deployment.yaml: This is an Yet Another Markup Language file used to deploy the created docker file in Kubernetes using the concept of containerization.

8)CC Project Report: This is the documentation of the entire project and the steps followed in its development accordingly.

Output Files: The explanation about the output generated is available in the project report which explains clearly each step on how is the end result obtained.
