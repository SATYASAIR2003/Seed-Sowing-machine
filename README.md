# Automated Seed Sowing Machine

A Bluetooth-controlled Automated Seed Sowing Machine built using Arduino Uno, ultrasonic sensor, and a servo-based seed dispensing mechanism. This system automates the seed sowing process, detects obstacles, minimizes seed wastage, and improves overall farming efficiency. It is controlled through a custom MIT App Inventor Android application that provides real-time updates and wireless control.

# Objectives

To develop a Bluetooth-controlled automated seed sowing machine.
To achieve precision in seed placement using a servo-controlled dispensing mechanism.
To reduce manual labor and improve operational efficiency for farmers.
To implement real-time obstacle detection using an ultrasonic sensor.
To minimize seed wastage through automatic seed flow control.
To create a cost-effective and user-friendly smart farming solution.
To integrate a mobile app for wireless control and live updates.
To enhance productivity and consistency in the sowing process.
To ensure adaptability across different soil and field conditions.
To promote sustainable and modern agricultural practices.

# Features

Bluetooth-based wireless control
Automated seed dispensing using a servo motor
Ultrasonic sensor for real-time obstacle detection
Buzzer alerts for warnings and completion
Mobile app with Start, Stop, and Reset functions
Designed using CATIA with modular hardware assembly

# Hardware Used

Arduino Uno
HC-05 Bluetooth Module
Ultrasonic Sensor (HC-SR04)
Servo Motor
500 RPM Geared Motors
Motor Driver Shield
12V 7Ah Battery
Step-down Transformer

# App Functionalities

Connect via Bluetooth
Send commands:
S → Start operation
E → Stop operation
R → Reset values
Live updates on sowing progress and obstacle alerts

# How It Works

User sends Start command using the mobile app.
Machine moves forward and begins seed dispensing.
Ultrasonic sensor detects obstacles (within 50 cm).
Machine stops, closes seed hole, and triggers buzzer.
Resumes automatically once the obstacle clears.
End command stops operation completely.

# Performance

Obstacle detection accuracy: 98%
Seed wastage reduction: 40%
Continuous runtime: ~2 hours
Stable Bluetooth range: 10 meters

# Impact

Reduces manual labor
Increases sowing accuracy
Enhances productivity
Supports sustainable farming

# Future Enhancements

AI-based autonomous navigation
GPS-guided path optimization
Solar-powered operation
Cloud-based monitoring
