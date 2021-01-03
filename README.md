# Aim
Integrating the machine learning models into the streaming platform using Apache Kafka and Apache Spark Streaming to detect any real-time threats, in order to stop the hacking. 

# Related project
This project is related to the following project: https://github.com/SoyeonKim79/Detecting-Hacking-Activities-with-Stactic-Data (Detecting-Hacking-Activities-with-Static-Data) which investigated the open data and developed the machine learning models. In this project, we would need to create a proof-of-concept streaming application to demonstrate the integration of machine learning model, Kafka and Spark streaming and create visualisation for monitoring purpose.

# Information on Dataset
Two streaming data files are provided, which captures information relating to the Linux system’s process activity and memory activity. The machine information is also provided, which captures information relating to Linux machines.
The streaming data files are an adapted version of process and memory data from the
Internet of Things dataset collected by Dr. Nour Moustafa, using IoT devices, Linux systems, Windows systems, and network devices. For more detailed information on the dataset, please refer to the Metadata file or from the website
below https://ieee-dataport.org/documents/toniot-datasets .

In conclusion, streaming data created from files “ Streaming_Linux_process.csv ” and “ Streaming_Linux_memory.csv ” would be used to simulate the process and memory data streamed from cluster 1 for machines with ID of 4, 5, 6, 7, 8

# Tasks
* Task 1 <br>
Implement two Apache Kafka producers (one for process and one for memory) to simulate the real-time streaming of the data.

* Task 2 <br>
Implement multiple Apache Kafka consumers to consume the data from task 1.

* Task 3 <br>
Implement Spark Structured Streaming to consume the data from task 1. Also, perform predictive analytics by using a set of pre-trained pipeline models, one for predicting attack in process data, another for predicting attack in memory data.

+ dd

# Environment
* Ubuntu 20.04 LTS (Focal Fossa) 
* Python (3.8) 
* Jupyter Notebook 
* Apache Spark (3.0.0) 
* Apache Kafka (2.5.0) 
