# Alarm-Clock

[![JavaScript](https://img.shields.io/badge/JavaScript-yellow?style=flat-square&logo=javascript&logoColor=black)](https://www.javascript.com/)

## Introduction

Alarm-Clock is a web-based alarm clock application with a modern Neumorphism design. It allows users to set alarms and displays the current time. This project is built using JavaScript.

Key features include:

*   Setting alarms for specific times.
*   Displaying the current time in real-time.
*   A visually appealing Neumorphism user interface.

## Installation

To run this project, you'll need a web browser that supports JavaScript.  Since the provided code snippet is JavaScript, no specific installation steps are required.  Simply open the HTML file (if one exists) in your browser.

## Usage

To use the Alarm-Clock, follow these steps:

1.  **Open the HTML file:**  Locate the HTML file (e.g., `index.html`) in your project directory and open it in your web browser.
2.  **Set the alarm:**  The interface will likely provide controls (e.g., dropdowns, input fields) to set the desired alarm time (hour, minute, second).
3.  **View the current time:** The current time will be displayed in real-time.
4.  **Wait for the alarm:** When the current time matches the set alarm time, the alarm will trigger (implementation details not provided in the code snippet, but likely involves a sound or visual notification).

Example (based on the provided `JsAlarm.js` snippet):

```javascript
// Assuming the HTML has elements with the following IDs:
// chr, cmin, csec (for current time display)
// tpick-h, tpick-m (for time picker)

var ac = {
    // (A) INITIALIZE ALARM CLOCK
    init : function () {
      // (A1) GET THE CURRENT TIME - HOUR, MIN, SECONDS
      ac.chr = document.getElementById("chr");
      ac.cmin = document.getElementById("cmin");
      ac.csec = document.getElementById("csec");

      // (A2) CREATE TIME PICKER - HR, MIN, SEC
      ac.thr = ac.createSel(23);
      document.getElementById("tpick-h").appendChild(ac.thr);
      ac.thm = ac.createSel(59);
      document.getElementById("tpick-m").appendChild(ac.thm);
      // ... (rest of the code)
    }
};

// Call the init function to initialize the alarm clock
ac.init();
```

## Features

*   **Time Display:** Displays the current time (hours, minutes, seconds).
*   **Alarm Setting:** Allows users to set alarms.
*   **Neumorphism Design:**  Employs a Neumorphism user interface for a modern look.
*   **JavaScript Implementation:**  Built using JavaScript for front-end functionality.

## Contributing

Contributions to the Alarm-Clock project are welcome!  If you'd like to contribute, please:

1.  **Fork the repository.**
2.  **Create a new branch** for your feature or bug fix.
3.  **Make your changes.**
4.  **Submit a pull request.**

Please ensure your code adheres to the project's coding style (if any) and includes appropriate documentation.