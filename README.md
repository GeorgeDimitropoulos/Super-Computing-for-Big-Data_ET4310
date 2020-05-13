# Super-Computing-for-Big-Data_ET4310
This repository contains the 3 projects that we implemented in Spark (in Scala) under the course Super Computing for Big Data during the MSc in Computer Science (Data Science specialization) at TU Delft the period 2017-2018

We had to process the entire GDELT dataset to analyze the 10 most common topics in the news for each day. The entire dataset consists of several terabytes, so a Spark application was made to do this analysis using Amazon Elastic MapReduce (EMR) and also to explain how we run our Spark application on the entire dataset using 20 c4.8xlarge spot instances in 12 minutes (the minimum goal was under half an hour) and how we managed to optimize the Spark application for our chosen metrics
