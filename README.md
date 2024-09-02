# Break Reminder Notification python program

## Overview
This Python code helps you maintain a healthy work-life balance by reminding you to take a break every hour. The script sends a desktop notification using the `plyer` library with a message encouraging you to rest.

## Features
- Sends a desktop notification every hour.
- Customizable notification title and message.
- Lightweight and easy to use.

## Installation
1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/break-reminder.git
   cd break-reminder
## Install Required Dependencies This script requires the "plyer" library. Install it using pip:
  pip install plyer

##  Customization
  You can customize the notification title, message, and interval by modifying the following lines in the code:
 
  notification.notify(
      title = "ALERT!!!",
      message = "Take a break! It has been an hour!",
      timeout = 10
  )
  time.sleep(3600)  # Time in seconds
