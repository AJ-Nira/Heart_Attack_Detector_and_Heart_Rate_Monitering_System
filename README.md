# Heart_Attack_Detector_and_Heart_Rate_Monitering_System
This program monitors heart rate and triggers alerts for abnormal readings (e.g., BPM > 120 or &lt; 50). It features a panic button for emergency notifications, a buzzer for audible alerts, and sends Telegram messages with real-time updates. The OLED display shows the current heart rate, average BPM, and alert status.

It uses an infrared sensor (MAX30105) to detect and measure the user's heart rate. It displays the real-time heart rate (BPM) and the average BPM on an OLED screen. If the heart rate falls outside a healthy range (either too high or too low for consecutive readings), the system triggers an alert. 

The alert is accompanied by:
- A buzzer sounding off to indicate an abnormal condition.
- A Telegram message is sent to designated contacts to notify them of the possible heart attack situation.

Additionally, a panic button is provided for the user to manually trigger an emergency alert. This system also connects to Wi-Fi to enable the Telegram bot functionality and ensures remote notifications.

The project combines heart rate monitoring, emergency alert systems, and wireless communication, making it suitable for health monitoring and safety applications.

#Description of Changes:
Wi-Fi Credentials:

The actual Wi-Fi SSID and password values are replaced with placeholder text: "your_SSID" and "your_PASSWORD".
This ensures that sensitive network information is not exposed in the code.
Telegram Bot Token:

The Telegram bot token is replaced with "your_BOT_TOKEN", a placeholder. This token is required for authentication with the Telegram API, but it has been hidden to prevent unauthorized access to the bot.
Telegram Chat IDs:

The chat IDs for Telegram communication are replaced with placeholders: "your_CHAT_ID1" and "your_CHAT_ID2". These are the unique identifiers for the Telegram chats where messages will be sent. By replacing them with placeholders, we avoid sharing personal or private chat information.
