# T20 Scheduler – Machine Learning Integrated Scheduling Project

This project creates an optimized **T20 cricket schedule** using:
- Distance calculations
- KMeans clustering
- Travel optimization
- HHO (Harris Hawks Optimization) algorithm
- Machine learning prediction model

The main goal is to generate a **fixture/schedule with minimum travel distance** while also simulating match outcomes using a prediction model.

---

## 🔍 Project Description

This is a machine-learning–integrated scheduling system designed to reduce the total travel distance between cricket stadiums.  
It works by:

1. **Calculating latitude & longitude** for each stadium  
2. **Computing travel distance** using distance formulas  
3. **Applying clustering (KMeans)** to group nearby teams  
4. **Using the HHO algorithm** for optimization  
5. **Running a ML prediction model** to simulate match results  
6. **Generating a final schedule, points table, and champion**

Everything is integrated into one final unified script.

---

## 📂 Datasets

A very small dataset was used to train the ML prediction model:

- `2022_teams_played.csv` (minimal dataset)

⚠️ **Note**:  
Better results can be achieved by using **more features and a larger dataset** for training.

The scheduling dataset contains **10 teams split into 2 groups**, such as:

- `Group_A_Teams`
- `Group_B_Teams`

You are free to replace these datasets with your own for custom scheduling.

---

## 🧠 Machine Learning Model

The ML prediction model takes team names and runs a simulated match result.  
It is not the main focus of the project — scheduling optimization is the main goal —  
but the model is integrated to complete the tournament simulation.

---

## 📊 Output of the Project

The project generates:
- Full league schedule  
- Travel-optimized fixture list  
- Points table  
- Finalists  
- Final **champion** predicted by the ML model  
- Folium map visualizing stadium locations  



