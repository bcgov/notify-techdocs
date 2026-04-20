# Functionalities

## Notification Types

### 1. Simple Notifications
Send direct messages without templates.

### 2. Template Notifications
Use predefined templates with dynamic placeholders.

### 3. Event-Driven Notifications
Trigger notifications based on system events.

---

## Templates

Templates define reusable notification structures.

### Features:
- Dynamic placeholders
- Channel-specific formatting
- Versioning support

---

## Attachments

Supported attachment types:

- Inline (Base64 encoded)
- URL-based
- Template-driven attachments

---

## Overrides

Overrides allow runtime customization:

```json
{
  "overrides": {
    "subject": "Custom Subject"
  }
}
```
