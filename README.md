#  AI Aerospace Decision Tool

A project that demonstrates how **AI use cases in aerospace can be evaluated and ranked** using a structured decision model.

---

##  Overview

The **AI Aerospace Decision Tool** is an interactive web-based dashboard that compares different aerospace AI applications based on key decision factors:

* Impact
* Risk
* Technical Complexity
* Feasibility
* Cost
* Data Availability

The goal is to help answer a real-world question:

> *“Which AI projects are actually worth pursuing in aerospace?”*

---

##  Live Demo

https://louiea11.github.io/ai-aerospace-decision-tool/

---

##  Key Features

*  **Weighted Decision Model**
  Adjust priorities and instantly see how rankings change

*  **Interactive Visualization**
  Dynamic ranking table + bar chart

*  **Multiple AI Use Cases**
  Includes applications in aviation, satellites, and space missions

*  **Fully Client-Side**
  Runs entirely in the browser (no backend required)

---

## 🛠️ Tech Stack

* **HTML / CSS / JavaScript**
* **Chart.js** for visualization
* Originally prototyped in **Python (Matplotlib)** and converted to web

---

## 📊 How It Works

Each application is scored using a weighted formula:

```
Final Score =  
(Impact × Weight)  
− (Risk × Weight)  
− (Complexity × Weight)  
+ (Feasibility × Weight)  
− (Cost × Weight)  
+ (Data Availability × Weight)
```

Users can adjust weights to simulate different priorities such as:

* research-focused (high impact)
* cost-sensitive (low budget)
* safety-critical (low risk)

---

##  AI Applications Compared

* Satellite Image Analysis
* Aircraft Fault Detection
* Weather Forecasting
* Autonomous Navigation
* Space Mission Planning

---

##  What This Project Demonstrates

* Decision modeling and tradeoff analysis
* Translating Python logic into a web app
* Data visualization and UI design
* Ability to communicate technical ideas clearly

---

##  Future Improvements

* Integrate real aerospace datasets
* Add scenario presets (NASA, airline, startup, defense)
* Build backend with Flask or FastAPI
* Export reports (PDF / CSV)
* Add more AI applications

---

## 👤 Author

**Louie Alruzouq**

