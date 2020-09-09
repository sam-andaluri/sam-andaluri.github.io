# Solution Portfolio

The following are a list of solutions I developed for customers and for citizen science projects.

## Amazon MQ Disaster Recovery Architecture

Customers using Amazon MQ frequently ask for a cross region DR. This [solution](https://github.com/sam-andaluri/BrokerSync) provides a way to copy messages from primary region to DR region and keep the messages in Sync between regions.

## Amazon MQ CloudWatch Dashboard

Amazon CloudWatch provides a rudimentary service dashboard and widgets for building custom dashboards. However, the default dashboards are difficult to read and interpret. This [solution](https://github.com/sam-andaluri/mqdashboard) provides enriched dashboard where users can see the brokers (primary/standby), queues and topics and drill down to queue and topic level metric charts.

## Cross Region/Cross Account Dashboard Architecture

Many enterprise customers in AWS use multiple accounts to seggegate their workloads (by project/environment). Quite often, this could results in 10s or 100s of accounts. This [solution](https://github.com/sam-andaluri/dashboard-poc) provides an architecture that helps customers to leverage [Amazon CloudWatch Cross Region/Cross Account dashboard functionality](https://aws.amazon.com/about-aws/whats-new/2019/11/amazon-cloudwatch-launches-cross-account-cross-region-dashboards/) along with auto-generated CloudWatch dashboards. The account level quotas and personal health events are also integrated into this solution. 

## Classifying Cloud types using cloud vision APIs

NASA runs a citizen science project named [Globe](https://observer.globe.gov). This project consists of collecting data on Cloud and Land cover classification and mosquito habitats. My children participate in the cloud cover program. The solution for this born out of question from my 13 year old daughter: If a computer vision model can identify a cat or dog, can it identify a cloud tyoe by its shape?. To answer that question, together we set out on a journey to see how well the different cloud provider vision algorithms can identify the cloud cover. This led down a path to learn machine learning and computer vision. The following are complete solutions including a human-in-the-loop workflow for each of the three major cloud providers:

### Amazon Rekognition

### Google Cloud Vision

### Azure Vision



