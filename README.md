# Water Drinking Reminder with Notifications

A simple Python desktop reminder that sends periodic notifications to remind you to drink water.

The project focuses on practicing Python functions, loops, time-based execution, and desktop notifications using the `plyer` library.

## 🎥 Preview

## 🎥 Preview

[▶️ Watch Water Drinking Reminder Demo](./Preview/Water%20Drinking%20Reminder%20And%20Notification.mp4)

The preview demonstrates the Python script running in VS Code and the desktop notification appearing with the water reminder message.

## ✨ Features

- Sends desktop notifications for drinking-water reminders
- Displays a custom notification title
- Displays a custom reminder message
- Keeps the reminder running continuously
- Uses a configurable notification timeout
- Includes a short testing interval for quickly demonstrating notifications
- Uses Python's `time` module for scheduling the reminder delay

## 🎯 Project Overview

The Water Drinking Reminder is a lightweight Python utility designed to provide periodic desktop reminders to drink water.

The application runs continuously and triggers a desktop notification at the configured interval.

For normal use, the reminder interval can be set to one hour. During development and testing, the interval is reduced to a few seconds so the notification can be demonstrated quickly.

## 🔄 How It Works

    1. The program imports Python's time module.
    2. The Plyer notification module is imported.
    3. A water_reminder() function is created.
    4. The function runs continuously using a while loop.
    5. A desktop notification is generated using notification.notify().
    6. The notification displays a custom title and reminder message.
    7. The program waits for the configured time interval.
    8. The process repeats continuously.

## 🔔 Notification

The application displays a desktop notification with:

    Title:
    Water Reminder for Dheeraj

    Message:
    Time to sip some water!

The notification remains visible for the configured timeout period.

## ⏱️ Reminder Interval

The code includes a normal one-hour reminder interval:

    time.sleep(3600)

For testing purposes, the project currently uses:

    time.sleep(3)

This allows the notification to appear every few seconds during demonstration and testing.

The testing interval can be changed back to `3600` seconds for an hourly reminder.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Application development |
| `time` | Controlling the reminder interval |
| `plyer` | Creating desktop notifications |
| `while` loop | Running the reminder continuously |
| Functions | Organizing reminder logic |

## 📁 Project Structure

    Water-Drinking-Reminder-with-Notifications/
    │
    ├── Preview_video/
    │   └── Water Driking Reminder And Notifiaction.mp4
    │
    ├── main.py
    │
    └── README.md

## ▶️ Run Locally

### 1. Clone the Repository

    git clone https://github.com/dheerajmishra75/Water-Drinking-Reminder-with-Notifications.git

### 2. Navigate to the Project

    cd Water-Drinking-Reminder-with-Notifications

### 3. Install the Required Package

    pip install plyer

### 4. Run the Application

    python main.py

Once the program starts, it will continuously generate the configured desktop water reminder notifications.

## 🧪 Testing

For demonstration purposes, the reminder interval is set to 3 seconds.

This makes it possible to verify the notification functionality without waiting for the normal hourly interval.

For regular use, change:

    time.sleep(3)

to:

    time.sleep(3600)

## 📚 Python Concepts Practiced

This project helped practice:

- Importing Python modules
- Functions
- `while` loops
- Infinite loops
- Time delays using `time.sleep()`
- External Python packages
- Desktop notification APIs
- Function calls
- Basic application automation

## 🎯 Learning Outcomes

Through this project, I practiced how to:

- Work with Python's standard `time` module
- Use an external Python package
- Create desktop notifications
- Build a continuously running utility
- Control execution intervals
- Organize functionality inside a reusable function
- Test time-based functionality using shorter intervals

## 🚀 Future Improvements

Possible improvements for future versions include:

- User-configurable reminder intervals
- Start and stop controls
- Custom reminder messages
- Daily reminder schedules
- Notification sounds
- System tray support
- GUI-based settings
- Enable/disable reminder controls

## 🔗 Project Links

- GitHub: https://github.com/dheerajmishra75/Water-Drinking-Reminder-with-Notifications

## 👨‍💻 Author

**Dheeraj Mishra**

B.Tech CSE Student | Python | Data Science | Machine Learning | Backend Development

## 📌 Disclaimer

This project was created for learning and practice purposes. It is a simple desktop reminder utility and is not intended to provide medical or health-related guidance.
