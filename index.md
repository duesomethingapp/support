---
layout: default
title: Due Something
description: Pokes to Remind — For Tasks You Can't Forget
---

# Support

**Pokes to Remind — For Tasks You Can't Forget**

Need help with Due Something? You're in the right place.

## Frequently Asked Questions

### Why isn't my location reminder triggering?
Location reminders rely on Apple's Core Location services, which need permission to work reliably:

- Go to **Settings → Privacy & Security → Location Services → Due Something** and make sure it's set to **Always** (not "While Using") if you want reminders to trigger while the app is in the background.
- Make sure Location Services are turned on system-wide (**Settings → Privacy & Security → Location Services**).
- Arrival/departure alerts can take a minute or two to trigger due to how iOS manages background location — this is expected behavior, not a bug.

### Voice dictation isn't working
Voice dictation uses Apple's Speech Recognition, which needs both microphone and speech recognition permissions:

- Go to **Settings → Due Something** and confirm both **Microphone** and **Speech Recognition** are enabled.
- Speech Recognition also requires an internet connection on some devices, depending on your settings.

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

## Still Need Help?

If your question isn't answered above, reach out and we'll get back to you:

📧 [duesomethingapp@gmail.com](mailto:duesomethingapp@gmail.com)

When reporting an issue, it helps to include:
- Your device model and iOS version
- What you expected to happen vs. what actually happened
- Steps to reproduce the issue, if possible

## Privacy

Curious about what data Due Something accesses and how it's handled? See our [Privacy Policy](https://duesomethingapp.github.io/privacypolicy/).
