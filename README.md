# DatalakeDemo



Process :
   -> Files can flow into Amazon S3 through any channel.
   ->File creation in Amazon S3 produces an event you can catch with a Lambda function.
   ->The Lambda function retrieves data and metadata from Amazon S3, and pushes it into Amazon ES.
   ->Using Direct Amazon ES API calls or, at a larger scale, Amazon Kinesis Data Firehose can be used to populate Amazon ES. 
   -> You can also use Logstash, which is a data-collection and log-parsing engine.
   ->Further you can use Comprehend to analyse the data behavior 
   
   
   
