## 🔔 Custom Notification Module for Odoo

### 📘 Overview

The **custom_notification** module for Odoo provides a robust and user-friendly notification system that integrates seamlessly with both backend and frontend. Users receive real-time alerts within the Odoo interface, enhancing productivity and communication.

### 🚀 Features

- ✅ **Notification Model**  
  Stores notifications with fields for:
  - Title & message
  - Related user
  - Read/unread status
  - Associated action data (model, record ID, view mode)

- 🔗 **Dynamic Action Handling**  
  Notifications can link to specific Odoo records, automatically redirecting users to the relevant view or form.

- 💬 **Frontend Interface**  
  - Dropdown in the system tray (systray)  
  - Unread badge count  
  - Relative timestamps (e.g., "5 minutes ago")  
  - “See More” button for pagination

- 🔄 **REST API Endpoints**  
  - Fetch notifications (JSON)  
  - Mark notifications as read

- 💻 **Responsive Design**  
  Styled to blend with Odoo’s UI for a consistent and intuitive user experience.
# 🔔 Custom Notification Module for Odoo

## 📘 Overview

The `custom_notification` module for Odoo provides a robust notification system that allows users to receive and manage notifications directly within the Odoo interface. Notifications appear in the system tray (systray) with a dropdown UI, showing:

- Unread notifications
- Titles, messages, and relative timestamps
- Interactive actions (e.g., redirect to records)
- Pagination support

Fully integrated with Odoo's backend and frontend using OWL (Odoo Web Library).

---

## 🚀 Features

- **Notification Model**  
  Stores title, message, user, read status, and record action details (model, record ID, view mode, etc.)

- **Dynamic Action Handling**  
  Redirect users to relevant records when clicking a notification.

- **Frontend Interface**  
  - System tray bell icon  
  - Unread count badge  
  - Relative timestamps  
  - "See More" button for pagination

- **REST API**  
  - JSON endpoints to fetch and update notification status

- **Responsive & Native Feel**  
  Styled to blend seamlessly with Odoo's UI.

---

## 📦 Dependencies

- Odoo **17.0 or later** (tested on 17.0)
- **No extra Python packages required**
- Uses **OWL** (Odoo Web Library) for frontend

---

## 🛠️ Installation

1. **Clone or Download the Module**
   ```bash
   git clone https://github.com/chalaa/custom_notification
