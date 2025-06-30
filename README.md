##Custom Notification Module for Odoo

#Overview

The custom_notification module for Odoo provides a robust notification system that allows users to receive and manage notifications within the Odoo interface. Notifications are displayed in the system tray (systray) with a dropdown menu, showing unread notifications with titles, messages, and relative timestamps. Users can mark notifications as read and trigger associated actions (e.g., redirecting to specific records). The module supports pagination for loading more notifications and integrates seamlessly with Odoo's backend and frontend.

#Features

Notification Model: Stores notifications with fields for title, message, user, read status, and action-related data (model, record ID, view mode, etc.).
Dynamic Action Handling: Notifications can link to specific records in Odoo, redirecting users to the relevant form or view.
Frontend Interface: A system tray dropdown displays notifications with a badge for unread counts, relative timestamps, and a "See More" button for pagination.
REST API: JSON-based endpoints to fetch notifications and mark them as read.
Responsive Design: The notification dropdown is styled for usability and integrates with Odoo's UI.