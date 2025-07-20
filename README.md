# 🖥️ EFFICIO - OS Scheduling & Page Fault Simulation Web App

EFFICIO is a web-based educational tool designed to **simulate Operating System scheduling algorithms** and **page replacement algorithms** interactively. The user can choose an algorithm, provide required inputs, and get key outputs like process completion times, waiting times, turnaround times, cache hits, and misses — all in a user-friendly interface.

---

## 🚀 Features

- 🔐 **User Authentication**
  - Secure login and registration system.
  - Only authenticated users can access the calculation tools.
  - Session persists until logout.

- 📊 **Algorithm Selection**
  - Dropdown menu to choose from various scheduling or page replacement algorithms.

- 🧾 **Custom Input Forms**
  - Enter dynamic values such as:
    - Arrival time
    - Burst time
    - Number of processes
    - Time quantum (for RR)
    - Frame size
    - Page reference string

- 📈 **Comprehensive Results**
  - CPU Scheduling Output:
    - Process-wise completion time
    - Waiting time
    - Turnaround time
    - Average waiting and turnaround times
  - Page Replacement Output:
    - Number of cache hits
    - Number of cache misses

- 👥 **Session Management**
  - User remains logged in unless explicitly logged out.

- 📬 **Contact Page**
  - Users can reach out for queries, feedback, or support.

---

## 🧠 Algorithms Implemented

### 🔄 CPU Scheduling Algorithms

1. **First-Come-First-Served (FCFS)**
2. **Shortest Job First (SJF)**
3. **Round Robin (RR)**
4. **Shortest Remaining Time First (SRTF)**
5. **Highest Response Ratio Next (HRRN)**

**Output:**
- Completion Time (for each process)
- Waiting Time
- Turnaround Time
- Average Waiting Time
- Average Turnaround Time

### 🧠 Page Replacement Algorithms

1. **First-In-First-Out (FIFO)**
2. **Least Recently Used (LRU)**
3. **Optimal Page Replacement**

**Output:**
- Number of Cache Hits
- Number of Cache Misses

---

## 🧰 Tech Stack & Skills Used

- `HTML`, `CSS`, `Bootstrap` — for responsive frontend
- `Flask` — Python web framework for backend
- `SQL` — User login and data management
- `Operating System Concepts` — Scheduling and Paging algorithms
- `Jinja2` — for template rendering in Flask

---

## 📂 Folder Structure
```
EFFICIO/
│
├── app.py # Main Flask application
│
├── algorithms/ # Folder containing all algorithm logic
│ ├── fcfs.py # First Come First Serve
│ ├── sjf.py # Shortest Job First
│ ├── rr.py # Round Robin
│ ├── srtf.py # Shortest Remaining Time First
│ ├── hrrn.py # Highest Response Ratio Next
│ ├── fifo.py # FIFO Page Replacement
│ ├── lru.py # LRU Page Replacement
│ └── optimal.py # Optimal Page Replacement
│
├── templates/ # HTML templates for frontend
│ ├── index.html # Home page
│ ├── login.html # Login page
│ ├── register.html # Registration page
│ ├── scheduler.html # Scheduling algorithms page
│ ├── page_fault.html # Page replacement algorithms page
│ └── contact.html # Contact form page
│
├── static/
│ └── images/ # Image assets used in the app
│ └── efficio_logo.png # Example logo and other images
│
└── README.md # Project documentation file
```



