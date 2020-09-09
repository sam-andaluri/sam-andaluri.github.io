# Solution Portfolio

The following are a list of solutions I developed for different customers.

## Amazon MQ Disaster Recovery Architecture

Customers using Amazon MQ frequently ask for a cross region DR. This [solution](https://github.com/sam-andaluri/BrokerSync) provides a way to copy messages from primary region to DR region and keep the messages in Sync between regions.

## Amazon MQ CloudWatch Dashboard

Amazon CloudWatch provides a rudimentary service dashboard and widgets for building custom dashboards. However, the default dashboards are difficult to read and interpret. This [solution](https://github.com/sam-andaluri/mqdashboard) provides enriched dashboard where users can see the brokers (primary/standby), queues and topics and drill down to queue and topic level metric charts.

## Cross Region/Cross Account Dashboard Architecture

Many enterprise customers in AWS use multiple accounts to seggegate their workloads (by project/environment). Quite often, this could results in 10s or 100s of accounts. This [solution](https://github.com/sam-andaluri/dashboard-poc) provides an architecture that helps customers to leverage [Amazon CloudWatch Cross Region/Cross Account dashboard functionality](https://aws.amazon.com/about-aws/whats-new/2019/11/amazon-cloudwatch-launches-cross-account-cross-region-dashboards/) along with auto-generated CloudWatch dashboards. The account level quotas and personal health events are also integrated into this solution. 
