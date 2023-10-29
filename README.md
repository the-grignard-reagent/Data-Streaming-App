# Kafka-YoutubeWatcher

## Overview
- ► Uses Python to fetch and process data from a static web API 
- ► Streams that data live, from Python into a Kafka (by Confluent Cloud) topic 
- ► Processes the incoming source data with ksqlDB, watching for important changes 
- ► Then streams out live, custom notifications via Telegram

## ► Dependencies
- confluent_kafka >= 1.8
- python-dateutil >= 2.8
- types-requests >= 2.27
- requests >= 2.25
- fastavro >= 1.4
