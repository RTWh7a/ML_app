# ML_app
🚀 Building for Speed, Planning for Scale: My New AutoML Model App
When you're starting a machine learning project, writing repetitive boilerplate code to test dozens of baseline models one by one is a massive time sink. I wanted to solve that bottleneck.

I built an interactive Automated Machine Learning (AutoML) Web Application using Streamlit and LazyPredict that completely streamlines the initial phases of a data science pipeline.  
PY

With this tool, you simply drop in a dataset, and the app handles the heavy lifting—instantly training and comparing up to 30 classification models simultaneously.  
PY

📊 What the App Does Right Now:
Instant Multi-Model Training: Automatically trains over two dozen algorithms in a single execution phase, saving hours of manual coding.  
PY

Dynamic Parameter Control: Integrated sidebar sliders to adjust train/test split ratios and set random_state seeds on the fly for complete experiment reproducibility.  
PY

Clean Performance Visualizations: Generates comprehensive summary dataframes and scaled Seaborn horizontal bar charts to visually contrast accuracy, F1-score, and ROC AUC metrics instantly.  
PY

🛠️ Framing the Gaps: What’s Next on the Roadmap
Building a great MVP (Minimum Viable Product) is just step one. An engineer's job is to look at their code, find the limitations, and plan the next iteration. Here are the gaps I’m actively working to fill in version 2.0:

Dynamic Target Selection: Moving away from hardcoded final-column targets to let users select any column as the label via a dynamic dropdown menu.

Full Regression Task Support: Expanding the architecture beyond classification tasks to seamlessly handle continuous numerical targets (like housing prices or financial forecasting).

Advanced Data Preprocessing & Cleaning: Integrating automated missing value imputation, outlier detection, and categorical encoding pipelines directly into the UI.

Model Export & Deployment: Adding a feature to let users download the top-performing model as a .pkl or .joblib file for immediate deployment.

A huge thanks to everyone who has given me feedback on this so far! The code is hosted in HypareParameter.py. I’d love to know: what features do you prioritize most when testing baseline models?  
PY
