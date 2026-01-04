# DOSEGUARDIAN-INTELLIGENT-PILL-TAKING-ASSISTANT
DoseGuardian is an intelligent medication reminder and monitoring system designed to assist patients in taking their prescribed medicines on time. Many individuals, especially elderly patients and those under long-term treatment, often forget or skip their medication doses, leading to reduced treatment effectiveness and health complications. 
##🎯 Features
⏰ Real-time clock (RTC) based time tracking
⌨️ Keypad-based menu navigation
🕒 Set and edit:
  Time
  Date
  Day
  ------------------------------------------------

##Medicine reminder time
📟 LCD display for time, date, and alerts
🔔 Buzzer alert for medicine reminder
💡 LED indication if medicine is not taken
✅ Confirmation using push button
-------------------------------------------------
🧰 Hardware Requirements
ARM7 LPC2148 / LPC2138 Microcontroller
16×2 LCD Display
4×4 Matrix Keypad
Buzzer
LED
Push Buttons (Menu / Acknowledge)
Power Supply (5V)
Connecting Wires
---------------------------------------------------
🧪 Software Requirements
Keil μVision IDE
Embedded C
Proteus (optional, for simulation)
--------------------------------------------------------
⚙️ Working Principle
RTC continuously updates current time and date.
LCD displays:
Time (HH:MM:SS)
Date (DD/MM/YYYY)
Day of week
User presses MENU switch to enter settings.
Using keypad, user can:
  Edit RTC time/date
  Set medicine reminder time
When RTC time matches medicine time:
  LCD shows "Take Med"
  Buzzer turns ON
If user confirms by pressing switch:
  LCD shows "Medicine Taken"
If not confirmed within time:
  LED turns ON
  LCD shows "MED not taken"
---------------------------------------------
📋 Menu Options
Main Menu
1 → Edit RTC Information
2 → Edit Medicine Reminder Time
3 → Exit Menu
RTC Edit Menu
Edit Hour, Minute, Second
Edit Day, Date, Month, Year
SET MED TIME Edit Menu
Set Medicine Hour
Set Medicine Minute
Set Medicine Second
-------------------------------------

🧠 Key Concepts Used
ARM7 GPIO Programming
RTC Register Configuration
Matrix Keypad Scanning
LCD Interfacing (8-bit mode)
Real-Time Event Matching
Embedded Menu System
Polling-based Input Handling
-----------------------------------

## Safety & Reliability
Input validation for:
Hour (0–23)
Minute/Second (0–59)
Date (1–31)
Month (1–12)
Prevents invalid RTC configurations
Ensures user acknowledgment for reminders
------------------------------------------------------


## Applications
Medicine reminder for elderly people
Patient care monitoring
Embedded healthcare systems
Smart assistive devices
------------------------------


# Author
Bhanu Prakash 
Embedded Systems & ARM7 Developer
Embedded C, and Microcontroller-based system design
---------------------------

