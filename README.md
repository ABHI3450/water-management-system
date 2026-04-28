# 💧 Smart Water Management System

A desktop-based simulation tool to design and optimize water distribution networks using graph algorithms.

## 🚀 Features

- Add, move, and delete nodes (houses or water sources)
- Connect/disconnect pipelines
- Interactive UI with pan and zoom
- Grid overlay for alignment
- Run simulation to compute optimal connections
- Visual visualization of the network

## 🧠 How It Works

- Nodes → Houses or water sources  
- Edges → Pipelines  

The system uses **Minimum Spanning Tree (Prim’s Algorithm)** to find the most efficient way to connect all nodes.

## 🛠️ Tech Stack

- Python
- PyQt6
- NetworkX
- NumPy
- Matplotlib

## ⚙️ Installation

```bash
git clone <your-repo-link>
cd SmartWaterManagement
pip install -r requirements.txt
python main.py
```
📂 Project Structure
```bash
project/
│── main.py
│── check_and_install.py
│── requirements.txt
│── ui/
│── logic/
│── visualization/
```
🧪 Future Improvements

● Add real-time water flow simulation

● Implement Max Flow algorithms

● Convert to web app

⚠️ Limitations

● No real fluid dynamics (only structure optimization)

● Works best for small networks

📜 License


● MIT License



