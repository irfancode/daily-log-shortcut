# Quick Build Guide — Create Your Daily Log in 5 Minutes

Follow these exact steps to build the shortcut:

---

## Step 1: Create the Notes Folder

1. Open **Notes** app
2. Tap **Back** → **New Folder**
3. Name: `Daily Log`
4. Ensure **iCloud** is selected (blue cloud icon)

---

## Step 2: Build the Shortcut

Open **Shortcuts** → Tap **+** → Name it `Daily Log`

### Add These Actions (in order):

```
Action 1: Date
          → Format: "EEEE, MMMM d, yyyy" (e.g., "Wednesday, May 6, 2026")

Action 2: Get Notes
          → Folder: Daily Log
          → Sort by: Modified (Newest First)
          → Limit: 1

Action 3: If (Note exists)
          → Continue with "Then"

Action 4: Get Text from Note
          → (From previous result)

Action 5: Text
          → Paste this template:

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
🌅 MORNING

[Your intentions for today]

📊 YESTERDAY
───────────────────────────────────
[Yesterday's wins & todos copied below]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Action 6: Combine Text
          → Template (Action 5) + Yesterday's Note (Action 4)

Action 7: Create Note
          → Folder: Daily Log
          → Title: Today's Date (from Action 1)

Action 8: Add to Note
          → Content: Combined text (from Action 6)

Action 9: Open Note
```

### For "Else" (new day - no previous note):
```
Action: Text
        → Paste:

📅 [Today's Date]
━━━━━━━━━━━━━━━━━━━━━━

🌅 MORNING

-

📊 YESTERDAY
─────────────────
(No previous entry)

📝 TONIGHT
──────────
Wins:
-

Todos for tomorrow:
-

💭 REFLECTION
─────────────

Action: Create Note → Same as above
        → Open Note
```

---

## Step 3: Test It

1. Tap the shortcut in Shortcuts
2. Should open a new note in "Daily Log" folder
3. Run again — should copy from previous entry

---

## Step 4: Make It One-Tap Access

### Option A: Back Tap (Recommended)
```
Settings → Accessibility → Touch → Back Tap
→ Double Tap → Daily Log
```

### Option B: Home Screen
```
Long press home screen → Edit → Add Widget
→ Shortcuts → Daily Log
```

### Option C: Siri
```
Say: "Hey Siri, Daily Log"
```

---

## Step 5: Automate Reminders (Optional)

```
Shortcuts → Automation → + → Time of Day
→ Morning: 7:00 AM
→ Evening: 9:00 PM
→ Action: Run Shortcut → Daily Log
```

---

## You're Done! 🎉

Now you have:
- ✅ One-tap daily journaling
- ✅ Automatic template from yesterday
- ✅ iCloud sync across all devices
- ✅ Streak-ready habit builder

**Start your streak today.**