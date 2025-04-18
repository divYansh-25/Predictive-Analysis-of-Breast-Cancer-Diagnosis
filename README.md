# Predictive-Analysis-of-Breast-Cancer-Diagnosis

Tumor Type Prediction
Project Overview
This project uses machine learning to predict whether a tumor is malignant or benign based on clinical data features like radius_mean and texture_mean. The model is trained using Logistic Regression, and the results are visualized using Matplotlib.

Features
Logistic Regression model for binary classification

Data preprocessing and visualization using Matplotlib

Histogram of tumor radius distribution

Scatter plot showing tumor separation by class

Interactive user input for prediction

Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/tumor-type-prediction
Navigate to the project folder:

bash
Copy
Edit
cd tumor-type-prediction
Install required dependencies:

bash
Copy
Edit
pip install pandas matplotlib scikit-learn
Usage
Run the Python script:

bash
Copy
Edit
python tumor_prediction.py
Enter the required values when prompted:

yaml
Copy
Edit
Enter radius_mean: 14.5  
Enter texture_mean: 20.0  
Example output:

nginx
Copy
Edit
Benign
Dataset
The dataset used is Breast Cancer Wisconsin (Diagnostic) Data, containing clinical measurements of tumors, such as:

radius_mean: Mean radius of the tumor

texture_mean: Mean texture of the tumor

diagnosis: Tumor classification (M = Malignant, B = Benign)

The dataset was cleaned by removing:

Unnecessary columns like id, Unnamed: 32

Rows with missing data

Visualizations
Histogram: Distribution of tumor sizes (radius_mean)

Scatter Plot: radius_mean vs. texture_mean, colored by diagnosis (Benign/ Malignant)

Contributing
Feel free to fork this repository and submit pull requests to add features or improve the model or visuals.

License
This project is open-source and available under the MIT License.

Credits
Developed by: [Divyansh Yadav]

Libraries Used: pandas, matplotlib, scikit-learn

Dataset Source: Breast Cancer Wisconsin (Diagnostic)

