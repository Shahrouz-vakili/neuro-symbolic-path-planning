# Neuro-Symbolic Path Planning: PRM vs. CNN

This repository contains the dataset, code, and results for the paper **"An Experimental Report on Comparative Evaluation of Probabilistic Roadmap and Convolutional Neural Network Approaches for Autonomous Path Planning."** The project evaluates the performance of Probabilistic Roadmaps (PRM) and a Neuro-Symbolic CNN-based path-planning approach in simulated autonomous navigation tasks.

---

## **Overview**
Path planning is a crucial aspect of autonomous navigation. This project compares:
1. **PRM**: A static graph-based approach for path planning.
2. **Neuro-Symbolic CNN**: A hybrid model combining Convolutional Neural Networks (CNNs) for adaptability with symbolic safety rules for enhanced obstacle avoidance.

The results demonstrate the advantages of the Neuro-Symbolic approach in dynamic environments, achieving better safety and computational efficiency.

---

## **Repository Structure**
- **`data/`**: Contains input data files:
  - `lidar_sensor_data.mat`: Simulated Lidar sensor readings.
  - `complex_map.mat`: Binary occupancy map used for simulations.
- **`code/`**: MATLAB scripts for experiments:
  - `prm_path_planning.m`: PRM-based path planning.
  - `neuro_symbolic_cnn.m`: Neuro-Symbolic CNN framework.
  - `evaluate_results.m`: Code for computing metrics (path length, computation time, obstacle avoidance).
- **`results/`**: Figures and tables from the experiments:
  - `prm_graph.jpg`: PRM graph visualizations.
  - `cnn_path.jpg`: Neuro-Symbolic CNN path visualizations.
  - `comparison_table.csv`: Results in tabular format.
- **`README.md`**: Repository documentation.
- **`LICENSE`**: Licensing information for data/code usage.

---

## **Usage**
### **Prerequisites**
- MATLAB (R2022b or later) with the following toolboxes:
  - Robotics System Toolbox
  - Deep Learning Toolbox

### **Running the Code**
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/neuro-symbolic-path-planning.git
   cd neuro-symbolic-path-planning
