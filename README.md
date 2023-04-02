# Real-Time-Twitter-Sentiment-Analysis
Performing real time twitter sentiment analysis. Implemented using python

Installations - kafka, spark, Elastic Search, Kibana, logstash
Necessary libraries (Python) - Spark, Kafka, Hadoop, tweepy, vader, pykafka, pyspark, nltk, Elasticsearch

Get the twitter official API for developers

Perform the kafka-spark integration as given in this link. To be run in the command prompt
https://github.com/binodsuman/kafka-spark-integration/blob/master/kafka-command.txt

Perform the instruction given in this video to download, install and start Elastic Search, Kibana and Logstash
https://www.youtube.com/watch?v=8iXZTS7f_hY&t=268s

Run the producer program. First provide the necessery authentication tokens provided by twitter API (Consumer Key, Consumer Secret Key, Access Token, Access Secret Token).

Create an appropriate index in elastic search where the data from Spark will be streamed into.

Provide that index name in the consumer program.

Run the Consumer program. The output along with the Sentiment Scores and other analysis will be stored in the Elastic Search. 

From there you could use Kibana to create appropriate visualizations and create a dashboard.
