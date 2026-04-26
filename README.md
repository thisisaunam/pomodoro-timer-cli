# Customizable pomodoro timer

A command-line python application that implements a structured and customizable pomodoro timer with multiple themes, session handling, and robust input validation.

---

## Features

* Multiple theme modes:
  * Classic
  * Soft study
  * Focus mode
  * Late-night workflow
  * Cozy desk
  * Monochrome minimal

* Predefined timer configurations:
  * 25 minutes work / 5 minutes break
  * 30 minutes work / 5 minutes break
  * 50 minutes work / 10 minutes break

* Fully customizable timer:
  * User-defined hours, minutes, and seconds for both study and break durations

* Session-based execution:
  * Supports multiple consecutive study sessions in a single run

* Centralized timer logic:
  * Reusable core function reduces redundancy and improves scalability

* Strong input validation:
  * Ensures only valid numeric inputs are accepted
  * Handles invalid entries using exception handling and loops

* Interactive CLI interface:
  * Structured prompts and clean output flow

---

## How to run

```id="run101"
python pomodoro_timer_v1.py
```

---

## Project structure

* pomodoro_timer_v1.py → main application file

---

## Concepts demonstrated

* Modular programming using functions
* Control flow (loops and conditionals)
* Input validation with try-except blocks
* Time-based execution using the `time` module
* Code reusability and abstraction

---

## Future improvements
* Persistent session tracking using file handling
* Sound/notification integration
* Menu-driven navigation system
* Graphical user interface (GUI) version

---

## Preview

<img width="587" height="751" alt="image" src="https://github.com/user-attachments/assets/b1c32ce4-c833-4b59-ae25-64a3380dc99b" />
<img width="660" height="726" alt="image" src="https://github.com/user-attachments/assets/31cdbde2-a09e-4047-8020-51f27bd1b761" />
<img width="572" height="553" alt="image" src="https://github.com/user-attachments/assets/f81051a6-eb77-4a6e-b68d-1857e9fd421a" />

---

## Notes

This project is part of a broader effort to build structured, user-interactive command-line applications while strengthening core python fundamentals.
