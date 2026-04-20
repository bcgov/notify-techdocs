# Notify Service

Notify is a centralized, scalable notification platform designed to send communications across multiple channels including Email, SMS, and third-party integrations.

## Overview

The service supports both simple notifications and event-driven messaging using templates. It is designed for flexibility, scalability, and ease of integration across government systems.

## Key Features

- Multi-channel delivery (Email, SMS, 3rd Party)
- Template-based notifications
- Event-driven architecture
- Layered defaults (Global → Tenant → Template → Request)
- Callback and subscription support
- Notification tracking and status monitoring
- Attachment support
- Preview capability before sending

## Core Concepts

### Multi-Tenancy
Each tenant operates independently with its own:
- Templates
- Configuration
- Notification settings

### Layered Defaults
Configuration is applied in the following order:
1. Global Defaults  
2. Tenant Defaults  
3. Template Defaults  
4. Request Overrides  

### Idempotency
Each request can include a unique key to prevent duplicate notifications.

---
