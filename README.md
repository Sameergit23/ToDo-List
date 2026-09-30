# AnimatoDo: To-Do List with Reminders

AnimatoDo is a single-page to-do list that runs in the browser. You can add tasks with an optional date and time, and it plays a sound and shows a reminder box when a task is due. It is one `index.html` file with no dependencies or build step, and tasks are saved in your browser's `localStorage`.

## Features

- Add tasks with an optional **date** and **time**
- **Reminder alerts** when a task is due: a sound plays and a popup offers **Done** or **Silent**
- **Edit tasks inline** by clicking the task text
- Tick off completed tasks, or delete them
- **Tasks persist** across page reloads
- Paste a date (`YYYY-MM-DD`) or a time (`HH:MM`) straight into the date and time fields

## Getting started

No install is needed. Clone the repo and open `index.html` in a browser:

```bash
git clone https://github.com/Sameergit23/ToDo-List.git
cd ToDo-List
# open index.html in your browser
```

Keep the tab open for reminders to fire. The app checks for due tasks every 10 seconds, and your browser may need to allow audio playback for the page.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole app: markup, styles and JavaScript |
| `reminder.mp3` | Sound played when a reminder is due |

## Tech stack

HTML · CSS · Vanilla JavaScript · Web Storage API

## Author

Built by [Sameer Akhtar](https://github.com/Sameergit23).
