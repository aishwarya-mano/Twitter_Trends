# Twitter Trends

Leveraged tweet data using the twitter API and displayed the same on a HeatMap using the Google Maps API while utilizing the ElasticSearch changefeed property to stream live data for a particular keyword using kafka and sns, thus reducing the overhead of polling the database constantly for new tweet data.

Used the Apache Kafka to create a processing queue for the Tweets that are delivered by the Twitter Streaming API.
Used Amazon SNS service to update the status processing on each tweet so the UI can refresh.
Integrated the third party cloud service API into the Tweet processing flow.
