# Notification Management

## Tracking

Each notification includes:

- notifyId
- status
- statusUrl

---

## Status Lifecycle

- QUEUED
- PROCESSING
- SENT
- DELIVERED
- FAILED

---

## Callbacks

Notify supports webhook callbacks.

### Example

```json
{
  "notifyId": "12345",
  "status": "DELIVERED"
}
```
