# NoteNest Notification Service

NoteNest Notification Service manages system and user-triggered notifications.

## Responsibilities

- Note share alerts
- Tag update notifications
- Collaboration messages
- System announcements
- Asynchronous event processing

## Architecture

Built with:

- AWS Lambda
- Amazon SNS
- Amazon EventBridge (optional)
- CloudWatch Logs

Event Flow:

1. Note event occurs
2. Event published to SNS
3. Lambda processes notification
4. Notification delivered to user

## AWS Always Free Tier Usage

- Lambda
- SNS messaging
- EventBridge routing
- CloudWatch logs

## Design Pattern

- Event driven architecture
- Decoupled services
- Asynchronous communication

## Portfolio Value

Demonstrates scalable serverless messaging architecture.
