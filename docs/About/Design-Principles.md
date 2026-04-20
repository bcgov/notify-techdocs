# Design Principles

## 1. API-First & Asynchronous

Notifications are NOT synchronous.

- API creates a queue entry
- Delivery happens asynchronously

Supported via:
- Polling (GET /notify/{id})
- Callbacks (webhooks)

---

## 2. Separation of Concerns

Applications:
- Trigger events

Admins:
- Define templates
- Configure recipients
- Choose channels

---

## 3. Flexibility (Overrides)

Supports:
- Full defaults
- Partial overrides
- Fully custom notifications

---

## 4. Idempotency

Duplicate requests are prevented:
- Same payload within time window → ignored
- Override flag allows re-send

---

## 5. API Standards

- Rate limiting
- Correlation IDs
- Pagination
- Error handling
