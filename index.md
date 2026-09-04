---
layout: default
title: Due Something
description: Pokes to Remind — For Tasks You Can't Forget
---

# Support

### Need help with Due Something? You're in the right place.

## Frequently Asked Questions

### Why am I not getting notifications?

- Go to **Settings → Due Something → Notifications** and make sure notifications are allowed.
- A task needs a due date to alert. Tasks with a date but no time alert at your **Default Due Time** (set in the app's Settings — 8:00 AM unless you've changed it).
- Focus modes can silence alerts. By default Due Something's alerts are time-sensitive and break through Focus — you can restrict that to only **Emergent** tasks in the app's Settings.
- iOS limits how many alerts an app can schedule ahead, so opening the app now and then keeps the queue topped up. Due Something also refreshes in the background when iOS allows it.
- If a task is waiting for a place (see *Can I snooze a task until I get somewhere?*), its alerts are paused until you get there or its safety net runs out.

### Why do I keep getting alerts for the same task?

That's Due Something doing its job — overdue tasks are re-notified until you complete them, so nothing slips through. You're in control of how persistent it is:

- Change the resend interval, or turn off **Resend Indefinitely** and set a limit, in the app's **Settings → Notifications**.
- Give an individual task its own schedule with **Custom Snooze** in the task editor.
- Use a snooze option on the alert to quiet a task for a while, or **Mark as Completed** to finish it.
- Set **Quiet Hours** in **Settings → Notifications** to hold alerts overnight; anything due during the window is delivered once when it ends.

### Can I snooze a task until I get somewhere?

Yes. On an overdue task, open the snooze menu and choose **Snooze Location**, then **Until I Arrive** or **Until I Leave**, and pick a saved place. The task moves to a **Waiting for Location** section in Scheduled and stays quiet until you get there, then becomes due right away.

- Set up your places in **Settings → Location-Based**.
- Allow Location access — **Always** is best so it works in the background. If Location access is turned off, Due Something tells you when you try to snooze to a place.
- If you choose **Until I Arrive** for a place you're already at, the task wakes within a few seconds.
- The **Safety Net** in the same screen re-notifies you after a set time (one hour unless you change it) if you haven't reached the place, so nothing waits forever.
- To cancel a wait, tap the location icon on the task and choose **Stop Waiting**. Snoozing the task any other way also ends the wait.

### Can I snooze until a place from a notification?

Yes. In **Settings → Location-Based**, turn on **Show in Notifications** and choose one place and direction. That option then appears on every reminder notification and the Lock Screen, above Mark as Completed.

### Why isn't my location reminder triggering?

Location reminders rely on Apple's Core Location services, which need permission to work reliably:

- Go to **Settings → Privacy & Security → Location Services → Due Something** and make sure it's set to **Always** (not "While Using") if you want reminders to trigger while the app is in the background.
- Make sure Location Services are turned on system-wide (**Settings → Privacy & Security → Location Services**).
- Arrival/departure alerts can take a minute or two to trigger due to how iOS manages background location — this is expected behavior, not a bug.
- The same applies to tasks snoozed until a place.

### What is the Daily Digest?

One notification each morning at your Default Due Time listing the tasks due that day and how many are overdue. It's skipped on days when nothing is due or overdue. Turn it off in **Settings → Default Due Time → Daily Digest**.

### Voice dictation isn't working

Voice dictation uses Apple's Speech Recognition, which needs both microphone and speech recognition permissions:

- Go to **Settings → Due Something** and confirm both **Microphone** and **Speech Recognition** are enabled.
- Speech Recognition also requires an internet connection on some devices, depending on your settings.

### How do I attach a photo or document to a task?

Tap the paperclip next to the Notes field in the task editor — you can take a photo, scan a document, pick from your photo library, choose a file, or make a drawing. Taking photos or scanning needs camera permission (**Settings → Due Something → Camera**). Picking from your library uses Apple's photo picker, which only shares the photos you select — Due Something never sees your library. Files up to 25 MB can be attached. Tap an attachment to view it full-screen or mark it up.

### Do attachments sync between my devices?

Not yet. Photos, scans, drawings, and files you attach to a task are stored on the device where you added them. Your tasks themselves sync through Apple Reminders as usual, but an attachment added on your iPhone won't appear on your iPad or Mac, and vice versa. Cross-device attachment syncing is planned for a future update.

### Can I add attachments on my Mac?

Yes. In the task editor, tap the paperclip next to Notes to add a photo from your library or choose a file. Take Photo, Scan Document, and Drawing are available on iPhone and iPad only. On the Mac, clicking an attachment opens it in its default app, such as Preview.

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

### What is the Due Something Report?

A snapshot of how you're doing: what's open and overdue, what you completed recently, your streak, and how you snooze. It's computed on the spot from your own data and nothing is stored or sent anywhere. Find it in **Settings → Due Something Report**.

### Does Due Something require an account?

No. Due Something doesn't use accounts, logins, or developer-operated servers. Everything runs through Apple's own frameworks (Reminders, iCloud, Location, Speech Recognition) directly on your device.

### How do I use the widget?

Long-press your Home Screen, tap **＋**, and search for Due Something. Long-press the widget and choose **Edit Widget** to pick which list it shows. Tapping a task's circle completes it right from the widget; the **＋** in the widget's corner starts a new task. One note: when you complete a repeating task from the widget, its next occurrence appears the next time you open the app.

### Can I snooze from the widget?

Yes. Overdue tasks in the Home Screen widget show a snooze button. It pushes the task back by the duration in **Settings → Widgets & Live Activities → Snooze Duration** (10 minutes unless you change it).

### How do I put Due Something on my Lock Screen?

Long-press the Lock Screen, tap **Customize**, tap the widget area, and choose Due Something. There are three sizes: a circle showing your overdue count, a rectangle showing your next tasks, and a single line above the clock. Each can be set to any list.

### What is the overdue Live Activity?

When something is overdue, your oldest overdue task appears on the Lock Screen and in the Dynamic Island with a count of how many more are overdue, plus Snooze and Complete buttons. It starts the next time you open the app while something is overdue, and ends when nothing is. Turn it off in **Settings → Widgets & Live Activities → Allow Live Activities**, or for all apps in the Settings app. Live Activities end on their own after eight hours; opening the app starts a fresh one.

### Can I add a task from Control Center?

Yes. Open Control Center, tap **＋** in the top corner, tap **Add a Control**, and search for Due Something. The button opens the app straight to a new task. It also works as a Lock Screen button and with the Action button.

### Can I find tasks with Spotlight?

Yes. Your open tasks appear in iPhone and Mac search. Tapping a result opens it in Due Something. The index lives only on your device.

### Can I add tasks from other apps?

Yes — share a webpage, selected text, a photo, or a file from any app and choose **Due Something** in the share sheet. The page's title becomes the task title, the link is saved in the notes, a shared photo or file becomes an attachment, and any date in shared text is picked up automatically.

### Does Due Something work with Siri and Shortcuts?

Yes. Try "Add a task to Due Something" or "What's overdue in Due Something" — phrases need to include the app's name. You can also snooze by voice: "Snooze my overdue tasks in Due Something for 30 minutes", "Snooze everything in Due Something", or "Snooze a task in Due Something", which asks you which task and how long. The Shortcuts app has the full set of actions (add, search, snooze, batch snooze, and more) for building your own automations.

### Does Due Something have keyboard shortcuts?

On the Mac, and on iPad with a keyboard: **⌘N** new task, **⌘⇧N** new list, **⌘F** search, **⌘1** Overview and **⌘2** through **⌘5** the smart lists, **⌘⇧K** complete the selected tasks, and **⌘⌫** delete them. In the task editor, **⌘↩** saves and **Esc** cancels.

### Does Due Something work with VoiceOver and other accessibility features?

Yes. Every control is labeled for VoiceOver, undo toasts are announced and stay until you act on them, and the app follows Larger Text, Reduce Motion, Increase Contrast, and Differentiate Without Color. One note: search is normally opened by pulling down on a list and holding. When VoiceOver, Switch Control, or AssistiveTouch is on, a search button appears in the toolbar instead. With Voice Control, use Siri or a keyboard to search.

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
