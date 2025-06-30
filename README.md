# Biomechanical-Effects-of-an-Ankle-Brace-on-hip-and-knee Joint

## Gait Kinematics Prediction with Multivariate Regression

This project explores the **biomechanical effects of an ankle brace** on the right leg and how it influences **knee and hip joint kinematics** during human gait. Using multivariate regression techniques, the project predicts joint angles based on processed gait data.

## Objective
To build a regression model that can accurately **predict knee and hip joint angles** based on gait cycle data, specifically evaluating the influence of an ankle brace.

## Technologies & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn (`MultiOutputRegressor`)

## Dataset
The dataset contains gait cycles collected under different conditions with and without an **ankle brace on the right leg**. It includes joint angle measurements for the knee and hip over time.

# Key Steps

### 1. Data Preprocessing
- Cleaned raw gait cycle data
- Created pivot tables to organize data by condition and cycle
- Engineered features for joint angle analysis

### 2. Modeling
- Built **Multivariate Regression** models using `MultiOutputRegressor`
- Trained models on features from gait cycles to predict:
  - **Knee flexion/extension**
  - **Hip flexion/extension**

### 3. Evaluation & Visualization
- Evaluated prediction performance using Mean Square Error metrics
- Visualized **actual vs predicted joint angles** for interpretability

## 📈 Sample Results
- Clear trend shifts were observed when ankle braces were used
- Visuals show close alignment between predicted and actual joint angle curves

## 📁 File Structure
- `Biomechanical Effects of an Ankle Brace on hip and knee.ipynb`: Main Jupyter notebook with complete pipeline
- `README.md`: Project overview and documentation

## 🚀 How to Run
1. Clone the repository
2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
