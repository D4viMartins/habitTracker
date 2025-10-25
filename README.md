# 📈 Habit Tracker with Pixela API

> A Python automation project that tracks daily habits using the **Pixela API** — a web service that lets you visualize progress with beautiful graphs.  
> This script allows you to create, update, and delete data points (“pixels”) directly from Python, making habit tracking effortless.

## 🧩 Technologies and Tools Used

- **Python 3.10+**
- **Requests** — for making HTTP requests to the Pixela API
- **Datetime** — for generating dynamic dates in the correct format
- **Pixela API** — to visualize data in a clean and interactive graph interface

## ⚙️ Main Features

- **User Creation:**  
  Registers a new user on Pixela with username and authentication token.

- **Graph Creation:**  
  Builds a custom graph (e.g., cycling, studying, coding) with defined units, colors, and data types.

- **Pixel Logging:**  
  Adds a new “pixel” entry to track your daily progress — such as kilometers cycled, hours studied, or lines of code written.

- **Data Update:**  
  Modifies any existing record directly from Python (e.g., changing the number of kilometers for a day).

- **Data Deletion:**  
  Removes specific entries from the graph with a single command.

## 🖥️ Demonstration

```bash
# Example of daily progress tracking

📊 Created user: notshinigami  
📈 Created graph: "Cycling Graph"  
📅 Added pixel for date: 2025-10-23 → 5 km  
✏️ Updated pixel: 10 km  
🗑️ Deleted pixel entry for 2025-10-23
