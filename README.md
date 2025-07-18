# 🗓️ Event Scheduler Program

A simple yet functional console-based Event Scheduler developed using **Object-Oriented Programming (OOP)** principles. This program allows users to efficiently manage events by creating, viewing, deleting, and exiting the event management system.

## 🚀 Features

This application supports four core operations:

### 1️⃣ Create Event
Allows users to create a new event by entering structured input when prompted. The user provides specific details such as:
- **Title** – a unique identifier for the event
- **Date & Time** – when the event is scheduled
- **Description** – optional additional details
- **Location** – where the event will be held

The event is stored in memory and can be retrieved or manipulated later.

### 2️⃣ View Events
Displays a list of all saved events with their full details in a readable format. If no events have been created, the program informs the user accordingly.

### 3️⃣ Delete Event
Prompts the user to enter the title of the event they wish to delete. If the title matches an existing event, the program removes it from the event list.

### 4️⃣ Exit Program
Closes the scheduler gracefully, ending the current session.

---

## 🧠 How It Works

This project is built using **Object-Oriented Programming**. The main components include:
- An `Event` class that encapsulates attributes like title, date, location, and description.
- A `Scheduler` class or controller that handles user interaction and manages the collection of `Event` objects.

Each feature is tied to a method that keeps the code modular, maintainable, and easy to expand.

---

## 📦 Setup & Run

1. Clone the repo:
   ```bash
   git clone https://github.com/Mtho-hub/Event-Scheduler.git
