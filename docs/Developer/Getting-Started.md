# Getting Started

## Send Notification

POST /notifyevent

```json
{
  "notificationEventType": "funding-approved",
  "params": {
    "firstname": "John"
  }
}
```

## What Happens
* Event received
* Defaults resolved
* Notification created
* Queued in Redis
* Worker delivers
