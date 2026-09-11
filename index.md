---
layout: default
title: Due Something
description: Pokes to Remind — For Tasks You Can't Forget
---

# Support

### Need help with Due Something? You're in the right place.

## Frequently Asked Questions

### Why am I not getting notifications?

* Go to **Settings → Due Something → Notifications** and make sure notifications are allowed.
* A task needs a due date to alert. Tasks with a date but no time alert at your **Default Due Time** (set in the app's Settings — 8:00 AM unless you've changed it).
* Focus modes can silence alerts. By default Due Something's alerts are time-sensitive and break through Focus — you can restrict that to only **Emergent** tasks in the app's Settings.
* iOS limits how many alerts an app can schedule ahead, so opening the app now and then keeps the queue topped up. Due Something also refreshes in the background when iOS allows it.
* If a task is waiting for a place (see _Can I snooze a task until I get somewhere?_), its alerts are paused until you get there or its safety net runs out.

### Why do I keep getting alerts for the same task?

That's Due Something doing its job — overdue tasks are re-notified until you complete them, so nothing slips through. You're in control of how persistent it is:

* Change the resend interval, or turn off **Resend Indefinitely** and set a limit, in the app's **Settings → Notifications**.
* Give an individual task its own schedule with **Custom Snooze** in the task editor.
* Use a snooze option on the alert to quiet a task for a while, or **Mark as Completed** to finish it.
* Set **Quiet Hours** in **Settings → Notifications** to hold alerts overnight; anything due during the window is delivered once when it ends. If you use **Stagger Notifications**, those catch-up alerts arrive a few minutes apart instead of all at once.

### What does Emergent mean?

It's a step above flagged, for the few things that genuinely can't wait. Turn it on in the task editor — it's offered once a task has a due date — and the task shows a red exclamation mark in its row.

* Emergent tasks break through **Quiet Hours**, so they still alert while everything else is held.
* If you've set alerts to break through Focus for **Emergent Only** rather than every task, these are the ones that get through.
* You can toggle Emergent on several tasks at once from Scheduled — see _Can I change several tasks at once?_
* Emergent marks sync to your other devices.

### Can I snooze a task until I get somewhere?

Yes. On an overdue task, open the snooze menu and choose **Snooze Location**, then **Until I Arrive** or **Until I Leave**, and pick a saved place. The task moves to a **Waiting for Location** section in Scheduled and stays quiet until you get there, then becomes due right away.

* Set up your places in **Settings → Location-Based**. Your saved places sync to your other devices.
* Allow Location access — **Always** is best so it works in the background. If Location access is turned off, Due Something tells you when you try to snooze to a place.
* If you choose **Until I Arrive** for a place you're already at, the task wakes within a few seconds.
* The **Safety Net** in the same screen re-notifies you after a set time (one hour unless you change it) if you haven't reached the place, so nothing waits forever.
* To cancel a wait, tap the location icon on the task and choose **Stop Waiting**. Snoozing the task any other way also ends the wait.

### Can I snooze until a place from a notification?

Yes. In **Settings → Location-Based**, turn on **Show in Notifications** and choose one place and direction. That option then appears on every reminder notification and the Lock Screen, above Mark as Completed.

### Why isn't my location reminder triggering?

Location reminders rely on Apple's Core Location services, which need permission to work reliably:

* Go to **Settings → Privacy & Security → Location Services → Due Something** and make sure it's set to **Always** (not "While Using") if you want reminders to trigger while the app is in the background.
* Make sure Location Services are turned on system-wide (**Settings → Privacy & Security → Location Services**).
* Arrival/departure alerts can take a minute or two to trigger due to how iOS manages background location — this is expected behavior, not a bug.
* The same applies to tasks snoozed until a place.

### Does a location alert change when a task is due?

Yes. A task with a location alert comes due at its due date **or** when you reach the place, whichever happens first. Arriving early makes it due there and then; if you never go, the original due date still stands. Nothing is lost either way.

This is different from **Snooze Location** above, where a task has no due moment at all until the place — or its safety net — wakes it.

### What is the Daily Briefing?

One notification each morning at your Default Due Time listing the tasks due that day and how many are overdue. It's skipped on days when nothing is due or overdue. Turn it off in **Settings → Default Due Time → Daily Briefing**.

### Where does tapping a notification take me?

To **Scheduled**, with the task near the top. Tapping the body of an alert never completes or changes anything — use the notification's own buttons to snooze or complete.

### What does the number on the app icon count?

Your choice, in **Settings → Appearance → Icon Badge**:

* **Overdue** — tasks whose time has passed. This is the default.
* **Due Today** — everything due today, whether or not its time has come.
* **All Scheduled** — every task with a due date, however far off.

All three rise and fall as you add and complete tasks. A task waiting on a place isn't counted by any of them, because it has no due moment until the place wakes it.

### Voice dictation isn't working

Voice dictation uses Apple's Speech Recognition, which needs both microphone and speech recognition permissions:

* Go to **Settings → Due Something** and confirm both **Microphone** and **Speech Recognition** are enabled.
* Speech Recognition also requires an internet connection on some devices, depending on your settings.

### How do I attach a photo or document to a task?

Tap the paperclip next to the Notes field in the task editor — you can take a photo, scan a document, pick from your photo library, choose a file, or make a drawing. Taking photos or scanning needs camera permission (**Settings → Due Something → Camera**). Picking from your library uses Apple's photo picker, which only shares the photos you select — Due Something never sees your library. Files up to 25 MB can be attached. Tap an attachment to view it full-screen or mark it up. A task with attachments shows a small paperclip in its row, with a count when there's more than one.

### Do attachments sync between my devices?

Yes. Photos, scans, drawings, and files you attach on one device appear on your others through your iCloud account. Until a file has finished downloading, the attachment shows a cloud icon and "Waiting for iCloud" — tap it to try again if it's taking a while. Attachments count toward your iCloud storage; if it's full, new attachments stay on the device where you added them until space is freed, and Due Something tells you once.

### Can I add attachments on my Mac?

Yes. In the task editor, tap the paperclip next to Notes to add a photo from your library or choose a file. Take Photo, Scan Document, and Drawing are available on iPhone and iPad only. On the Mac, clicking an attachment opens it in its default app, such as Preview.

### Can I change several tasks at once?

Yes. Open the options menu (the **…** button) in a list, in Scheduled, or in Completed, and choose **Select**. Tap the tasks you want and a bar appears at the bottom with what you can do to them:

* **In a list** — flag, move to another list, complete, or delete.
* **In Scheduled** — snooze (including presets and location), mark Emergent, complete, or delete.
* **In Completed** — restore or delete.

Tap the **✕** on that bar to finish. On iPad and Mac, the sidebar button in the top corner turns into an **✕** while you're selecting, which does the same. With a keyboard, **⌘⇧K** completes the selection and **⌘⌫** deletes it. Deletions can be undone from the toast that follows.

### Can I turn my calendar events into tasks?

Yes. Go to **Settings → Calendar Connect → Import Events**, pick a calendar, tick the events you want, choose which list they go to, and tap **Add**. Nothing is imported automatically, and your calendar is never changed — importing only ever creates tasks.

### Which calendars can I import from?

**Settings → Calendar Connect → My Calendars** lists every calendar on the device with a switch. Switch one off and it stays off the import screen. This choice is per-device, because calendars aren't identified the same way across devices.

### Why does Due Something ask for Calendar access?

Only for Calendar Connect — reading events so you can import them, and writing an event when you use **Add to Calendar** on a task. Decline it and everything else in the app works exactly as before.

### How far ahead do the events go?

Six months by default. Change it under **Import Options → Look Ahead**, anywhere from one month to a year. Events that have already passed are never offered.

### A repeating event became a repeating task. Can I get just one date?

**Copy Repeat Rule** (in Import Options, on by default) gives a repeating event a repeating task. To take a single date instead, tap the event to expand it and pick the occurrence you want. If an event repeats in a way the app can't express, importing it makes a one-off task rather than a wrong repeat.

### An event I imported isn't in the list any more

**Hide Imported** (in Import Options, on by default) leaves out events you've already imported, so the list stays useful on your next visit. Switch it off to see them again, marked as imported.

### Can an imported task come due before the event starts?

Turn on **Notify Earlier** in Import Options, then set **Move Up Due Time By** — anything from 1 minute to 60 hours. The task falls due that far ahead of the event, so there's time to act on it. Your calendar isn't touched.

* A repeating event carries the same head start into every occurrence.
* All-day events are left alone. They have no time of day to bring forward, so their tasks fall due at your Default Due Time as usual.

### How do I know which calendar a task came from?

An imported task's notes end with a line naming it — _Imported from the "Work" calendar_ — underneath the event's own location and notes.

### Can I put a task on my calendar?

Yes. **Add to Calendar** in the task editor writes the task out as a calendar event, repeats included. **Settings → Calendar Connect → Default Event Duration** sets how long that event runs when the task has no end time. A task with no time of day becomes an all-day event.

### Reminders aren't syncing across my devices

Due Something reads and writes directly to Apple's Reminders app, so your tasks and lists sync through Apple's iCloud.

* Make sure iCloud is signed in on all your devices (**Settings → \[Your Name\] → iCloud**).
* Confirm **Reminders** is toggled on under iCloud settings on each device.
* Give it a few minutes — iCloud sync isn't always instant.

Everything Due Something adds on top of Reminders — flags, attachments, snooze settings, list icons, and more — syncs separately; see _What does iCloud Sync keep in step?_ below.

### What does iCloud Sync keep in step?

Your tasks and lists already sync through Apple Reminders. Due Something's own extras sync through your iCloud account as well, on every device signed in to the same Apple Account:

* Flags, Emergent marks, and muted alerts
* Custom Snooze settings, snooze history, and location alerts on individual tasks
* Attachments
* List icons, hidden lists, sort order, list order, and manual task order
* Recently Deleted, so you can restore a task from any device
* Saved places for Snooze Location
* Which calendar events you've already imported
* Your Settings, section by section (see the next question)

It's on automatically when you're signed in to iCloud. Changes usually arrive on your other devices within a few seconds while they're awake, or the next time they open. Everything is stored in your private iCloud account and end-to-end encrypted — we have no access to it.

### Can I choose what syncs?

Yes. Go to **Settings → iCloud Sync**.

* **Sync this Device with iCloud** turns syncing on or off for the device you're holding. When it's off, that device keeps everything it has and stops sending or receiving changes; turn it back on to catch up.
* The switches below it choose which sections of Settings are kept the same on all your devices: Default View, Default List, Default Due Time, Notifications, Snooze Options, Widgets & Live Activities, Calendar Connect, Appearance, and Sounds & Haptics. Widgets & Live Activities and Sounds & Haptics start off, since they're about how one device shows and plays things. Turn a section off to let each device keep its own settings for it; turn it back on to share the settings of the device you turn it on from. These choices apply to all your devices.
* **Restore iCloud Sync Defaults** puts just these switches back to their defaults. It doesn't change your settings themselves.

You can also switch Due Something off entirely under **Settings → \[Your Name\] → iCloud → Saved to iCloud** on iPhone and iPad, or **System Settings → \[Your Name\] → iCloud → Saved to iCloud** on the Mac. The app keeps working from its local data.

### A list shared with me is marked view only

If someone shares a list with you as view only, Due Something shows its tasks with a lock next to the list name, and leaves the list out of the choices for new tasks. You can still change its tasks on your device, but those changes stay there — iCloud won't accept them for a list you can't edit — so the app warns you the first time. Ask the list's owner for edit access if you need to make changes that everyone sees.

### My list settings reset after I renamed a list

Due Something keeps a list's icon, sort, and visibility with the list by its name, and carries them over when you rename it — in Due Something, in Reminders, or on another device. The one case it can't tell apart is two lists with the same name in the same account; the second one keeps its settings on each device separately. Give them different names to sync both.

### What is the Shelf?

The group at the very top of the sidebar, holding Scheduled to begin with. Put the lists and smart lists you use constantly on it and they stay above everything else.

* On iPhone and iPad, drag a row across the Shelf's line to move it on or off.
* On the Mac, right-click a row and choose **Move to The Shelf** or **Remove from The Shelf**.

### How do I reorder my lists?

On iPhone, open the sidebar's options menu and choose **Reorder Lists**. On iPad, press and hold any row and drag it. Rows can go anywhere — smart lists and your own lists can be mixed in whatever order suits you. The gap partway down the sidebar marks where your own lists begin; drag a row above or below it to move it between the two groups.

### How do I make a new list on iPad?

Pull down at the top of the sidebar and hold. A **＋** fills in, and letting go opens the new-list sheet. On iPhone, use **New List** in the sidebar's options menu; on the Mac, the **＋** next to "My Lists".

If you use VoiceOver or Switch Control, a **＋** button appears at the top of the iPad sidebar instead, since pull-and-hold is a timed gesture.

### Can I hide a list's name at the top of the screen?

Yes — **Hide Header Name** in any list's options menu, including Scheduled and Recently Deleted. The list still works exactly the same; only the large title is hidden.

### Why does the app ask for Contacts access?

This is entirely optional. It's only used to make it faster to set a location reminder from a contact's saved address. If you don't use that feature, you can leave Contacts access off and everything else in the app will work normally.

### I deleted a reminder by accident

Open Due Something and check the **Recently Deleted** list — deleted reminders are kept there for 30 days before being permanently removed, so you should be able to restore it. Recently Deleted syncs, so a task deleted on your iPhone can be restored from your Mac, and restoring or permanently deleting it on one device removes it from the list on the others.

### How do snooze suggestions work?

**Settings → Snooze Options → Active Snooze Mechanism** decides what you're offered when you snooze:

* **Static** — the same intervals every time, set by you.
* **Adaptive** — Short, Medium and Long buckets whose durations drift toward what you actually pick.

Adaptive learns from your own past snooze choices using a small model that runs on your device. The history it learns from — when you snoozed and for how long — syncs between your devices through your iCloud account, end-to-end encrypted, so suggestions are the same everywhere. Nothing is sent to us. Turn it off or clear the history in **Settings → Snooze Options**.

Two more options sit alongside them in the same section: **Smart Presets** (Later Today, This Evening, Tomorrow Morning, This Weekend, Next Week) and **Location-Based**.

### What is the Due Something Report?

A snapshot of how you're doing: what's open and overdue, what you completed recently, your streak, and how you snooze. It's computed on the spot from your own data and nothing is stored or sent anywhere. Find it in **Settings → Due Something Report**.

### Does Due Something require an account?

No. Due Something doesn't use accounts, logins, or developer-operated servers. Everything runs through Apple's own frameworks (Reminders, iCloud, Calendar, Location, Speech Recognition) directly on your device and in your own iCloud account.

### How do I use the widget?

Long-press your Home Screen, tap **＋**, and search for Due Something. Long-press the widget and choose **Edit Widget** to pick which list it shows. Tapping a task's circle completes it right from the widget; the **＋** in the widget's corner starts a new task. One note: when you complete a repeating task from the widget, its next occurrence appears the next time you open the app.

### Can I snooze from the widget?

Yes. Overdue tasks in the Home Screen widget show a snooze button. It pushes the task back by the duration in **Settings → Widgets & Live Activities → Snooze Duration** (10 minutes unless you change it).

### How do I put Due Something on my Lock Screen?

Long-press the Lock Screen, tap **Customize**, tap the widget area, and choose Due Something. There are three sizes: a circle showing your overdue count, a rectangle showing your next tasks, and a single line above the clock. Each can be set to any list.

### What is the overdue Live Activity?

When something is overdue, your oldest overdue task can appear on the Lock Screen and in the Dynamic Island with a count of how many more are overdue, plus Snooze and Complete buttons. It's off until you turn it on in **Settings → Widgets & Live Activities → Allow Live Activities**. Once on, it starts the next time you open the app while something is overdue, and ends when nothing is. Live Activities end on their own after eight hours; opening the app starts a fresh one.

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

Yes. Every control is labeled for VoiceOver, undo toasts are announced and stay until you act on them, and the app follows Larger Text, Reduce Motion, Increase Contrast, and Differentiate Without Color.

Two notes about gestures that are held rather than tapped. Search is normally opened by pulling down on a list and holding; when VoiceOver, Switch Control, or AssistiveTouch is on, a search button appears in the toolbar instead. The same applies to making a list on iPad — a **＋** button appears at the top of the sidebar in place of the pull-and-hold. With Voice Control, use Siri or a keyboard to search.

### I left a tip but something went wrong

Thank you! Tips are one-time purchases handled entirely by Apple's App Store — Due Something never sees your payment details. If a purchase fails or the Tip Jar shows tips as unavailable, check that you're signed in to the App Store and that in-app purchases aren't restricted in Screen Time. If Apple charged you and something still looks wrong, email us and we'll sort it out.

## Still Need Help?

If your question isn't answered above, reach out and we'll get back to you:

📧 [duesomethingapp@gmail.com](mailto:duesomethingapp@gmail.com)

When reporting an issue, it helps to include:

* Your device model and iOS version
* What you expected to happen vs. what actually happened
* Steps to reproduce the issue, if possible

## Privacy

Curious about what data Due Something accesses and how it's handled? See our [Privacy Policy](https://duesomethingapp.github.io/privacypolicy/).
