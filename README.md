
# Process data with Apache Spark & Docker

Exploring Spark by processing public data sets obtained from kaggle. 

Answering some of the key questions when working with Spark: 
 * Why Spark
 * How Spark Works
 * Set up your dev environment  with Docker & Jupyter
 * Work with DataFrames (JSON & CSV)
 * Introduction into SparkSQL
 * Coding with RDDs
 * Conclusion
## Installation
Create a directory to store your docker files here

Setting up the docker environment and pull the image from the docker hub
```bash
  docker pull jupyter/pyspark-notebook
```
```bash
  docker run -p 8888:8888 -v PathWhereYouCreateYourDockerDirectory:/home/jovyan/work jupyter/pyspark-notebook
``` 

Once installed, to access the notebook click and open the links provided in the terminal

## DataSets
Download the dataset from here:
https://github.com/Sup3rRookie/Apache_Spark-Docker