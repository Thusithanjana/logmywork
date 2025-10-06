# 🕒 Today's Work Tracker

A simple and elegant web app for tracking your daily tasks and calls. It allows you to record task descriptions, start and stop timers, edit task notes, and export your activity log as a CSV file.

---

## 🚀 Features

- **Task Timer** — Start and stop timers for individual tasks.  
- **Call Tracker** — Separate button for tracking phone calls.  
- **Auto Save** — All data is stored in the browser session automatically.  
- **Edit Descriptions** — Update task descriptions anytime.  
- **CSV Export** — Download your session logs as a formatted CSV file.  
- **Clean UI** — Minimalist card-based layout with responsive design.  

---

## 🧭 How It Works

1. Open `index.html` in any modern browser (Chrome, Edge, Firefox, Safari).  
2. Enter a task description in the text area.  
3. Click **Start Task** to begin timing.  
4. Click **Stop Task** to end and save it.  
5. Use **Call** / **Hang Up** to track call durations.  
6. Use the **Edit** button to change task descriptions.  
7. Click **Save as CSV** to download all session data as a `.csv` file.

---

## 💾 Data Storage

- Tasks are stored **temporarily** in your browser’s `sessionStorage`.  
- Closing the browser or tab clears the data automatically.  
- Export to CSV before closing to save your work permanently.

---

## 📄 CSV Format

Each row in the exported CSV contains:
| No | Description | Start Time | End Time | Duration |
|----|--------------|-------------|-----------|-----------|

---

## 🛠️ Technical Overview

- **Languages:** HTML, CSS, JavaScript (no external libraries)  
- **Storage:** Browser `sessionStorage`  
- **Export:** Blob-based CSV download  
- **Compatibility:** Works offline and in any modern browser

---

## 🧑‍💻 Developer Notes

- You can customize styles in the `<style>` section of the HTML file.  
- Modify the constant `STORAGE_KEY` if you want multiple versions to store data separately.  
- The app intentionally uses no frameworks for portability and simplicity.  

---

## 📦 Deployment

Just upload `index.html` to any web server or open it locally by double-clicking the file.  
No dependencies, no build steps — it’s ready to use.

---

## 📜 License

This project is open source under the [MIT License](https://opensource.org/licenses/MIT).
