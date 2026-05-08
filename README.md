# Hi, I'm Zehuan Yu

I have a background in mechanical engineering, robotics, and data analysis, with hands-on experience in automotive engineering, ROS 2 simulation, Python programming, C++, SQL, and technical problem solving.

My projects focus on building practical engineering and data workflows, including autonomous racing simulation, emergency braking logic, data analysis pipelines, mathematical modeling, and C++ object-oriented programming.

---

## Featured Projects

### F1TENTH Race Planner

A ROS 2 local racing planner for the F1TENTH simulator using LiDAR-only perception.

This project combines wall following, follow-the-gap, local trajectory planning, predictive speed control, racing-line biasing, and ML-assisted tuning. The planner was tested in the F1TENTH simulator on the Spielberg map, with parameter studies comparing speed limits, planning horizon, clearance margins, steering smoothing, and ML tuner settings.

**Highlights:**

- Built a LiDAR-based local planner for autonomous racing simulation
- Combined wall following, follow-the-gap, and local planning logic
- Added predictive speed control based on curvature, clearance, braking distance, and steering smoothness
- Used parameter tuning and ML-assisted adjustment to improve lap performance
- Ran simulator tests and documented ranked parameter-study results

**Tech Stack:** ROS 2, Python, F1TENTH simulator, LiDAR, NumPy, YAML, Docker/noVNC

---

### F1TENTH Automatic Emergency Braking

A ROS 2 safety node for the F1TENTH simulator that uses LiDAR and odometry data to detect collision risk and apply emergency braking.

This project focuses on autonomous vehicle safety. The node calculates time-to-collision from laser scan data and vehicle speed, then publishes braking commands when the car gets too close to obstacles.

**Highlights:**

- Implemented automatic emergency braking logic
- Used `/scan` LiDAR data and `/ego_racecar/odom` velocity feedback
- Calculated time-to-collision for obstacle detection
- Published Ackermann drive commands to stop the vehicle
- Tested braking behavior in the F1TENTH simulator

**Tech Stack:** ROS 2, Python, F1TENTH, LiDAR, Odometry, Ackermann Drive

---

### F1TENTH Installation Guide

A reproducible setup guide for launching and running the F1TENTH simulator environment.

This project documents the installation workflow for Ubuntu, WSL2, Docker, ROS 2 Foxy, and the F1TENTH gym simulator. The goal was to make simulator setup easier for new users and reduce environment-related debugging time.

**Highlights:**

- Documented native and Docker-based setup workflows
- Covered ROS 2 Foxy and F1TENTH simulator dependencies
- Helped standardize the simulator launch process
- Focused on making the development environment reproducible

**Tech Stack:** ROS 2 Foxy, Ubuntu, Docker, WSL2, F1TENTH Gym

---

### Spotify Year-End Music Trend Analyzer

A Python data analysis project comparing 2020 and 2021 year-end music trends using Spotify API data, SQLite, SQL queries, and Matplotlib visualizations.

**Highlights:**

- Collected playlist data from the Spotify Web API
- Stored artist and track records in SQLite
- Used SQL joins to compare artists across years
- Identified artists appearing in both years and artists unique to each year
- Generated visualizations for artist overlap and trend comparison

**Tech Stack:** Python, Spotify API, SQLite, SQL, Matplotlib, JSON

---

### BioStatistics: HIV Dynamics Simulation

A Python-based mathematical modeling project that simulates HIV infection dynamics and immune response using ordinary differential equations.

**Highlights:**

- Modeled interactions between healthy CD4+ T-cells, infected cells, virions, and immune response cells
- Used SciPy ODE solvers for numerical simulation
- Compared immune response behavior under different parameter settings
- Visualized CTLp and CTLe trends over time

**Tech Stack:** Python, NumPy, SciPy, Matplotlib, ODE modeling

---

### Intro-to-Programming-Cpp-Projects

A semester-long C++ programming portfolio covering console applications, games, ciphers, object-oriented design, and simulation.

**Highlights:**

- Built projects including a focaccia calculator, Rock-Paper-Scissors game, cipher program, Battleship game, and elevator simulation
- Practiced C++ fundamentals, functions, loops, strings, file input, and class design
- Developed larger multi-file programs using object-oriented programming

**Tech Stack:** C++, OOP, File I/O, Console Applications

---

## Technical Skills

**Programming:** Python, C++, SQL  
**Robotics & Simulation:** ROS 2, F1TENTH, LiDAR, Odometry, Ackermann Drive, Docker  
**Data & Analysis:** SQLite, Pandas-style data workflows, Matplotlib, JSON, API data collection  
**Engineering:** Automotive systems, simulation testing, parameter tuning, technical documentation  
**Tools:** Git, GitHub, Ubuntu, WSL2, Docker, VS Code

---

## Current Focus

I am currently building projects at the intersection of robotics, simulation, automotive engineering, and data analysis. My strongest interests are autonomous vehicle simulation, safety systems, data-driven engineering, and practical software tools for solving real engineering problems.
