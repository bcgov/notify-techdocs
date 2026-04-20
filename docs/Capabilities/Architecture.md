# Architecture

Notify uses an event-driven, asynchronous architecture.

---

## Components

- API Layer
- Database
- Redis Queue
- Worker Services
- Delivery Providers

---

## Flow

1. API receives request  
2. Data stored in database  
3. Notification pushed to Redis queue  
4. Worker processes notification  
5. Delivery provider sends message  
6. Status updated  
7. Callback triggered  

---

## Idempotency

Ensures duplicate requests are not processed multiple times.
