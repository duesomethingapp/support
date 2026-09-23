---
layout: default
title: Due Something
description: Pokes to Remind — For Tasks You Can't Forget
---

# Support

### Need help with Due Something? You're in the right place.

## Frequently Asked Questions

### Why am I not getting notifications?

- Start at **Settings → Notifications → Notification Status** in the app. It tells you what's scheduled and, if the system won't show Due Something's alerts, exactly what's stopping them — with a button that takes you to the setting that fixes it. A warning triangle appears on the row when that's the case, so you don't have to go looking. See _How do I check my notifications are working?_
- Or go to **Settings → Due Something → Notifications** on your device and make sure notifications are allowed.
- A task needs a due date to alert. Tasks with a date but no time alert at your **Default Due Time** (set in the app's Settings — 8:00 AM unless you've changed it).
- Focus modes can silence alerts. By default Due Something's alerts are time-sensitive and break through Focus — you can restrict that to only **Emergent** tasks in the app's Settings.
- iOS limits how many alerts an app can schedule ahead, so opening the app now and then keeps the queue topped up. Due Something also refreshes in the background when iOS allows it — if **Background App Refresh** is switched off for Due Something, or Low Power Mode is on, the alerts already scheduled still arrive but no new ones are added until you open the app. Notification Status tells you when that's what's happening.
- If a task is waiting for a place (see _Can I snooze a task until I get somewhere?_), its alerts are paused until you get there or its safety net runs out.
- If you set **Create Alarm** on a task, that's a separate thing from its notifications and needs its own permission — see _My alarm didn't go off_.

### Why do I keep getting alerts for the same task?

That's Due Something doing its job — overdue tasks are re-notified until you complete them, so nothing slips through. You're in control of how persistent it is:

- Change the resend interval, or turn off **Resend Indefinitely** and set a limit, in the app's **Settings → Notifications**.
- Give an individual task its own schedule with **Custom Snooze** in the task editor.
- Use a snooze option on the alert to quiet a task for a while, or **Mark as Completed** to finish it.
- To keep nights quiet, use a Focus or Scheduled Summary in iOS **Settings → Notifications**; Due Something's alerts respect them like any other app's.

### What does Emergent mean?

It's a step above flagged, for the few things that genuinely can't wait. Turn it on in the task editor — it's offered once a task has a due date — and the task shows a red exclamation mark in its row.

- If you've set alerts to break through Focus for **Emergent Only** rather than every task, these are the ones that get through.
- You can toggle Emergent on several tasks at once from Scheduled — see _Can I change several tasks at once?_
- Emergent marks sync to your other devices.

### What is Create Alarm?

A real alarm — the kind that rings through Silent mode and Focus, with the system alarm sound and a Stop button — for the few tasks a notification isn't enough for.

It's in the task editor, just below **Emergent**, and appears only when a task has a **Date**, a **Time**, and **Emergent** all turned on. Those three together are what makes an alarm appropriate, so it can't be set by accident.

- The alarm rings at the task's due time, including any snooze you've applied.
- **Stopping the alarm doesn't complete the task.** It still appears in your lists and still gets its normal reminders.
- A repeating task gets an alarm for its current occurrence; completing it moves the alarm on to the next one.
- The first time you turn it on, iOS asks for permission to set alarms. This is separate from notification permission.
- Your ordinary Due Something notifications carry on as well — an alarm is added to them, not a replacement for them.

Alarms are on iPhone and iPad. Your choice is remembered on the Mac and syncs, but macOS has no alarm to set.

### My alarm didn't go off

- Check that the task still has **Date**, **Time**, and **Emergent** on. Turning any of them off clears the alarm.
- Check alarm permission in **Settings → Due Something**. Each device asks separately, so allowing it on your iPhone doesn't cover your iPad.
- An alarm has to be in the future. Setting one for a time that has already passed won't ring.
- If the task saved but the alarm couldn't be set, Due Something says so at the time rather than failing quietly.

### Can I snooze a task until I get somewhere?

Yes. On an overdue task, open the snooze menu and choose **Snooze Location**, then **Until I Arrive** or **Until I Leave**, and pick a saved place. The task moves to a **Waiting for Location** section in Scheduled and stays quiet until you get there, then becomes due right away.

- Set up your places in **Settings → Snooze → More Options → Location-Based**. Your saved places sync to your other devices.
- Allow Location access — **Always** is best so it works in the background. If Location access is turned off, Due Something tells you when you try to snooze to a place.
- If you choose **Until I Arrive** for a place you're already at, the task wakes within a few seconds.
- The **Safety Net** in the same screen re-notifies you after a set time (one hour unless you change it) if you haven't reached the place, so nothing waits forever.
- To cancel a wait, tap the location icon on the task and choose **Stop Waiting**. Snoozing the task any other way also ends the wait.

### Can I snooze until a place from a notification?

Yes. In **Settings → Snooze → More Options → Location-Based**, turn on **Show in Notifications** and choose one place and direction. That option then appears on every reminder notification and the Lock Screen, above Mark as Completed.

### Can I snooze a task to a specific date or time?

Yes. Open the snooze menu and choose **New Date/Time**, below Location. Set a date, a time, or both:

- **A date only** — the task moves to that day and keeps its own time of day.
- **A time only** — the task stays on its own day and moves to that hour.
- **Both** — the task moves to exactly that moment.

It works on a selection too: select tasks in Scheduled, tap the alarm icon, and choose New Date/Time. Leaving one half out is what makes this useful in bulk — pick a time only, and ten tasks spread across the week each move to that hour on their own day.

A task with a date but no time stays that way when you move it to another date; choosing a time is what gives it one. Turn the option off under **Settings → Snooze → More Options → Snooze to Date/Time**.

### Why isn't my location reminder triggering?

Location reminders rely on Apple's Core Location services, which need permission to work reliably:

- Go to **Settings → Privacy & Security → Location Services → Due Something** and make sure it's set to **Always** (not "While Using") if you want reminders to trigger while the app is in the background.
- Make sure Location Services are turned on system-wide (**Settings → Privacy & Security → Location Services**).
- Arrival/departure alerts can take a minute or two to trigger due to how iOS manages background location — this is expected behavior, not a bug.
- The same applies to tasks snoozed until a place.

### Does a location alert change when a task is due?

Yes. A task with a location alert comes due at its due date **or** when you reach the place, whichever happens first. Arriving early makes it due there and then; if you never go, the original due date still stands. Nothing is lost either way.

This is different from **Snooze Location** above, where a task has no due moment at all until the place — or its safety net — wakes it.

### How do I check my notifications are working?

**Settings → Notifications → Notification Status** answers it in one place. It reads what's actually set up on your device rather than what the app intended, so what you see is what will happen:

- **Next Alert** — when the next one is due, and which task it's for.
- **Alerts Queued** — how many are set up out of the number iOS allows an app to hold at once.
- **Tasks Covered** — how many of your dated tasks have an alert waiting. If it's fewer than all of them, that's normal: iOS only holds so many at a time, so the furthest away are set up as the nearer ones go off. Nothing is lost.
- **Last Topped Up** — when Due Something last rebuilt the queue. **Refresh Notifications** rebuilds it immediately.

If the system won't show alerts at all — notifications turned off, never allowed, delivered quietly, or allowed with **Banners** and the **Lock Screen** switched off — a warning at the top of that screen says which, and takes you to the setting that fixes it.

### If I travel, do my alerts move?

A task with a time doesn't move. Due at 3:00 PM means that exact moment wherever you are, so flying somewhere doesn't shift it forward or back by the time difference.

Tasks with a date but no time work the other way, because your **Default Due Time** is a time of day rather than a fixed moment. Those follow the clock where you are — you'll get them at 8:00 AM local — from the next time you open the app after landing. The **Daily Briefing** is the same kind of thing, and follows the local clock straight away.

### What is the Daily Briefing?

One notification each morning at your Default Due Time listing the tasks due that day and how many are overdue. It's skipped on days when nothing is due or overdue. Turn it off in **Settings → Default Due Time → Daily Briefing**.

### Where does tapping a notification take me?

To **Scheduled**, with the task near the top. Tapping the body of an alert never completes or changes anything — use the notification's own buttons to snooze or complete.

### What does the number on the app icon count?

Your choice, in **Settings → Appearance → Icon Badge**:

- **Overdue** — tasks whose time has passed. This is the default.
- **Due Today** — everything due today, whether or not its time has come.
- **All Scheduled** — every task with a due date, however far off.

All three rise and fall as you add and complete tasks. A task waiting on a place isn't counted by any of them, because it has no due moment until the place wakes it.

### Can I use Due Something in light or dark mode?

Yes — **Settings → Appearance → Appearance**:

- **System Default** — follows your device, which is how it starts.
- **Light Mode** and **Dark Mode** — the app stays as you set it, whatever the rest of the device is doing.

The change takes effect straight away, including on anything already open. It's one of the settings that can be kept the same on all your devices — see _Can I choose what syncs?_

### Voice dictation isn't working

Voice dictation uses Apple's Speech Recognition, which needs both microphone and speech recognition permissions:

- Go to **Settings → Due Something** and confirm both **Microphone** and **Speech Recognition** are enabled.
- Speech Recognition also requires an internet connection on some devices, depending on your settings.

### Can I go straight from one task to another?

Yes. With a task open, tap another one in the list behind it and Due Something saves the first and opens the second in its place. The task you're editing is highlighted in the list, so you can see where you are.

The list stays live while the editor is open — you can scroll it to find what you want next.

If the first task can't be saved — an empty title, a permission still to grant, or a conflict to review — it stays open so nothing is lost. A task you haven't changed, or one in a list you can only read, switches without writing anything.

### How do I attach a photo or document to a task?

Tap the paperclip next to the Notes field in the task editor — you can take a photo, scan a document, pick from your photo library, choose a file, or make a drawing. Taking photos or scanning needs camera permission (**Settings → Due Something → Camera**). Picking from your library uses Apple's photo picker, which only shares the photos you select — Due Something never sees your library. Files up to 25 MB can be attached. Tap an attachment to view it full-screen or mark it up. A task with attachments shows a small paperclip in its row, with a count when there's more than one.

### Do attachments sync between my devices?

Yes. Photos, scans, drawings, and files you attach on one device appear on your others through your iCloud account. Until a file has finished downloading, the attachment shows a cloud icon and "Waiting for iCloud" — tap it to try again if it's taking a while. Attachments count toward your iCloud storage; if it's full, new attachments stay on the device where you added them until space is freed, and Due Something tells you once.

### Can I add attachments on my Mac?

Yes. In the task editor, tap the paperclip next to Notes to add a photo from your library or choose a file. Take Photo, Scan Document, and Drawing are available on iPhone and iPad only. On the Mac, clicking an attachment opens it in its default app, such as Preview.

### Can I share or print a task?

Yes. The share button in the task editor turns a task into a PDF — its title, due date, list, location, repeat, marks, link, notes, and a page for each attachment. From there you can send it, save it to Files, or print it.

You can do it for several tasks at once too: select them in a list, tap the share icon, and choose **Export as Separate PDFs** or **Export as One PDF**, which adds a cover page listing them all.

### What is the Mac menu bar item?

A small panel that lives in your menu bar, so Due Something is one click away without switching apps. The icon shows your overdue count, and clicking it opens Scheduled in miniature — the same grouping, with snooze and complete on each task, and a field at the top for adding one.

All of it is under **Settings → Mac Only**:

- **Menu Bar Item** turns it on and off.
- **Show Menubar Window** sets a keyboard shortcut that opens it from any app.
- **Start at Login** opens Due Something when you log in.
- **Hide Mac App in Dock** keeps the app running in the menu bar alone, with no Dock icon. It needs the menu bar item switched on, since that becomes the only way back in.

### Can I narrow down what Scheduled shows?

Yes. Open the options menu (the **…** button) in Scheduled and use the filters to show only the tasks you want: **Repeating**, **Calendar**, **Flagged**, **Emergent**, **Location**, or **Alarm**. Pick more than one to widen the net. Each matches the mark shown on a task's row, so what you filter by is what you can see.

Turn them all off to go back to everything.

### Can I change several tasks at once?

Yes. Open the options menu (the **…** button) in a list, in Scheduled, or in Completed, and choose **Select**. Tap the tasks you want and a bar appears at the bottom with what you can do to them:

- **In any list, and in Scheduled** — snooze (including Smart Presets, a location, or a new date and time), flag, mark Emergent, set a location alert, move to another list, share as a PDF, complete, or delete.
- **In Completed and Recently Deleted** — restore or delete.

Snoozing a task that has no date gives it one — the time you snooze it to. Marking an undated task **Emergent** gives it the current date and time, since Emergent only means anything against a deadline. A task that already has a date keeps it.

The bar shows five buttons at a time; if you have more than that turned on, slide it sideways to reach the rest.

Choose which buttons appear at all in **Settings → Look & Feel → Batch Select Options**. Turn one off and it leaves every bar that had it. With all of a list's buttons off, Select leaves that list's menu, since there'd be nothing to do with a selection.

Tap **Edit** on that screen to drag the buttons into the order you want instead; the checkmark saves it. The order you set is used in every selection bar, whichever way round it's drawn.

Tap the **✕** on the bar to finish. On iPad and Mac, the sidebar button in the top corner turns into an **✕** while you're selecting, which does the same. With a keyboard, **⌘⇧K** completes the selection and **⌘⌫** deletes it. Deletions can be undone from the toast that follows.

### Can I change what swiping a task does?

Yes — **Settings → Look & Feel → Customize Swipe**. Each direction has three positions, and you can put Complete, Flag, Emergent, Location, Snooze, Share, Move, or Delete in any of them, or leave a position empty. The one nearest the row's edge is what a full swipe does.

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

- A repeating event carries the same head start into every occurrence.
- All-day events are left alone. They have no time of day to bring forward, so their tasks fall due at your Default Due Time as usual.

### How do I know a task is connected to a calendar?

A green calendar icon appears next to the task's title, on iPhone, iPad, Mac, and Apple Watch. It means one of two things:

- The task came from a calendar event you imported. Its notes end with a line naming the calendar — _Imported from the "Work" calendar_ — underneath the event's own location and notes.
- The task writes its own event, through **Add to Calendar** in the task editor.

You can show only these tasks in Scheduled — see _Can I narrow down what Scheduled shows?_

### Can I put a task on my calendar?

Yes. **Add to Calendar** in the task editor writes the task out as a calendar event, repeats included. **Settings → Calendar Connect → Default Event Duration** sets how long that event runs when the task has no end time. A task with no time of day becomes an all-day event.

### Reminders aren't syncing across my devices

Due Something reads and writes directly to Apple's Reminders app, so your tasks and lists sync through Apple's iCloud.

- Make sure iCloud is signed in on all your devices (**Settings → \[Your Name\] → iCloud**).
- Confirm **Reminders** is toggled on under iCloud settings on each device.
- Give it a few minutes — iCloud sync isn't always instant.

Everything Due Something adds on top of Reminders — flags, attachments, snooze settings, list icons, and more — syncs separately; see _What does iCloud Sync keep in step?_ below.

### What does iCloud Sync keep in step?

Your tasks and lists already sync through Apple Reminders. Due Something's own extras sync through your iCloud account as well, on every device signed in to the same Apple Account:

- Flags, Emergent marks, and muted alerts on tasks
- Custom Snooze settings, snooze history, and location alerts on individual tasks
- Whether a task has an alarm
- Calendar events a task has written for itself, through Add to Calendar
- Attachments
- List icons, hidden lists, sort order, list order, and manual task order
- Recently Deleted, so you can restore a task from any device
- Saved places for Snooze Location
- Which calendar events you've already imported
- Your Settings, section by section (see the next question)

It's on automatically when you're signed in to iCloud. Changes usually arrive on your other devices within a few seconds while they're awake, or the next time they open. Everything is stored in your private iCloud account and end-to-end encrypted — we have no access to it.

### Can I choose what syncs?

Yes. Go to **Settings → iCloud Sync**.

- **Sync this Device with iCloud** turns syncing on or off for the device you're holding. When it's off, that device keeps everything it has and stops sending or receiving changes; turn it back on to catch up.
- The switches below it choose which sections of Settings are kept the same on all your devices: Default View, Default List, Default Due Time, Notifications, Snooze, Widgets & Live Activities, Calendar Connect, Appearance, and Sounds & Haptics. Widgets & Live Activities and Sounds & Haptics start off, since they're about how one device shows and plays things. Turn a section off to let each device keep its own settings for it; turn it back on to share the settings of the device you turn it on from. These choices apply to all your devices.
- **Restore iCloud Sync Defaults** puts just these switches back to their defaults. It doesn't change your settings themselves.

You can also switch Due Something off entirely under **Settings → \[Your Name\] → iCloud → Saved to iCloud** on iPhone and iPad, or **System Settings → \[Your Name\] → iCloud → Saved to iCloud** on the Mac. The app keeps working from its local data.

### A list shared with me is marked view only

If someone shares a list with you as view only, Due Something shows its tasks with a lock next to the list name, and leaves the list out of the choices for new tasks. You can still change its tasks on your device, but those changes stay there — iCloud won't accept them for a list you can't edit — so the app warns you the first time. Ask the list's owner for edit access if you need to make changes that everyone sees.

### My list settings reset after I renamed a list

Due Something keeps a list's icon, sort, and visibility with the list by its name, and carries them over when you rename it — in Due Something, in Reminders, or on another device. The one case it can't tell apart is two lists with the same name in the same account; the second one keeps its settings on each device separately. Give them different names to sync both.

### What is the Shelf?

The group at the very top of the sidebar, holding Scheduled to begin with. Put the lists and smart lists you use constantly on it and they stay above everything else.

- On iPhone and iPad, drag a row across the Shelf's line to move it on or off.
- On the Mac, right-click a row and choose **Move to The Shelf** or **Remove from The Shelf**.

### Can I show two lists at once?

Yes, on iPad, Mac, and iPhone Duo. Open a list's options menu (the **…** button) and choose **Open Multi-List**, then pick the second list. They sit side by side in landscape and one above the other in portrait.

- The list you're working in is the active one. Tap an inactive list's name to switch to it.
- Tap the **active** list's name for a menu of everything you could put there instead. The list already open on the other side is greyed out, so you can't have the same one twice.
- The **✕** next to the active name closes that list and keeps the other.
- **Select** works across both at once — choose tasks on either side and the bar acts on all of them.
- Drag a task from one list to the other to move it.

Rotating, folding, or resizing the window keeps both lists. If the window becomes too small for two, the one you were working in stays and the other closes.

### Can I save a pair of lists?

Yes. With two lists open, choose **Saved Layouts → Save Current Layout** from the options menu and give it a name. It remembers both lists and which one you were working in.

Reopen it any time from **Multi-List → Saved Layouts**. You can rename them, drag them into the order you want, and delete ones you've finished with.

If a list in a saved layout has since been deleted, opening it asks you which list to use instead rather than quietly picking one.

Layouts sync across your devices.

### Can I make my own Smart List?

Yes. Start a new list as usual, then turn on **Smart List** under the name. That turns it into a saved view — it looks through the tasks you already have rather than becoming somewhere tasks live, so nothing is copied or duplicated.

Tap **Edit Rules** to say what it should show:

- **Source Lists** — which lists to look in.
- **Due Date** — overdue, today, the next 7 or 30 days, anything with a date, or anything without one.
- **Completion** — unfinished tasks, finished ones, or both.
- **Flagged**, **Emergent**, **Repeating**, **Location**, **Alarm**, and **Calendar Association** — the same marks you can filter Scheduled by.

Choose whether a task has to match **every** rule or just **any** of them. You can also give it an icon and a colour, sort it by due date or title, hide its header, and pick which real list new tasks added from it should go to.

Smart lists of your own sit in the sidebar with everything else — reorder them, put them on the Shelf, hide them, or open one in Multi-List. They sync across your devices.

Deleting one removes the view, never the tasks in it.

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

**Settings → Snooze → Set Option** decides what you're offered when you snooze:

- **Static** — the same intervals every time, set by you.
- **Adaptive** — Short, Medium and Long buckets whose durations drift toward what you actually pick.

Adaptive learns from your own past snooze choices using a small model that runs on your device. The history it learns from — when you snoozed and for how long — syncs between your devices through your iCloud account, end-to-end encrypted, so suggestions are the same everywhere. Nothing is sent to us. Turn it off or clear the history in **Settings → Snooze**.

Two more ways to snooze sit under **More Options** in the same section: **Smart Presets** (Later Today, This Evening, Tomorrow Morning, This Weekend, Next Week) and **Location-Based**. **Snooze to Date/Time** is there too — see _Can I snooze a task to a specific date or time?_

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

### Is there an Apple Watch app?

Yes. It shows your Scheduled tasks grouped the same way the iPhone does — Overdue, Today, and on through the week — with the list's color beside each one, and Emergent, flag, and calendar marks where they apply.

- **Swipe a task to act on it.** Out of the box, swiping left completes it and swiping right snoozes it — see _Can I change what swiping does on my Watch?_ to set them to something else, including Delete.
- **Tap the ＋** at the top to add a task by dictation, scribble, or the keyboard. What you say is read for dates and repeats exactly as typing it into the app would be.
- Tasks arrive on the Watch through your iCloud account, the same as your other devices. Flags, Emergent marks, and snoozes you set elsewhere show up here too.
- A task in a list shared with you as view only can't be changed from the Watch, so its swipes are dimmed.

### I added a task on my Watch with my iPhone away. Will it still alert me?

Yes. When you add a task on the Watch, the Watch works out when it's due from what you said and sets its own alert for that time, there and then. That alert lives in watchOS, so it arrives at the right moment whether or not your iPhone is reachable — out of range, switched off, or left at home for the day.

A task with a time you gave it appears straight away among the others due then, with a small red **Apple Watch** mark beside its name. That mark means it lives on your Watch and nowhere else yet; it goes as soon as your iPhone has the task. Until then you can't complete or snooze it — there's nothing to act on — but you can swipe it to cancel.

A task with no time it could work out has nowhere to sit, so it waits in **Queued for iPhone** instead, with a line saying whether the Watch alert is set. If watchOS won't show alerts — turned off, or set to deliver quietly — that line says so rather than claiming it's scheduled, and a row only says more when there is more to say: that your iPhone has it and is syncing, or that it couldn't be saved at all.

Once your iPhone has the task and has set up its own alerts for it, the Watch hands over and drops its stand-in, so you're never told twice.

Two things it can't do:

- **A task with no time it can recognise** gets no Watch alert — there's no moment to set one for. The row says so.
- **A repeating task** is left for your iPhone to work out, so that its rule is read properly rather than guessed at.

### Can I cancel a task I added on my Watch?

Yes. Swipe the row — wherever it appears, whether among your other tasks or in **Queued for iPhone** — and tap **Cancel**. The task is withdrawn, its Watch alert goes with it, and no device picks it up later. If your iPhone had already saved it in the moment before you swiped, the cancel turns into a delete, so it ends up in Recently Deleted like anything else you delete.

### Can I change what swiping does on my Watch?

Yes, on your iPhone — **Settings → Apple Watch**. The section appears once the Watch app is installed.

**Swipe Options** sets what each direction does. Either one can be **Snooze**, **Complete**, or **Delete**, so you can have the pair you actually use. Delete moves the task to Recently Deleted, the same as deleting it anywhere else, and it's the one action a full swipe won't trigger — you have to tap it, so a long swipe can't throw a task away by accident.

**Snooze Swipe Duration** decides what a snooze swipe does:

- **Open Task** — opens the task so you can pick from the full snooze menu, including Smart Presets. This is how it starts.
- **Custom…** — snoozes by a fixed amount, anything from 1 minute to 60 hours, without opening anything. Best if you nearly always reach for the same delay.

These settings travel to your Watch over its direct connection to your iPhone rather than through iCloud, so a change lands the next time the two are connected.

### Why does something I did on my Watch take a moment to appear?

watchOS doesn't allow apps to change reminders directly — only to read them. So anything you do on the Watch is carried out by your iPhone on its behalf.

- **With your iPhone nearby**, it happens straight away.
- **Without it** — your iPhone is off, out of range, or its battery has gone — the Watch holds what you did and sends it through iCloud instead. It's applied the next time the two are together or both online. You can carry on completing and snoozing in the meantime.

A task you've completed shows as done on the Watch while it waits, so you're never left wondering whether it took. A snooze keeps the time the Watch showed you as well — if you snooze something for 10 minutes at 2:00 and your iPhone only hears about it at 2:08, the task is still due at 2:10, not pushed out to 2:18.

### Can I put Due Something on my watch face?

Yes, two complications:

- **Scheduled** — your next task and how many more are due. It comes in the circular, corner, rectangular, and inline shapes, so it fits most faces.
- **New Task** — a single button that opens straight into dictation.

Long-press your watch face, tap **Edit**, choose a complication slot, and pick Due Something. They refresh as your tasks change and when the Watch wakes them.

### Does Due Something work on iPhone Duo?

Yes, in every pose.

- **Unfolded** — the full inner display, with Multi-List available in both landscape and portrait.
- **Bent in landscape** — open a task or a list and its editor appears on the far half, with the list you were in on the near one, so you can see both.
- **The front display**, and **a single half** of the unfolded screen, both work as an ordinary iPhone would.
- The lists drawer opens from the left, and swiping from the edge opens it, the same as on any other iPhone.

Folding to a screen too small for two lists keeps the one you were working in and closes the other. Unfold again and you can reopen it, or use a saved layout.

### Can I find tasks with Spotlight?

Yes. Your open tasks appear in iPhone and Mac search. Tapping a result opens it in Due Something. The index lives only on your device.

### Can I add tasks from other apps?

Yes — share a webpage, selected text, a photo, or a file from any app and choose **Due Something** in the share sheet. The page's title becomes the task title, the link is saved in the notes, a shared photo or file becomes an attachment, and any date in shared text is picked up automatically.

### Can I drag something in from another app?

Yes. Drag text, a link, or one or more files onto a list and Due Something starts a task from them:

- The first line of dropped text becomes the title and the rest becomes notes.
- A link is kept in the notes.
- Files come in as attachments. Drop several documents together and you get one task carrying all of them.
- Either side of Multi-List will take a drop; the one under your finger highlights.

The task opens in the editor with everything filled in, so **nothing is saved until you tap Save**. Cancel and the copied files are discarded.

Files are limited to 25 MB each, and one drop can carry up to 20 items and 100 MB in total. If something in the drop can't be read, the whole import stops and tells you, rather than quietly leaving part of it out.

Read-only lists don't accept drops.

### Can I add several tasks at once?

Yes — type them one per line in the title field and each line becomes its own task, sharing the date, time, repeat, list, and notes you've set. Any attachments go on the first one.

Two more shortcuts while you're typing a title:

- **Type a "/" followed by a list name** — for example `Milk /groceries` — and Due Something offers matching lists. Pick one and the task goes there, with the "/" part removed from the title.
- **Retype something you've done before** and after three letters Due Something offers matching completed tasks from that list. Picking one brings the original task back rather than making a copy, so your history stays in one place instead of filling up with duplicates.

### Does Due Something work with Siri and Shortcuts?

Yes. Try "Add a task to Due Something" or "What's overdue in Due Something" — phrases need to include the app's name. You can also snooze by voice: "Snooze my overdue tasks in Due Something for 30 minutes", "Snooze everything in Due Something", or "Snooze a task in Due Something", which asks you which task and how long. The Shortcuts app has the full set of actions (add, search, snooze, batch snooze, and more) for building your own automations.

### Does Due Something have keyboard shortcuts?

On the Mac, and on iPad with a keyboard: **⌘N** new task, **⌘⇧N** new list, **⌘F** search, **⌘1** Overview and **⌘2** through **⌘5** the smart lists, **⌘⇧K** complete the selected tasks, and **⌘⌫** delete them. In the task editor, **⌘↩** saves and **Esc** cancels. On the Mac, the View menu also has **⌘+**, **⌘−**, and **⌘0** to make the text bigger, smaller, or actual size.

### Does Due Something work with VoiceOver and other accessibility features?

Yes. Every control is labeled for VoiceOver, undo toasts are announced and stay until you act on them, and the app follows Larger Text, Reduce Motion, Increase Contrast, and Differentiate Without Color.

Two notes about gestures that are held rather than tapped. Search is normally opened by pulling down on a list and holding; when VoiceOver, Switch Control, or AssistiveTouch is on, a search button appears in the toolbar instead. The same applies to making a list on iPad — a **＋** button appears at the top of the sidebar in place of the pull-and-hold. With Voice Control, use Siri or a keyboard to search.

### I left a tip but something went wrong

Thank you! Tips are one-time purchases handled entirely by Apple's App Store — Due Something never sees your payment details. If a purchase fails or the Tip Jar shows tips as unavailable, check that you're signed in to the App Store and that in-app purchases aren't restricted in Screen Time. If Apple charged you and something still looks wrong, email us and we'll sort it out.

---

## Still Need Help?

If your question isn't answered above, reach out and we'll get back to you:

📧 [duesomethingapp@gmail.com](mailto:duesomethingapp@gmail.com)

When reporting an issue, it helps to include:

- Your device model and iOS version
- What you expected to happen vs. what actually happened
- Steps to reproduce the issue, if possible

---

## Privacy

Curious about what data Due Something accesses and how it's handled? See our [Privacy Policy](https://duesomethingapp.github.io/privacypolicy/).
