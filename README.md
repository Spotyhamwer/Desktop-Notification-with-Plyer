# Desktop-Notification-with-Plyer
Display a desktop notification using the Plyer library.
from plyer import notification

title = 'Notification Title'
message = 'Notification Message'

notification.notify(
    title=title,
    message=message,
    app_icon=None,  # e.g., 'path/to/icon.png'
    timeout=10  # seconds
)
