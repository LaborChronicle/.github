# Notes
## Costs
We need to run this app at the lowest cost possible. That means we'll need to take the time to learn the ins and outs of using AWS. We'll want to use Rust wherever possible, and minimize Python as much as possible. Furthermore, we might need to use some data archiving techniques to minimize storage costs. 
## Tech Stack
API = AWS API Gateway

Monitoring/logging = AWS Cloudwatch

Crawling = AWS Lambda, Amazon EventBridge, Rust, Scraper (Python + BeautifulSoup if this is too hard)

Email Subscription = AWS Lambda, Python

Content Filtering, Deduplication = AWS Lambda, Python + Distilbert + scikit-learn for training, Rust as an entry point and preprocessing for triggering

Database = AWS DynamoDB (NoSQL), Rust

Frontend = TypeScript, React Native

Notifications = AWS SNS

Authentification = AWS Cognito