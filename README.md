# Tweet Extraction

This repository consists of configuration files:

* twitter-full.conf: Logstash configuration file
   
   1) Input is Twitter
   2) Output is Elasticsearch
   3) Filter option is filtering incoming tweets and getting important fields from tweets.
 
* extract-tweets-to-file.conf: Logstash configuration file
   
   1) Input is Elasticsearch
   2) Output is File
   3) Filter option is filtering incoming data from elasticsearch, modifying text or extended_text field of tweets.

## Getting Started

> **Important:** To use these configuration files, please fill the blank fields in the files.
