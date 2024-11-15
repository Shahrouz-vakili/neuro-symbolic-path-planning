# Neuro-Symbolic Path Planning: PRM vs. CNN

This repository contains the dataset, code, and results for the comparative evaluation of Probabilistic Roadmaps (PRM) and a Neuro-Symbolic Convolutional Neural Network (CNN) approach for autonomous path planning. This study explores the integration of CNN adaptability with symbolic safety rules, showcasing improvements in safety, adaptability, and computational efficiency over traditional PRM methods.

---

## **Project Summary**
- **Objective**: To evaluate the performance of PRM and Neuro-Symbolic CNN in simulated autonomous navigation tasks.
- **Key Features**:
  - Combines the adaptability of CNNs with symbolic safety rules.
  - Conducted in MATLAB simulation environments with binary occupancy maps.
  - Assesses metrics like path length, computation time, and obstacle avoidance efficiency.

---

## **Repository Structure**
- **`data/`**: Datasets used in the simulations:
  - `complex_map.mat`: Binary occupancy map for the environment.
  - `lidar_sensor_data.mat`: Simulated Lidar sensor readings.
- **`code/`**: MATLAB scripts for experiments:
  - `prm_path_planning.m`: Implements PRM-based path planning.
  - `neuro_symbolic_cnn.m`: Neuro-Symbolic CNN framework.
  - `evaluate_results.m`: Computes performance metrics.
- **`results/`**: Output figures and performance comparison tables.
  - `prm_graph.jpg`: Visualization of PRM paths.
  - `cnn_path.jpg`: Visualization of CNN paths.
  - `comparison_table.csv`: Detailed performance metrics.
- **`README.md`**: Documentation for the repository.
- **`LICENSE`**: License file for usage rights.

---

## **Installation and Usage**
### **Requirements**
- MATLAB (R2022b or later) with:
  - Robotics System Toolbox
  - Deep Learning Toolbox

### **Steps to Run**
1. Clone this repository:
   ```bash
   git clone https://github.com/Shahrouz-vakili/neuro-symbolic-path-planning.git
   cd neuro-symbolic-path-planning
