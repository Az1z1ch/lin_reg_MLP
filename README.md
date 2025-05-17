**Project Description:**  
This project demonstrates a Multilayer Perceptron (MLP) implemented in PyTorch for regression analysis on student performance data. The model predicts the "Performance Index" using features like study hours, previous scores, extracurricular activities, and sleep hours.  

**Key Steps:**  
- **Data Preprocessing**: Handles duplicates, scales numerical features, and encodes categorical variables.  
- **Neural Network**: A 4-layer MLP with ReLU activation, trained using Adam optimizer and MSE loss.  
- **GPU Support**: Utilizes CUDA if available for accelerated training.  
- **Evaluation Metrics**: Achieves high performance (R²: 0.988, MAE: 1.686) on test data.  

**Tech Stack**: Python, PyTorch, pandas, scikit-learn.  
**Use Case**: Ideal for educational analytics or regression tasks with tabular data.  

**Results**: The model effectively captures patterns in student performance, showcasing the flexibility of MLPs for regression problems.
