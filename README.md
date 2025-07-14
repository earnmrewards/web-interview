# 🧪 Live Coding Challenge – Web Developer

Welcome to the live coding challenge!

This exercise is designed to evaluate your understanding of React, TypeScript, client-side behavior and server-side integration with Next.js. Feel free to structure the code as you see fit — we value clarity, modularity, and good decision-making.

---

## 🎯 Challenge: Inactivity Timer

### ✅ Goal

Implement a timer that tracks **user activity** on the page.

### 🔹 Requirements

- The timer should start counting when the user opens the page.
- It should reset whenever the user interacts with the page:
  - Click
  - Scroll
  - Keyboard input
- Every **10 seconds of inactivity**, log the total elapsed time in the console.
- The counter should **pause when the user leaves the tab** or browser window (e.g. tab goes to background or window loses focus).
- The timer should resume when the user returns to the page.
- The log format must be: `mm:ss`.

### 💡 Notes

- The UI does **not** need to be styled.
- Focus on: clear logic, correct behavior, and clean code.
- You may use any folder structure and tools (hooks, utils, etc.).
- You are free to use browser APIs and helper libraries if needed.

---

## ⚡ Bonus Challenge

If you complete the main task and there’s still time left, add the following:

### 📝 Server Logging

Every time the user hits 10 seconds of inactivity and logs to the console, also:

- Use a _server function_ to log a payload with the following data:
  - `elapsedTime` (in seconds or `mm:ss`)
  - `timestamp`
  - Any metadata you find useful (e.g., page URL, user agent)

Good luck!
