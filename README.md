<h1>COVID-19 Test Prediction using Machine Learning</h1>

<h2>📋 Brief description and context</h2>

<p>
As part of a data science research initiative, I developed a machine learning model to predict 
<strong>SARS-CoV-2 test results</strong> based on <strong>patients’ hematological and biochemical parameters</strong>.<br>
The project explores how classical machine learning methods can assist in <strong>early COVID-19 diagnosis</strong> 
by identifying meaningful correlations in clinical data.
</p>

<p>
The notebook presents a complete end-to-end pipeline, including <strong>data preprocessing</strong>, 
<strong>feature engineering</strong>, <strong>model comparison</strong>, and <strong>evaluation</strong>.<br>
By experimenting with algorithms such as <strong>Random Forests</strong> and <strong>Support Vector Machines (SVM)</strong>, 
this work demonstrates how different preprocessing strategies — including polynomial feature expansion and feature selection — 
influence classification accuracy and model robustness.
</p>

<hr>

<h2>🏆 Achievements</h2>
<ul>
  <li><strong>Comprehensive data preprocessing</strong>: Cleaned, encoded, and normalized patient data to handle missing and categorical values.</li>
  <li><strong>Feature engineering and selection</strong>: Applied <code>PolynomialFeatures</code> and <code>SelectKBest</code> to generate and retain the most relevant predictive variables.</li>
  <li><strong>Model pipeline design</strong>: Built reproducible pipelines combining transformation and classification stages for Random Forest and SVM models.</li>
  <li><strong>Model optimization</strong>: Used <code>GridSearchCV</code> and <code>RandomizedSearchCV</code> to fine-tune hyperparameters and improve performance.</li>
  <li><strong>Performance visualization</strong>: Implemented learning curve plots to assess overfitting and generalization behavior across different models.</li>
</ul>

<hr>

<h2>🎯 Responsibilities</h2>

<h3>Data analysis and preparation</h3>
<ul>
  <li>Conducted exploratory data analysis (EDA) to study feature distributions, detect outliers, and assess correlations.</li>
  <li>Encoded categorical variables and normalized numerical features for consistent model input.</li>
  <li>Handled missing values and ensured dataset balance for fair training.</li>
</ul>

<h3>Model development</h3>
<ul>
  <li>Built multiple classification pipelines using <code>RandomForestClassifier</code> and <code>SVC</code> wrapped in <code>make_pipeline</code>.</li>
  <li>Integrated preprocessing steps such as polynomial expansion and feature selection before model training.</li>
  <li>Implemented stratified data splitting to preserve class proportions during training and testing.</li>
</ul>

<h3>Evaluation and insights</h3>
<ul>
  <li>Assessed model performance using confusion matrices, classification reports, and F1-score metrics.</li>
  <li>Visualized learning curves to compare training vs. validation performance.</li>
  <li>Identified the most impactful features contributing to COVID-19 test prediction.</li>
</ul>

<h3>Optimization and experimentation</h3>
<ul>
  <li>Tuned hyperparameters (e.g., tree depth, kernel type, C, gamma) via cross-validation.</li>
  <li>Compared baseline vs. optimized models to quantify gains in precision and recall.</li>
  <li>Evaluated the influence of preprocessing complexity on model interpretability.</li>
</ul>

<hr>

<h2>🛠️ Technology stack</h2>
<ul>
  <li><strong>Programming language:</strong> Python</li>
  <li><strong>Libraries:</strong>
    <ul>
      <li><code>Scikit-learn</code>: For model building, pipelines, and evaluation.</li>
      <li><code>Pandas</code> &amp; <code>NumPy</code>: For data cleaning, manipulation, and feature processing.</li>
      <li><code>Matplotlib</code>: For plotting learning curves and performance metrics.</li>
      <li><code>Seaborn</code>: For exploratory data visualization (optional, used during EDA).</li>
    </ul>
  </li>
</ul>

<hr>

<h2>🔍 Sample model performance metrics</h2>

<table>
  <thead>
    <tr>
      <th>Model</th>
      <th>Accuracy</th>
      <th>Precision</th>
      <th>Recall</th>
      <th>F1-score</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Random Forest</td>
      <td>93.8%</td>
      <td>0.94</td>
      <td>0.92</td>
      <td>0.93</td>
    </tr>
    <tr>
      <td>SVM (Polynomial + Feature Selection)</td>
      <td>91.5%</td>
      <td>0.92</td>
      <td>0.90</td>
      <td>0.91</td>
    </tr>
  </tbody>
</table>

<p><em>Metrics are representative of the test set performance after model tuning and cross-validation.</em></p>

<hr>

<h2>🖥️ Key code snippets</h2>
<p>
Due to the detailed and exploratory nature of the project, all code and visualizations are included in the 
<strong>notebook attached to this repository</strong>.<br>
You can open the notebook to explore the full workflow — from data preprocessing and model training 
to evaluation and performance visualization.
</p>

<hr>
