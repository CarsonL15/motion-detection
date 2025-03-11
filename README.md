# Motion Detection Notification System

A Flask-based motion detection control panel for managing Pushover notifications. Designed for Raspberry Pi with a PIR sensor, this project now includes an advanced AI module for intelligent object recognition and human detection. This enhancement minimizes false alerts by ensuring that notifications are triggered only by relevant motion events. Developed using Python, Flask, JavaScript, HTML, CSS, and SQLite, with remote deployment via VS Code Remote SSH.

## Features

- **Motion Detection**: Uses a PIR sensor to detect movement.
- **AI Object Recognition & Human Detection**:  
  Leverages advanced deep learning algorithms to identify objects and specifically detect human figures. This feature enhances the system's accuracy by filtering out irrelevant motion and reducing false notifications.
- **User Management**: Add and remove users with unique Pushover keys.
- **Notification Control**: Toggle notifications per user using checkboxes.
- **Web-Based UI**: Built with Flask, HTML, CSS, and JavaScript.
- **Remote Deployment**: Managed via VS Code Remote SSH.

## Technologies Used

- **Python** (Flask for web server)
- **JavaScript** (Frontend interactivity)
- **HTML & CSS** (User interface)
- **JSON** (User data storage)
- **Pushover API** (Push notifications)
- **Raspberry Pi** (Motion sensor hardware)
- **VS Code Remote SSH** (Remote development & deployment)
- **AI Frameworks** (Integrated deep learning models for object recognition and human detection)

## Usage

- **Start/Stop Motion Detection:** Control the sensor from the web interface.
- **Manage Users:** Add users and adjust notification preferences.
- **Monitor Events:** Track motion events, with the AI module filtering for objects and human activity, and receive real-time alerts on your mobile device.
