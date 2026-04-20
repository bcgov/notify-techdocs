# Callbacks

## Request

```json
{
  "callback": {
    "url": "https://api.app.com/callback",
    "events": ["DELIVERED", "FAILED"]
  }
}
```

## Response
```json
{
  "status": "DELIVERED",
  "channel": "email"
}
```

## Notes
* Triggered per channel
* Supports retries
