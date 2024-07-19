# About Kalpa

## Product
At [Kalpa](https://www.kalpa.com) we help clients generate personalized video content at scale using a range of first and third party services. Our product focuses on three main areas:
1. Allowing users to define custom content generation workflows, called Scenes. These workflows are represented as a directional, acyclic graph (also known as a tree), and are created in the Kalpa Scene Builder.
2. Collecting information, either from customers directly or from integrations with the services they use, to automatically generate unique videos for each set of inputs provided.
3. Distributing those videos on behalf of our clients, either to their team, to the applications they use, or their customers directly.

The services we leverage to define these content creation workflows includes a broad range of cutting edge AI services, as well as media manipulation software that we develop and maintain in house.

## Use Cases
Customers can use our platform for an endless range of use cases, for example:
- Generating personalized outreach emails for potential clients, where each video includes detailed information specifically relevant to the recipient, their company, and their specific role.
- Helping customer success representatives provide customers with detailed, personalized usage reports and analytics, including recommendations on how to get the most out of their product, as well as product and business updates relevant to each customer's unique needs.
- Allowing human resources to automatically generate personalized emails detailing information about healthcare or employee-specific perks and compensation packages to use during recruiting and onboarding.
- Automating the process of compiling weekly sales data into a high level performance summary to be delivered weekly to senior leadership or to the entire company.

While this process does leverage a lot of AI we intentionally do not deploy or maintain any large language models, and instead choose to incorporate the endless stream of new AI products being brought to market into our product. This ensures that the business is able to grow along with the broader AI tech universe, and lets us focus on our core competencies of defining, executing, and delivering personalized video content on behalf of our customers.

## Tech Stack
Kalpa's platform is hosted on Amazon Web Services, and leverages a variety of services, including but not limited to:
- RDS (Aurora PostGres)
- CloudFront
- CloudFormation
- API Gateway
- AWS Lambda
- CloudWatch
- S3
- AWS Transcribe
- Elasticache
- SES
- Identity Access Management
- AWS Translate
- SQS/SNS Messaging
- Elastic Container Registry

We strongly believe in maintain infrastructure using code, so we rely heavily on CloudFormation and custom Bash scripts to automatically audit our various applications and services. Code is hosted on GitHub and deployed using CircleCI.

Our front end is built with React, TypeScript and Vite, and our API is built in Python 3.11 using the FastAPI framework. In addition we have a number of Lambda scripts that we leverage to handle things such as delivering media, managing web sockets, and implementing server side rendering for social sharing and implementing the Open Graph protocol for our public facing sites.

## The Team
As of this writing the team is about 5 full time employees combined with a rotating set of part or full time contractors. We work closely with a team of front end engineers, designers, and UI/UX experts at [Z1 Digital](Z1 Digital). The worke exclusively on our front end applications, but they are very much embedded in the Kalpa engineering team. Both of Kalpa's founders have worked with them on previous projects, so it's about as close a relationship as can be had with an overseas contracting firm (they do great work).

## Workflow
The kalpa team is fully remote, so we rely heavily on project management and collaboration tools to communicate. We use Slack for day-to-day communications, Zoom for video calls, and Jira for project management. Platform architecture and technical documentation are all stored in Confluence.
