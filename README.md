# 🗺️ Random Shortest Path Generator with NetworkX, Folium, and OSMnx

This Python project generates **random origin-destination points** within a city boundary and calculates the **shortest path** between them using OpenStreetMap data. It visualizes the path on an interactive map using **Folium**.

---

## 🚀 Features

- Generates a **random shortest path** in a selected city.
- Uses real-world road network data from OpenStreetMap via **OSMnx**.
- Computes the path using **NetworkX shortest path algorithms**.
- Renders an **interactive map** with markers and the route using **Folium**.

---

## 🧰 Libraries Used

- [`osmnx`](https://github.com/gboeing/osmnx) – download and manipulate street network data
- [`networkx`](https://networkx.org/) – graph analysis and shortest path calculation
- [`folium`](https://python-visualization.github.io/folium/) – map visualization

---

## 🏗️ Installation

Make sure you have Python 3.7 or later installed.

```bash
git clone https://github.com/yourusername/random-shortest-path.git
cd random-shortest-path
pip install -r requirements.txt
