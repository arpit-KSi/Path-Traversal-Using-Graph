* * *

# 🗺️ Dijkstra Travel Planner

A C++-based travel planner that finds the **fastest or cheapest** route between cities using **Dijkstra's algorithm**.

## 🚀 Features

✅ **Shortest Path Calculation** – Uses Dijkstra's Algorithm to compute the optimal travel route.  
✅ **Multiple Travel Preferences** – Choose between the **fastest** or **cheapest** route.  
✅ **Graph Representation** – Cities and routes are stored as a weighted graph.  
✅ **Custom Input Files** – Supports user-provided city and route data.  
✅ **HTML Report Generation** – Outputs a detailed travel plan in **.html** format.

## 📂 File Structure

- **`Main.cpp`** – Handles user input, file reading, and calls graph functions.
- **`GraphFunctions.h/.cpp`** – Implements Dijkstra's algorithm for shortest path search.
- **`Location.h/.cpp`** – Defines city properties and relationships.
- **`Route.h/.cpp`** – Defines travel routes between locations.
- **`FileOperations.h/.cpp`** – Handles file parsing for cities and routes.
- **`outputGenerator.h/.cpp`** – Generates an HTML report of the computed travel plan.

## 🛠️ Installation & Usage

### **1️⃣ Compile the Code**

```bash
g++ Main.cpp Route.cpp Location.cpp GraphFunctions.cpp FileOperations.cpp outputGenerator.cpp -o planner
```

### **2️⃣ Run the Program**

```bash
./planner cities.txt routes.txt output.html "New York" "Los Angeles" fastest
```

OR use interactive mode and enter filenames manually.

## 📌 Example Input Files

📍 **cities.txt**

```
USA, New York, 40.7128, -74.0060
USA, Los Angeles, 34.0522, -118.2437
...
```

📍 **routes.txt**

```
New York, Los Angeles, plane, 6, 300, direct flight
New York, Chicago, train, 5, 100, layover
...
```

## 🖥️ Output

Generates an **HTML travel plan**, listing the recommended route with distances, travel time, and costs.

## 📜 License

This project is open-source and available under the **MIT License**.

&nbsp;
