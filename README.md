# 🌍 **Small-World Effect in Network Models Using a Road Network Dataset**  

[![Python](https://img.shields.io/badge/Python-3.8-blue.svg)](https://www.python.org/) [![Network Science](https://img.shields.io/badge/Network%20Analysis-Gephi-green)](https://gephi.org/) [![Complex Networks](https://img.shields.io/badge/Complex%20Networks-Analysis-orange)]  

# 📌 Project Overview
This study critically examines Stanley Milgram’s small-world experiment and investigates the small-world effect in different network models using a real-world road network dataset. The project applies network science principles to analyze the structure, connectivity, and properties of random networks, scale-free networks (Barabasi-Albert model), and small-world networks (Watts-Strogatz model) in comparison to real road networks.

# 🔹 Key Focus Areas:
✔ Milgram’s Experiment & Six Degrees of Separation
✔ Analysis of Road Networks as Scale-Free Models
✔ Comparison: Random Poisson vs. Barabasi-Albert Scale-Free Networks
✔ Graph Metrics: Degree Distribution, Betweenness Centrality, Clustering Coefficient
✔ Network Visualization & Data Analysis Using Gephi


## 📊 **Dataset & Methodology**  
### **Dataset:**  
The **Chesapeake Road Network Dataset** was sourced from [Network Repository](https://networkrepository.com). It represents **real-world road connections**, where nodes are **intersections** and edges are **road segments**.

### **Metrics Analyzed:**  
| Metric | Description |
|--------|------------|
| **Degree Distribution** | Measures connectivity of nodes in the network |
| **Clustering Coefficient** | Evaluates the likelihood of forming clusters |
| **Average Path Length** | Determines efficiency of information flow |
| **Betweenness Centrality** | Identifies influential nodes that act as bridges |
| **Harmonic Closeness Centrality** | Measures how efficiently a node can access the network |


---

## 📁 **Project Structure**  
```
📂 data/                # Road Network Dataset (Gephi-compatible)
📂 analysis/            # Python scripts for data preprocessing & network analysis
📂 models/              # Random, Scale-Free, and Small-World Network Models
📂 visualization/       # Graph analysis and visualizations (Gephi files)
├── README.md          # Project Documentation
├── network_analysis.py # Python script for graph calculations
```

---

## 💻 **Installation & Usage**  
1️⃣ Clone the repository  
```sh
git clone https://github.com/Navabhargav/Small-World-Networks.git  
cd Small-World-Networks  
```  
2️⃣ Install required dependencies  
```sh
pip install networkx pandas matplotlib gephi  
```  
3️⃣ Run the network analysis script  
```sh
python network_analysis.py  
```  

---

## 🖥️ **Results & Key Findings**  
✔ The **road network exhibits small-world properties** with **high clustering and short average path lengths**.  
✔ The **degree distribution follows a power-law**, indicating a **scale-free network**.  
✔ **Key intersections act as hubs**, demonstrating **Barabasi’s preferential attachment principle**.  
✔ **Network robustness**: Scale-free networks show resilience to **random failures** but are **vulnerable to targeted attacks**.  
✔ **Betweenness Centrality** highlights **critical nodes** that play a major role in connectivity.  

---

## 📊 **Technologies Used**  
| **Category** | **Technologies** |
|-------------|-----------------|
| **Languages** | Python, R |
| **Network Analysis** | NetworkX, Gephi |
| **Data Processing** | Pandas, NumPy |
| **Visualization** | Matplotlib, Gephi Graphs |
| **Graph Metrics** | Degree Distribution, Clustering Coefficient, Betweenness Centrality |

---

## 📚 **References**  
- **Milgram, S. (1967)** - The Small-World Problem. *Psychology Today*  
- **Barabási, A. & Albert, R. (1999)** - Emergence of Scaling in Random Networks. *Science*  
- **Watts, D.J. & Strogatz, S.H. (1998)** - Collective Dynamics of ‘Small-World’ Networks. *Nature*  
- **Newman, M. (2018)** - Networks: An Introduction. *Oxford University Press*  
- **Gephi Documentation** - [https://gephi.org](https://gephi.org)  

---

## 🤝 **Contributors**  
👤 **Nava Bhargav Gedda**  
📩 [navabhargavg@gmail.com](mailto:navabhargavg@gmail.com)  
🔗 [LinkedIn](https://linkedin.com/in/nava-bhargav-gedda-4a4a30151) | 🌐 [GitHub](https://github.com/Navabhargav)  

👤 **Kaviya Thirumal**  
🔗 [LinkedIn](https://www.linkedin.com/in/pon-ananth-veppalodai-senthurpandi-b5016262/)

👤 **Pon Ananth Veppalodai Senthurapandi**  
🔗 [LinkedIn](https://www.linkedin.com/in/pon-ananth-veppalodai-senthurpandi-b5016262/)

---

⭐ **Like this project?** Star it on GitHub & share it with your network! 🚀  

---
