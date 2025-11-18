# Practical 4  

## 🎯 Aim  

Create an Android Alarm application by using **Service** & **BroadcastReceiver**.

---

## 📖 Description  

This practical demonstrates how to create a fully functional **Alarm Application** in Android using:

- **BroadcastReceiver** → Receives the alarm trigger  
- **Service** → Plays ringtone using MediaPlayer  
- **AlarmManager** → Schedules exact alarms  
- **PendingIntent** → Sends alarm trigger  
- **TimePickerDialog** → Allows user to select alarm time  
- **Calendar Class** → Handles time conversion  
- **SimpleDateFormat** → Displays selected alarm time  
- **MaterialCardView** → UI layout component for better design  

The application provides the following features:  

1. Select a time using the TimePicker.  
2. Set Exact Alarm using AlarmManager.  
3. Alarm triggers using BroadcastReceiver.  
4. Alarm sound plays using Service.  
5. Cancel or Stop Alarm anytime.  

---

## 📸 Screenshots with Description  

| Screenshot | Description |  
|------------|-------------|  
| <p align="center"><img src="screenshots/mainSc.jpeg" width="250"/></p> | The **Main Screen** displays current time and a button to set the alarm. |
| <p align="center"><img src="screenshots/Alarmset.jpeg" width="250"/></p> | After selecting the time, a **Toast** appears and the **Cancel Alarm** button becomes visible. |
| <p align="center"><img src="screenshots/notification .jpeg" width="250"/></p> | When the alarm triggers, **BroadcastReceiver** activates and **AlarmService** plays sound. |
| <p align="center"><img src="screenshots/alarmstop.jpeg" width="250"/></p> | After pressing stop/cancel, the alarm ringtone stops and service terminates. |

---

## 🛠 Components Used  

- **AlarmManager**  
- **PendingIntent**  
- **BroadcastReceiver**  
- **Service (MediaPlayer)**  
- **TimePickerDialog**  
- **Calendar Class**  
- **SimpleDateFormat**  
- **MaterialCardView**  
- **sendBroadcast()**  
- **startService() / stopService()**  
- **getSystemService()**  

---

## 📝 Required Permission  

```xml
<uses-permission android:name="android.permission.SCHEDULE_EXACT_ALARM" />

## 📘 Student Details > **Name:** *Bhavya Patel* > **Enrollment:** *23012021031* > **Batch:** *5IT-B-1*
