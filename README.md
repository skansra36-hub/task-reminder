# ⏰ Task Reminder with WhatsApp Notifications

A fully frontend-based task reminder application with **desktop notifications** and **WhatsApp messaging**. Works 100% offline with localStorage persistence.

## ✨ Features

### Core Features
- ✅ Create tasks with multiple daily reminders
- ✅ Set repeat daily (continues until marked done)
- ✅ Mark tasks as completed
- ✅ Track overdue and upcoming tasks
- ✅ Live statistics dashboard

### Notification System
- ✅ **Browser Notifications** (Desktop popup alerts)
- ✅ **WhatsApp Messages** (Send reminders to your WhatsApp)
- ✅ **Audio Alerts** (Beep sound notification)
- ✅ **Service Worker** (Works even when browser is closed)
- ✅ **No Spam** (Duplicate prevention per minute)

### Data Management
- ✅ 100% localStorage persistence
- ✅ All data stays on your device
- ✅ Zero backend server needed
- ✅ Works offline completely
- ✅ Handles 500+ tasks efficiently

## 🚀 Quick Start

### 1. Access the App
Open in your browser:
```
https://skansra36-hub.github.io/task-reminder/
```

### 2. Allow Notifications
When prompted, click **"Allow"** for browser notifications.

### 3. Add WhatsApp (Optional)
1. Go to **WhatsApp Setup** section
2. Enter your number: `+[Country Code][Phone Number]`
   - Example: `+12025551234`
3. Click **"Save WhatsApp Number"**

### 4. Create a Task
1. Enter task name
2. Pick a date
3. Set reminder time(s)
4. Choose notifications: ☑️ Browser ☑️ WhatsApp
5. Click **"✓ Create Task"**

## 📱 How WhatsApp Works

### Using Twilio WhatsApp Sandbox (FREE)
1. Go to https://www.twilio.com/console/sms/whatsapp/sandbox
2. Save your WhatsApp number
3. Send "join [sandbox code]" to activate
4. Task reminders will be sent to your WhatsApp

## 🔔 Notification Types

| Type | When | Works Offline |
|------|------|---|
| **Browser Popup** | When reminder time matches | ✅ Yes |
| **WhatsApp** | When reminder time matches | ✅ Yes |
| **Audio Beep** | When reminder time matches | ✅ Yes |
| **Desktop Alert** | When reminder time matches | ✅ Yes |

## 💡 Usage Tips

### Create Reminders
- **Task Name:** "Submit Report"
- **Date:** 2026-02-25
- **Times:** 09:00, 14:00, 17:00
- **Repeat:** ✓ Daily

### Bulk Import
```
Task Name | YYYY-MM-DD | HH:MM
Submit Report | 2026-02-25 | 10:00
Team Meeting | 2026-02-20 | 14:00
```

## 🔧 Technical Details

### Architecture
- **Frontend:** HTML + CSS + JavaScript (single file)
- **Storage:** Browser localStorage
- **Notifications:** Browser Notification API + Service Worker
- **Backend:** None (100% client-side)

## 🌐 Browser Support

| Browser | Desktop | Mobile |
|---------|---------|--------|
| Chrome | ✅ Full | ✅ Full |
| Firefox | ✅ Full | ✅ Full |
| Safari | ✅ Full | ⚠️ Limited |
| Edge | ✅ Full | ✅ Full |

## ⚙️ Troubleshooting

### Notifications Not Showing
1. **Check permission:** Browser Settings → Notifications → Allow
2. **Keep browser open:** First time, keep website open
3. **Check console:** F12 → Console for errors

### WhatsApp Not Working
1. **Check number format:** Must include country code (+)
2. **Verify connection:** Try saving again
3. **Check Twilio:** Confirm WhatsApp number in Twilio console

## 🔐 Privacy & Security

✅ **100% Private** - All data stored locally
✅ **No Tracking** - No analytics
✅ **No Cloud Sync** - Data never sent to servers
✅ **No Logins** - Anonymous
✅ **Open Source** - Transparent code

## 📋 Checklist

- ✅ Create tasks with multiple reminders
- ✅ Set repeat daily reminders
- ✅ Browser notifications
- ✅ WhatsApp message reminders
- ✅ Audio alerts
- ✅ Mark tasks complete
- ✅ Track overdue tasks
- ✅ All data persists
- ✅ Works offline
- ✅ No backend needed

## 🎯 Examples

### Daily Standup
- Name: "Daily Standup"
- Date: 2026-02-20
- Time: 09:00 AM
- Repeat: ✓ Daily
- Notify: ✅ Browser + ✅ WhatsApp

### Project Deadline
- Name: "Submit Final Project"
- Date: 2026-03-01
- Times: 08:00, 12:00, 16:00
- Repeat: No
- Notify: ✅ Browser + ✅ WhatsApp

## 📄 License

MIT License - Feel free to use and modify

---

**Made with ❤️ for deadline-driven teams**

Simple. Free. Powerful. Persistent.
