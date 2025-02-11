# AppliedArtificialIntelligence_GeneticAlgorithm_BTH
Genetic Algorithm and Data Science – University Project

## 📌 Overview
This repository contains our implementation of various AI and data science techniques for the *Applied Artificial Intelligence* course at **Blekinge Institute of Technology**. The project explores **Genetic Algorithms (GAs)** and **Machine Learning** models across four key tasks.

## 📂 Project Structure
- **Task 1: Traveling Salesman Problem (TSP) with GA**  
  - Implemented a Genetic Algorithm (GA) to find the optimal route for the TSP.  
  - Tested different **population sizes** (10, 20, 50, 100) and **mutation rates** (0.9, 0.6, 0.3, 0.1).  
  - Analyzed the effect of parameters on optimization performance.

- **Task 2: Single-Objective Optimization with GA**  
  - Implemented a **custom fitness function** and integrated it into a GA framework.
  - Ensured proper optimization and correctness of results.

- **Task 3: Maze Solving using GA**  
  - Implemented a GA to find the shortest path in a **2D maze** for a mouse.  
  - Modeled the maze as a **matrix**, where paths have a value of 1 and obstacles are assigned a high value (e.g., 1000).

- **Task 4: Data Science & Machine Learning Models**  
  - **Generated synthetic data** using NumPy.
  - Implemented and compared three models for **regression and prediction**:
    - **Linear regression**
    - **Polynomial regression (degree 2)**
    - **Neural network (3 layers: input, hidden (6 nodes), and output)**
  - Evaluated models using **Mean Squared Error (MSE)** and visualized results.

## 🛠 Technologies Used
- **Python** (Primary language)
- **NumPy, Scikit-learn** (Data Science & Machine Learning)
- **Keras / TensorFlow** (Neural Networks)
- **Jupyter Notebook / .py scripts** (Implementation)

## 🚀 Installation & Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/genetic-algorithm-project.git
   cd genetic-algorithm-project
   ```
2. Install required dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run specific tasks:
   - **TSP GA:** `python task1_tsp.py`
   - **Optimization GA:** `python task2_optimization.py`
   - **Maze GA:** `python task3_maze.py`
   - **ML Models:** `python task4_ml_models.py`

## 📊 Results & Analysis
Each task includes a report analyzing the results and discussing insights into Genetic Algorithms and Machine Learning models.

## 👥 Authors
This project was developed by **[Your Name]** and **[Team Members]** for the *Applied Artificial Intelligence* course at **Blekinge Institute of Technology**.

## 📄 License
This project is licensed under the **MIT License** – feel free to use and modify it while giving proper credit.

---
🔍 *For more details, check out the individual task files!*

