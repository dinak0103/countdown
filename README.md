# ⏳ Custom Countdown Timer

A customizable countdown timer built using HTML, CSS, and JavaScript. This app lets users set a countdown title and date, displays a live countdown, and stores the timer in local storage for persistence across sessions.

## 🔧 Features

- User-defined countdown title and target date
- Real-time countdown display (days, hours, minutes, seconds)
- Countdown auto-resumes on page reload via `localStorage`
- Reset option to clear countdown
- Responsive design

## 🧠 Technologies Used

- HTML
- CSS
- JavaScript (Vanilla)

## 🚀 Getting Started

To run the project locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/custom-countdown.git
  ```
2. Clone the repository:

   ```bash
cd custom-countdown
  ```

3. Open index.html in your browser:

```bash
open index.html
  ```

## 🎯 Function Highlights

- updateDOM(): Updates countdown UI every second
- updateCountdown(): Captures form input and starts countdown
- reset(): Resets countdown and clears storage
- restorePreviousCountdown(): Loads previous countdown from localStorage on page load

