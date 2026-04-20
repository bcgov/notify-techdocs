# Data Model

## Entities

### Tenant
Represents an organization using Notify.

### Template
Defines reusable notification structures.

### Notification
Represents a message instance.

### Event
Triggers notifications.

### Subscription
Defines callback listeners.

---

## Relationships

- Tenant → Templates
- Templates → Notifications
- Notifications → Callbacks
