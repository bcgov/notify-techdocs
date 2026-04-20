## Simple Email

```json
{
  "to": ["me@example.com"],
  "subject": "Simple email",
  "body": "Hello world"
}
```

## Template Example
```json
{
  "template": {
    "subject": "{{subject}}",
    "body": "Hello {{name}}"
  },
  "params": {
    "subject": "Hi",
    "name": "Avinash"
  }
}
```

## Notification Event
```json
{
  "notificationEventType": "funding-approved",
  "params": {
    "firstname": "Lucky",
    "amount": "1000"
  }
}
```
flowchart LR
A[Event] --> B[Defaults]
B --> C[Template]
C --> D[Queue]
D --> E[Delivery]
