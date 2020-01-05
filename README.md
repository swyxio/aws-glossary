# aws-glossary


## AppSync

### Pipeline Resolvers

Pipeline Resolvers allows you to break up resolvers (the code that runs in response to a network request) into multiple steps, share code across resolvers, and orchestrate calls requiring multiple data sources. These new capabilities unlock new scenarios for data aggregation and authorization in a GraphQL API. You can mix and match actions from any supported data source such as Amazon DynamoDB, AWS Lambda, or HTTP endpoints.

### Delta Sync

Delta Sync optimizes the end user experience when the device switches from offline to online, providing automatic network reconnection and synchronization of only changed database items to the client cache. This new SDK feature can be used with standard GraphQL queries against a single data source, or combined with the new Pipeline Resolvers to optimize your backend into a journal of changed events. Delta Sync is available for JavaScript, iOS, and Android client SDKs.

- https://docs.aws.amazon.com/appsync/latest/devguide/tutorial-delta-sync.html

### Data Source

An Aurora Serverless Data Source is now built in, enabling you to access Aurora Serverless using GraphQL. This functionality leverages the new Aurora Serverless Data API to efficiently manage connections and allows customers to leverage a relational database within AppSync without using a Lambda function as the intermediary.
