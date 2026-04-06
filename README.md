🧠 Virtual Memory Management Simulator

📌 Overview

This project is an interactive web-based simulator that demonstrates key concepts of operating system memory management, including paging, segmentation, and page replacement algorithms. It allows users to visualize how memory is allocated and how different algorithms affect performance.

🎯 Features 

🔹 Paging simulation with frame allocation

🔹 Page fault detection and tracking

🔹 LRU (Least Recently Used) algorithm

🔹 Optimal page replacement algorithm

🔹 Step-by-step execution table

🔹 Interactive UI with user input

🔹 Graphical comparison of algorithms

🔹 Performance analysis (fault comparison)

⚙️ Technologies Used

React.js

JavaScript

HTML & CSS

Vite

🧪 How to Run

npm install

npm run dev


Then open:

http://localhost:5173

📊 Example Input

Reference String: 7,0,1,2,0,3,0,4,2,3,0,3,2

Frames: 3

🧠 Concepts Covered

Paging

Segmentation (basic concept)

Page Faults

Demand Paging

LRU Algorithm

Optimal Algorithm

📈 Output

Total page faults

Step-by-step memory state

Graph comparison of algorithms

FLOWCHART

START
   ↓
User Inputs:
- Page Reference String
  
- Frame Capacity
  
   ↓
Click "Run Simulation"

   ↓
Parse Input Data

   ↓
Run LRU Algorithm

   ↓
Check:

Is page in memory?
   ↓
Yes → HIT

No  → PAGE FAULT

   ↓
Update Frames (LRU logic)
   ↓
Store Steps + Count Faults
   ↓
Run Optimal Algorithm
   ↓
Check:

Is page in memory?
   ↓
Yes → HIT

No  → PAGE FAULT
   ↓
Replace page (Optimal logic)

   ↓
Store Steps + Count Faults

   ↓
Display Results:

- LRU Faults
  
- Optimal Faults
  
   ↓
Show Graph Comparison

   ↓
Show Step-by-Step Table

   ↓
  
END
