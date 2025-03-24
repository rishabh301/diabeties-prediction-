<!DOCTYPE html>
<html lang="en">
<head>
    
</head>
<body>
    <div class="container">
        <h1>🏥 Diabetes Prediction System</h1>
        <h2>📌 Project Overview</h2>
        <p>This project is a <strong>Diabetes Prediction System</strong> that uses Machine Learning to analyze patient data and predict whether an individual has diabetes based on various health parameters.</p>
        <h2>🎯 Features</h2>
        <ul>
            <li>Accepts key medical attributes as input.</li>
            <li>Uses a trained machine learning model for prediction.</li>
            <li>Provides instant diagnosis results.</li>
            <li>Scales input data for better model accuracy.</li>
        </ul>
        <h2>🚀 Technologies Used</h2>
        <ul>
            <li><strong>Programming Language:</strong> Python 🐍</li>
            <li><strong>Libraries:</strong> NumPy, Pandas, Scikit-Learn</li>
            <li><strong>Framework:</strong> Flask (For deployment)</li>
        </ul>
        <h2>📂 Dataset Information</h2>
        <p><strong>Source:</strong> Pima Indians Diabetes Dataset</p>
        <p><strong>Attributes:</strong></p>
        <ul>
            <li>Pregnancies</li>
            <li>Glucose Level</li>
            <li>Blood Pressure</li>
            <li>Skin Thickness</li>
            <li>Insulin Level</li>
            <li>BMI (Body Mass Index)</li>
            <li>Diabetes Pedigree Function</li>
            <li>Age</li>
        </ul>
        <p><strong>Target:</strong> 0 (No Diabetes) or 1 (Diabetes)</p>
        <h2>📊 Model Workflow</h2>
        <ul>
            <li>Data Preprocessing: Standardization and missing value handling.</li>
            <li>Feature Selection: Selecting the most important attributes.</li>
            <li>Model Training: Using algorithms like Logistic Regression, Decision Tree, and Random Forest.</li>
            <li>Evaluation: Measuring accuracy using Precision, Recall, and F1-Score.</li>
            <li>Deployment: Making the model available via Flask API.</li>
        </ul>
        <h2>🔥 How to Use</h2>
        <h3>Clone the Repository:</h3>
        <pre><code>git clone https://github.com/RishabhSharma0/Diabetes-Prediction.git
cd Diabetes-Prediction</code></pre>
        <h3>Install Dependencies:</h3>
        <pre><code>pip install -r requirements.txt</code></pre>
        <h3>Run the Prediction Script:</h3>
        <pre><code>python main.py</code></pre>
        <h3>Start the Web App:</h3>
        <pre><code>python app.py</code></pre>
        <h3>📸 Example Prediction Output:</h3>
        <pre><code>input_data = (0,137,40,35,168,43.1,2.288,33)
input_data_as_numpy_array = np.asarray(input_data)
input_data_reshape = input_data_as_numpy_array.reshape(1,-1)
std_data = scalar.transform(input_data_reshape)
prediction = classifier.predict(std_data)

if prediction[0] == 0:
    print('The person does NOT have diabetes')
else:
    print('The person HAS diabetes')</code></pre>
        <h2>📬 Connect with Me</h2>
        <p>Let's connect and discuss more! 🚀</p>
        <a href="https://github.com/rishabh301" class="btn">🌟 Star This Project</a>
    </div>
</body>
</html>
