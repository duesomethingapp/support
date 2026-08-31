---
layout: default
title: Due Something
description: Pokes to Remind — For Tasks You Can't Forget
---

# Support

**Pokes to Remind — For Tasks You Can't Forget**

Need help with Due Something? You're in the right place.

## Frequently Asked Questions

### Why am I not getting notifications?
- Go to **Settings → Due Something → Notifications** and make sure notifications are allowed.
- A task needs a due date to alert. Tasks with a date but no time alert at your **Default Due Time** (set in the app's Settings — 8:00 AM unless you've changed it).
- Focus modes can silence alerts. By default Due Something's alerts are time-sensitive and break through Focus — you can restrict that to only **Emergent** tasks in the app's Settings.
- iOS limits how many alerts an app can schedule ahead, so opening the app now and then keeps the queue topped up. Due Something also refreshes in the background when iOS allows it.

### Why do I keep getting alerts for the same task?
That's Due Something doing its job — overdue tasks are re-notified until you complete them, so nothing slips through. You're in control of how persistent it is:

- Change the resend interval, or turn off **Resend Indefinitely** and set a limit, in the app's **Settings → Notifications**.
- Give an individual task its own schedule with **Custom Snooze** in the task editor.
- Tap **Cancel** on any alert to stop resends for just that task without completing it.

### Why isn't my location reminder triggering?
Location reminders rely on Apple's Core Location services, which need permission to work reliably:

- Go to **Settings → Privacy & Security → Location Services → Due Something** and make sure it's set to **Always** (not "While Using") if you want reminders to trigger while the app is in the background.
- Make sure Location Services are turned on system-wide (**Settings → Privacy & Security → Location Services**).
- Arrival/departure alerts can take a minute or two to trigger due to how iOS manages background location — this is expected behavior, not a bug.

### Voice dictation isn't working
Voice dictation uses Apple's Speech Recognition, which needs both microphone and speech recognition permissions:

- Go to **Settings → Due Something** and confirm both **Microphone** and **Speech Recognition** are enabled.
- Speech Recognition also requires an internet connection on some devices, depending on your settings.

### How do I attach a photo or document to a task?
Tap the photo icon next to the Notes field in the task editor — you can take a photo, scan a document, or pick from your photo library. Taking photos or scanning needs camera permission (**Settings → Due Something → Camera**). Picking from your library uses Apple's photo picker, which only shares the photos you select — Due Something never sees your library. Tap the thumbnail to view the image full-screen or mark it up.

### Reminders aren't syncing across my devices
Due Something reads and writes directly to Apple's Reminders app, so syncing is handled by Apple's iCloud — not by Due Something.

- Make sure iCloud is signed in on all your devices (**Settings → [Your Name] → iCloud**).
- Confirm **Reminders** is toggled on under iCloud settings on each device.
- Give it a few minutes — iCloud sync isn't always instant.

### Why does the app ask for Contacts access?
This is entirely optional. It's only used to make it faster to set a location reminder from a contact's saved address. If you don't use that feature, you can leave Contacts access off and everything else in the app will work normally.

### I deleted a reminder by accident
Open Due Something and check the **Recently Deleted** list — deleted reminders are kept there for 30 days before being permanently removed, so you should be able to restore it.

### How do snooze suggestions work?
Due Something learns from your own past snooze choices using a small on-device model. Nothing is uploaded — the suggestions are generated and stored entirely on your device.

### Does Due Something require an account?
No. Due Something doesn't use accounts, logins, or developer-operated servers. Everything runs through Apple's own frameworks (Reminders, iCloud, Location, Speech Recognition) directly on your device.

### How do I use the widget?
Long-press your Home Screen, tap **＋**, and search for Due Something. Long-press the widget and choose **Edit Widget** to pick which list it shows. Tapping a task's circle completes it right from the widget; the **＋** in the widget's corner starts a new task. One note: completing a *repeating* task from the widget takes full effect the next time you open the app.

### Can I add tasks from other apps?
Yes — share a webpage or selected text from any app and choose **Due Something** in the share sheet. The page's title becomes the task title, the link is saved in the notes, and any date in shared text is picked up automatically.

### Does Due Something work with Siri and Shortcuts?
Yes. Try "Add a task to Due Something" or "What's overdue in Due Something" — phrases need to include the app's name. The Shortcuts app has the full set of actions (add, search, snooze, batch snooze, and more) for building your own automations.

### I left a tip but something went wrong
Thank you! Tips are one-time purchases handled entirely by Apple's App Store — Due Something never sees your payment details. If a purchase fails or the Tip Jar shows tips as unavailable, check that you're signed in to the App Store and that in-app purchases aren't restricted in Screen Time. If Apple charged you and something still looks wrong, email us and we'll sort it out.

## Still Need Help?

If your question isn't answered above, reach out and we'll get back to you:

📧 [duesomethingapp@gmail.com](mailto:duesomethingapp@gmail.com)

When reporting an issue, it helps to include:
- Your device model and iOS version
- What you expected to happen vs. what actually happened
- Steps to reproduce the issue, if possible

## Privacy

Curious about what data Due Something accesses and how it's handled? See our [Privacy Policy](https://duesomethingapp.github.io/privacypolicy/).
