# Covid-19

<h2>COVID-19 Test Prediction using Machine Learning</h2>

<h3>📋 Brief description and context</h3>
<p>
As part of an applied data science initiative, this project focuses on predicting <strong>SARS-CoV-2 test results</strong> based on patients’ hematological and biochemical data. 
The aim was to explore how classical machine learning algorithms can support early detection of COVID-19 by analyzing blood test indicators.
<br><br>
The notebook walks through a complete end-to-end workflow: from data cleaning and preprocessing, to feature engineering, model comparison, and evaluation. 
By applying algorithms such as <strong>Random Forests</strong> and <strong>Support Vector Machines (SVM)</strong>, the project demonstrates how different preprocessing techniques affect classification performance.
</p>

<h3>🏆 Achievements</h3>
<ul>
  <li><strong>Data preprocessing pipeline:</strong> Cleaned and normalized real patient data to handle missing values and categorical variables.</li>
  <li><strong>Feature engineering:</strong> Generated polynomial interactions and applied <code>SelectKBest</code> to identify the top predictive features.</li>
  <li><strong>Model comparison:</strong> Trained and evaluated multiple classifiers, including Random Forest and SVM, to determine the most effective approach.</li>
  <li><strong>Hyperparameter optimization:</strong> Integrated <code>GridSearchCV</code> and <code>RandomizedSearchCV</code> to fine-tune model performance.</li>
  <li><strong>Learning curve analysis:</strong> Visualized model generalization capacity and overfitting tendencies using <code>learning_curve</code>.</li>
</ul>

<h3>🎯 Responsibilities</h3>
<ul>
  <li><strong>Exploratory data analysis (EDA):</strong> Examined feature distributions, correlations, and outlier patterns to inform preprocessing choices.</li>
  <li><strong>Data transformation:</strong> Implemented polynomial feature expansion, feature selection, and standardization to enhance model performance.</li>
  <li><strong>Model development:</strong> Built classification pipelines combining preprocessing and estimator steps for reproducibility.</li>
  <li><strong>Model evaluation:</strong> Used confusion matrices, classification reports, and F1-scores to assess predictive accuracy.</li>
  <li><strong>Visualization and reporting:</strong> Produced clear visualizations to interpret learning behavior and model robustness.</li>
</ul>

<h3>🛠️ Technology stack</h3>
<ul>
  <li><strong>Programming language:</strong> Python</li>
  <li><strong>Libraries:</strong>
    <ul>
      <li>Scikit-learn – for preprocessing, model training, and evaluation</li>
      <li>Pandas & NumPy – for data handling and feature engineering</li>
      <li>Matplotlib – for performance and learning curve visualization</li>
    </ul>
  </li>
  <li><strong>Environment:</strong> Jupyter Notebook</li>
</ul>

<h3>🔍 Sample results and insights</h3>
<ul>
  <li>Random Forest achieved strong classification performance with high recall on positive COVID-19 cases.</li>
  <li>SVM models benefited significantly from feature scaling and polynomial feature transformations.</li>
  <li>Feature selection improved interpretability by isolating the most medically relevant indicators.</li>
</ul>

<h3>🧩 Key learnings</h3>
<p>
This project highlights how classical machine learning techniques can provide valuable decision-support tools in medical diagnostics. 
By combining rigorous preprocessing with robust model evaluation, the approach demonstrates how interpretable ML models can complement clinical testing strategies.
</p>

<h3>📘 Repository contents</h3>
<ul>
  <li><strong>covid-19.ipynb</strong> – complete code, from data preprocessing to model evaluation.</li>
  <li>Generated plots and evaluation metrics.</li>
</ul>

      Thank you for your patience.
    </footer>
  </div>
</div>
