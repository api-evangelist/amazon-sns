# Amazon SNS (amazon-sns)
Amazon Simple Notification Service (SNS) is a fully managed messaging service for both application-to-application (A2A) and application-to-person (A2P) communication. It enables pub/sub, SMS, email, and mobile push notifications.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-sns/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Email, Messaging, Notifications, Pub/Sub, Push Notifications, SMS

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-18

## APIs

### Amazon SNS API
RESTful API for Amazon Simple Notification Service providing topic management, subscription lifecycle, message publishing, platform application management for mobile push, and SMS messaging operations.

**Human URL:** [https://aws.amazon.com/sns/](https://aws.amazon.com/sns/)

#### Tags:

 - AWS, Messaging, Notifications

#### Properties

- [Documentation](https://docs.aws.amazon.com/sns/)
- [OpenAPI](openapi/amazon-sns-api-openapi.yml)
- [APIReference](https://docs.aws.amazon.com/sns/latest/api/welcome.html)
- [GettingStarted](https://docs.aws.amazon.com/sns/latest/dg/sns-getting-started.html)
- [Pricing](https://aws.amazon.com/sns/pricing/)
- [FAQ](https://aws.amazon.com/sns/faqs/)
- [BestPractices](https://docs.aws.amazon.com/sns/latest/dg/sns-best-practices.html)
- [Features](https://aws.amazon.com/sns/features/)
- [Security](https://docs.aws.amazon.com/sns/latest/dg/sns-security.html)
- [RateLimits](https://docs.aws.amazon.com/sns/latest/dg/sns-quotas.html)
- [CodeExamples](https://github.com/awsdocs/aws-doc-sdk-examples)
- [SDK - Python SDK](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html)
- [CLI](https://awscli.amazonaws.com/v2/documentation/api/latest/reference/sns/index.html)

## Common Properties

- [Blog](https://aws.amazon.com/blogs/messaging-and-targeting/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Console](https://console.aws.amazon.com/sns/)
- [Compliance](https://aws.amazon.com/compliance/services-in-scope/)
- [Support](https://console.aws.amazon.com/support/home)
- [KnowledgeCenter](https://aws.amazon.com/premiumsupport/knowledge-center/#Amazon_Simple_Notification_Service)
- [Partners](https://aws.amazon.com/sns/partners/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [GitHubRepository](https://github.com/awsdocs/amazon-sns-developer-guide)

## Features

| Name | Description |
|------|-------------|
| Pub/Sub Messaging | Fan-out messages to multiple subscribers through topics supporting HTTP/S, email, SQS, Lambda, and SMS protocols. |
| FIFO Topics | Strict message ordering and exactly-once delivery for use cases requiring sequence-preserving fan-out. |
| Message Filtering | Subscription filter policies enabling subscribers to receive only the messages relevant to them. |
| Mobile Push Notifications | Cross-platform mobile push via APNs, FCM, and other push services through platform applications. |
| SMS Messaging | Direct SMS text messaging to phone numbers worldwide with support for transactional and promotional messages. |
| Dead-Letter Queues | Capture undeliverable messages for analysis and reprocessing to ensure no messages are lost. |

## Use Cases

| Name | Description |
|------|-------------|
| Application Event Fan-Out | Broadcast application events to multiple microservices simultaneously using pub/sub topic subscriptions. |
| Mobile Push Campaigns | Send targeted push notifications to mobile applications across iOS and Android platforms. |
| Alert and Monitoring Systems | Deliver operational alerts via SMS, email, and HTTP endpoints for infrastructure monitoring. |
| Order Confirmation Notifications | Send transactional notifications for order confirmations, shipping updates, and account activity. |
| Cross-Account Event Distribution | Share events across AWS accounts using SNS topic policies for multi-account architectures. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon SQS | Fan out SNS messages to SQS queues for reliable asynchronous processing across multiple consumers. |
| AWS Lambda | Invoke Lambda functions directly from SNS notifications for serverless event processing. |
| Amazon EventBridge | Route SNS events through EventBridge for complex event-driven routing and filtering. |
| AWS CloudFormation | Define and manage SNS topics and subscriptions as infrastructure-as-code resources. |
| Amazon Kinesis Data Firehose | Deliver SNS messages to data lakes and analytics services through Kinesis Data Firehose. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon SNS API](openapi/amazon-sns-api-openapi.yml)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amazon SNS](capabilities/shared/sns.yaml) -- 20 operations for pub/sub messaging

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Pub/Sub Messaging](capabilities/pub-sub-messaging.yaml) | SNS | 16 | Developer / Platform Engineer |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
