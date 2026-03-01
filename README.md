# Merge Sort Recursion Tree Visualizer

## Overview
The **Merge Sort Recursion Tree Visualizer** is an interactive web-based tool that demonstrates how the **Merge Sort algorithm** works using a recursion tree representation.  
It visually shows how an array is divided into smaller subarrays (splitting phase) and then merged back in sorted order (merging phase) with step-by-step animation.

This project helps students understand the internal working of **Divide and Conquer algorithms** through clear visualization.

---

## Features
- Interactive visualization of the Merge Sort recursion tree  
- Step-by-step animation of:
  - Splitting phase  
  - Merging phase  
- Dynamic input array (user-defined values)  
- Adjustable animation speed  
- Real-time statistics:
  - Number of comparisons  
  - Number of splits  
  - Number of merges  
  - Total steps executed  
- Color-based visualization:
  - **Orange** → Splitting  
  - **Green** → Merging  
  - **Highlighted nodes** for active operations  
- Responsive UI design

---

## How Merge Sort Works

**Merge Sort** is a **Divide and Conquer** algorithm that works in three steps:

1. **Divide**  
   Split the array into two halves recursively until each subarray contains only one element.

2. **Conquer**  
   Recursively sort the subarrays.

3. **Merge**  
   Combine the sorted subarrays to produce the final sorted array.

### Time Complexity
- Best Case: **O(n log n)**  
- Average Case: **O(n log n)**  
- Worst Case: **O(n log n)**

### Space Complexity
- **O(n)** (extra space required for merging)

---

## Technologies Used
- HTML5  
- CSS3  
- JavaScript (ES6)

## Project Structure
```
Merge-Sort-Recursion-Tree/
│
├── index.html
└── README.md
```


---

## How to Run the Project
1. Download or clone the repository.
2. Open the project folder.
3. Open **index.html** in any web browser.
4. Enter numbers separated by commas.
5. Click **Start Sort** to visualize the recursion tree.

No external libraries or installations are required.

---

## Example Input 
56, 29, 35, 42, 15, 41, 75, 21


The visualization will:
- Split the array recursively
- Display the recursion tree
- Merge the subarrays step-by-step
- Show the final sorted array

---

## Learning Objectives
This project helps in understanding:
- Merge Sort algorithm  
- Divide and Conquer technique  
- Recursion tree representation  
- Algorithm visualization concepts  
- Time complexity behavior (n log n)

---

## Future Improvements
- Step-by-step manual execution mode  
- Visualization for other sorting algorithms (Quick Sort, Heap Sort)  
- Export animation steps  
- Add pseudocode panel alongside visualization  
- Support larger arrays with zoom functionality

---

## Author
**Vaishnavi**  
B.Tech Computer Science Student
