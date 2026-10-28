# dot.

Your AI. Always with you.

A voice-first personal AI that runs in the browser on any device.

**Live:** https://drexskills.github.io/dot-app/

## What it does
- Full-screen voice: tap the mic, talk, and dot answers out loud
- Free natural voices already on your device (no API key, no subscription)
- Memory you approve, edit and delete
- Reminders and notes by voice
- Upload images or text files and ask about them
- Animated dot with moods, and installable to your Home Screen

## Brain
Inside Claude, dot uses Claude. On this site, set your dot server address in the menu under **Brain server**. The server needs a `POST /api/chat` endpoint that takes `{"message": "..."}` and returns `{"reply": "..."}`, served over https.

## Add to Home Screen
- iPhone: open in Safari, tap Share, then Add to Home Screen
- Android: open in Chrome, tap the menu, then Install app
