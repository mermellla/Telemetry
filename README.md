# DIMO Telemetry

https://github.com/awslabs/amazon-kinesis-client-python
https://github.com/aws-solutions/streaming-data-solution-for-amazon-kinesis-and-amazon-msk/blob/main/source/docs/README-Kinesis.md

High Level Architecture:

-Web app requests authentication from wallet/account
-Consumes telemetry data

Amazon API>Kinesis>Lambda>Step Function (Smart Contract) 


-Logic for low emissions driving (EPA Fuel Economy Dataset)
-If determines low emissions:
-SmartContract:
-ratio of score to token amount
-deposits into wallet (built off DIMO, Polygon or Eth?) 

Update web dashboard with total earnings and patterns over time of emissions metrics 

**DIMO Authentication**
-CloudFront

**Amazon API Gateway**

**Kinesis**
In-stream data refers to the capability of processing a data stream that collects, processes, and analyzes data.

Lambda

Function for determining low emissions driving
-stack ranked for best driving on the network 

Step Function**
-Smart Contract Implementation

Web Interface:
-CloudFront
-Earnings over time
-Actual Data tracked
-make data public for NFT vehicle

