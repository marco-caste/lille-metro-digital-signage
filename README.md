# Public Transport Digital Signage (Lille Metro)

Front-end web interfaces developed during an internship at **Aesys S.p.A.** (Summer 2022). 

### 📝 Description
This project contains a set of simulated smart displays designed as **Proof of Concept (PoC)** and rapid prototypes for the public transport network of Lille, France. The interfaces were developed to test different UX/UI solutions, asynchronous event handling, and multimedia rendering in a simulated environment. The focus was on clear design and vanilla web technologies without relying on heavy external frameworks.

### ✨ Key Features
- **On-Board Dynamic Displays (`onboard_display_1920x540.html`):** Real-time route tracking with progress indicators, asynchronous delay timers, and synchronized multimedia ads (alternating images and videos).
- **Station Arrival Boards (`station_arrivals.html`):** Countdown timers for upcoming trains, dynamically updating via JavaScript `setInterval` functions.
- **Interactive Events & Audio:** Implemented a functional passenger "STOP" request button triggering visual feedback and audio chimes.
- **Emergency & Service States:** Dedicated high-contrast screens for Fire Alarms (`fire_alarm.html`) and Out-of-Service notices (`out_of_service.html`) with dual-language (English/French) toggling and flashing backgrounds to capture immediate attention.

### 🧠 UX/UI Considerations
The design process involved direct user empathy, inspired by real-world navigation challenges in major subway systems. Layouts were optimized for immediate readability, prioritizing contrast, scrolling text for upcoming stops, and clear multilingual instructions.

### 🛠️ Tech Stack
- **Languages:** HTML5, CSS3, Vanilla JavaScript
- **Concepts:** DOM Manipulation, Asynchronous Programming (`setInterval`/`setTimeout`), Multimedia Synchronization, UX/UI Design
