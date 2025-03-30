<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Ensemble Techniques in Machine Learning</title>
</head>
<body>

  <h1>Ensemble Techniques in Machine Learning</h1>

  <p>This repository provides Python implementations of various ensemble learning methods, including Bagging, Random Forest, AdaBoost, Gradient Boosting, and XGBoost. These techniques are widely used to improve prediction performance by combining multiple models.</p>

  <h2>Table of Contents</h2>
  <ul>
    <li><a href="#overview">Overview</a></li>
    <li><a href="#techniques">Techniques Covered</a></li>
    <li><a href="#dataset">Dataset</a></li>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#dependencies">Dependencies</a></li>
    <li><a href="#project-structure">Project Structure</a></li>
    <li><a href="#license">License</a></li>
  </ul>

  <h2 id="overview">Overview</h2>
  <p>Ensemble learning improves model accuracy and generalization by combining multiple weaker models into a stronger one. This repository demonstrates how these ensemble techniques work using clear examples, datasets, and visualizations.</p>

  <h2 id="techniques">Techniques Covered</h2>
  <ul>
    <li><strong>Bagging</strong>: Reduces variance by averaging predictions over multiple models trained on different data subsets.</li>
    <li><strong>Random Forest</strong>: Uses an ensemble of decision trees with random feature selection to reduce overfitting.</li>
    <li><strong>AdaBoost</strong>: Adjusts weights iteratively to focus on difficult-to-classify samples.</li>
    <li><strong>Gradient Boosting</strong>: Optimizes a loss function over a series of models, each correcting the previous one's errors.</li>
    <li><strong>XGBoost</strong>: A highly efficient and scalable implementation of gradient boosting with regularization and parallelization.</li>
  </ul>

  <h2 id="dataset">Dataset</h2>
  <p>The dataset used in this project is the <strong>Loan Prediction dataset</strong> from Kaggle. You can import the dataset using the <code>kagglehub</code> library:</p>

  <pre>
import kagglehub

# Download latest version
path = kagglehub.dataset_download("ninzaami/loan-predication")

print("Path to dataset files:", path)
  </pre>

  <h2 id="installation">Installation</h2>
  <pre>
git clone https://github.com/premkumarkora/EnsembleTechniques.git
cd EnsembleTechniques
  </pre>

  <h2 id="usage">Usage</h2>
  <p>Each script is self-contained. Run any script using:</p>
  <pre>
python Random_Forest.py
  </pre>

  <h2 id="dependencies">Dependencies</h2>
  <ul>
    <li>Python 3.x</li>
    <li>pandas</li>
    <li>numpy</li>
    <li>matplotlib</li>
    <li>seaborn</li>
    <li>scikit-learn</li>
    <li>xgboost</li>
    <li>kagglehub</li>
  </ul>

  <p>You can install all required libraries using:</p>
  <pre>
pip install -r requirements.txt
  </pre>

  <h2 id="project-structure">Project Structure</h2>
  <pre>
EnsembleTechniques/
├── Bagging.py
├── Random_Forest.py
├── AdaBoost.py
├── Gradient_Boosting.py
├── XGBoost.py
├── README.md
  </pre>

  <h2 id="license">License</h2>
  <p>This project is licensed under the MIT License. See the LICENSE file for details.</p>

</body>
</html>
