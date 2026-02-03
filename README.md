# NanoBot
🤖 NanoBot – Interactive Emotion-Based Smart Robot (ESP32-C3)

NanoBot is an interactive, emotion-driven smart robot built on the ESP32-C3 Super Mini, designed to behave like a tiny digital companion. It reacts to touch, motion, time, and weather, displaying expressive animated eyes and facial emotions on an OLED screen while producing sound effects for feedback.

This project blends embedded systems, sensor fusion, UI animation, and IoT to create a playful yet technically rich robotic system.

✨ Key Features 😊 Emotion & Personality Engine

NanoBot supports 15+ animated moods, including:

Happy, Sad, Angry, Love, Sleepy, Tired

Fear, Dizzy, Shake, Confused, Cringe

Excited, Playful, Surprised, Annoyed

Each mood has:

Custom eye animation

Dynamic mouth expression

Matching sound effects

Automatic timeout and recovery to neutral/happy state

👆 Dual Touch Interaction

Left Touch Sensor

Tap gestures to view time, weather, system stats

Multi-tap to trigger special emotions (love, excited, playful, surprised)

Right Touch Sensor

Direct emotion control (sad, angry, annoyed, confused, tired)

Both Touches Together

Opens Sensor Debug Screen

🌀 Motion & Shake Detection (MPU6050)

Using the MPU6050 accelerometer & gyroscope, NanoBot reacts to physical movement:

🤯 Shake detection → Dizzy / Shake mood

😱 Sudden movement / fall → Fear reaction

🎮 Gentle motion → Playful behavior

Real-time motion magnitude is monitored and filtered for stability.

⏰ Live Time & Date (NTP)

Automatic time synchronization using NTP

Displays:

12-hour time (AM/PM)

Day of the week

Full date

Accessed via touch gesture

🌦️ Real-Time Weather (No API Key)

Uses Open-Meteo API

Displays:

Weather icon (sunny, cloudy, rainy, foggy, snowy, storm)

Temperature

Humidity

Location preset for Visakhapatnam

Auto refresh every few minutes

🖥️ Multiple Interactive Screens

NanoBot dynamically switches between:

Face Screen – Emotion display (default)

Time Screen – Clock & calendar

Weather Screen – Current weather

System Stats Screen

Wi-Fi status

Signal strength

Uptime

Sensor status

Sensor Debug Screen

Gyroscope magnitude

Accelerometer magnitude

Motion thresholds

🔊 Sound Feedback System

Uses a buzzer to generate expressive sound patterns:

Greeting sounds

Emotion-specific tones (scared, sleepy, excited, angry, love, etc.)

Touch and interaction feedback

💤 Smart Idle Behavior

Automatically enters sleepy mood after long inactivity

Gradually returns to happy state after intense emotions

Prevents mood locking or repetitive animations
