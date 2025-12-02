# Adaptive-OS-Scheduler-for-Real-Time-Systems
Adaptive OS Scheduler for Real-Time Systems

A dynamic and intelligent task scheduling system designed for real-time operating environments. This project demonstrates how task priorities can be automatically adjusted based on deadlines, execution time, workload changes, and system conditions—ensuring timely task completion and optimized CPU utilization.

📌 Project Overview

Traditional real-time schedulers (like RMS or EDF) work on fixed rules. However, modern systems require adaptability due to fluctuating task loads and unpredictable execution times.

This project introduces an Adaptive OS Scheduler that:

Continuously monitors real-time task parameters

Dynamically adjusts priorities

Detects missed deadlines

Optimizes scheduling decisions

Provides a visual simulation using HTML, CSS, and JavaScript

🎯 Key Features
✅ Real-Time Task Modeling

Each task has:

Arrival Time

Execution Time

Deadline

Priority

Remaining Time

Status Indicators

✅ Dynamic Priority Adjustment

Priority changes based on:

Deadline closeness

Remaining execution time

System load

Task urgency

✅ Visual Simulation (Browser-Based)

The interactive UI displays:

Task list with details

Live scheduler execution

Timeline view

Indicators:

🟢 Next task to execute

🔴 Deadline missed

✅ Adaptive Algorithm

Custom adaptive logic to prevent deadline failures

🖥️ Tech Stack

HTML5 – Interface structure

CSS3 – UI styling & visual indicators

JavaScript – Core scheduling logic & dynamic simulation
