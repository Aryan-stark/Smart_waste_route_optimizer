# Smart_waste_route_optimizer
A real-time waste management system that combines **C++ DSA**, **Machine Learning**, and **Interactive Dashboards** to optimize  waste collection routes.
## 🔧 Key Features

- 📍 **Dynamic Route Planning** using Dijkstra’s Algorithm (C++)
- 🧠 **AI/ML-Based Overflow Prediction** using Python
- 📊 **Real-Time Dashboard** with map visualization (Plotly Dash)
- 🚛 **Animated Vehicle Routing** to simulate bin collection
- ♻️ **Overflow Detection** to prioritize critical bins
- 📈 Simulated bin filling and real-time re-routing

---

## 📌 Tech Stack

| Tech            | Purpose                          |
|-----------------|----------------------------------|
| C++             | Graph, Dijkstra’s Algorithm      |
| Python          | ML model, simulation, dashboard  |
| Scikit-learn    | ML model for bin overflow        |
| Pandas/NumPy    | Data processing & simulation     |
| Plotly Dash     | Dashboard & map visualization    |

🚀 How It Works

1. **Bins fill up over time** in a simulated environment.
2. A **Machine Learning model predicts** which bins are likely to overflow soon.
3. The C++ backend runs **Dijkstra’s algorithm** to generate the optimal path for waste collection.
4. The **Python dashboard visualizes** all bin locations, overflow statuses, and the truck route in real-time.

