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
g++ Main.cpp Route.cpp Location.cpp -o planner
```

### **2️⃣ Run the Program**

```bash
./planner
```

## 📌 Example Input Files

📍 **cities.csv**

```
Afghanistan	Kabul	34.4667	69.1833
Albania	Tirane	41.3	19.8167
Algeria	Algiers	36.7	3.13333
American Samoa	Pago Pago	-14.2667	-170.717
...
```

📍 **routes.csv**

```
Abu Dhabi,Canberra (Use Sydney),plane,24,1339,"Qatar Airways, Thai Airways, Jetstar Airways, 2 stops, Momondo.com"
Abu Dhabi,Lima,plane,30,1967,"KLM Airways, 1 stop, Momondo.com"
Abu Dhabi,London,plane,10,666,"Turkish Airlines, 1 stop, Momondo.com"
...
```

## 🖥️ Output

Provide an **ouput.html**, file and you will get all the listing the with your desired conditions.

## 📜 License

This project is open-source and available under the **MIT License**.

&nbsp;
