# Project 2: Tracking User Activity

This README.md will start with the description of the project. A description of each of the files in the directory will follow afterwards.

Given a set of JSON assessment data (see file for specifics), read the data into Kafka and process it with spark. Then write the transoformed messages to HDFS. In addition, do some spark SQL to model possible work done through this pipeline.

- Project_2_Report.ipynb
    * This is the overall summary of everything I did. Goes through each part of the project, providing highlights and commenting on work. This is where the business questions are answered (though code to get the answers is in SparkCode.ipynb).
- SparkCode.ipynb
    * This is the jupyter notebook format of pyspark which contains all code used in the pyspark process. This includes code for consuming the messages off of Kafka, unrolling them in a couple of different ways to create tables, running sql queries against those tables, and writing the tables to HDFS in parquet format.
- assessments-attempts-20180128-121051-nested.json
    * This is the original Json dataset used in the project
- docker-compose.yml
    * This is the yml file for the project. Provides all images/services used in the project, includes the edits to spark to allow for work to be done in a jupyter notebook.
- isaacvernon1-history.txt
    * The .txt file derived from getting command line history. Contains more than just the commands used in the project. Not recommended to look at (here because project mentioned doing .txt file this way)
- isaacvernon1.txt
    * Cleaned and commented version of the previous text file. Contains all the commands used in this project, recommended for use as the .txt file for the project.



