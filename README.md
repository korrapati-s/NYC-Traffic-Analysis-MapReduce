# NYC-Traffic-Analysis-MapReduce

Once you clone the repository into CScloud you need change directory to the cloned repository and execute the following command

> **hadoop jar /usr/hdp/2.6.3.0-235/hadoop-mapreduce/hadoop-streaming-2.7.3.2.6.3.0-235.jar -file mapper.py -mapper mapper.py -file reducer.py -reducer reducer.py -input /data/nyc/nyc-traffic.csv -output pyOut**

In order to view the output, run the below command

> **hadoop fs -cat pyOut/***
