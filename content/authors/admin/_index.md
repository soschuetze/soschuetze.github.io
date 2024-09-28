---
# Display name
title: Sinclaire Schuetze

# Full name (for SEO)
first_name: Sinclaire
last_name: Schuetze

# Is this the primary user of the site?
superuser: true

# Highlight the author in author lists? (true/false)
highlight_name: true

# Role/position/tagline
role: Research Fellow

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: Stanford RegLab
    url: https://reglab.stanford.edu/

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: 'mailto:sschuetz@law.stanford.edu'
    label: E-mail Me
  - icon: brands/x
    url: https://twitter.com/soschuetze1
  - icon: brands/github
    url: https://github.com/soschuetze
  - icon: brands/linkedin
    url: https://www.linkedin.com/in/sinclaireschuetze/

interests:
  - Graph Machine Learning
  - Computational Social Science
  - Economic Applications

education:
  - area: MSc Social Data Science
    institution: University of Oxford
    date_start: 2023
    date_end: 2024
    summary: |
      Grade: Distinction (First Class Honours)

      Courses included:
      - Applied Machine Learning
      - Network Analysis
      - Applied Analytical Statistics
      - Data Analytics at Scale

      Thesis on the application of Siamese GNNs to the International Trade Network for the purpose of identifying financial crises. Also invited to Northeastern University London's Networks and Time II Conference for paper that used trade and migration networks to predict links in terrorism networks.
    button:
      text: Read Thesis
      url: uploads/Schuetze_sGNN_TradeNetworks.pdf
  - area: BA Data Science and Economics
    institution: Wellesley College
    date_start: 2019-08-01
    date_end: 2023-05-20
    summary: |
      GPA: 3.94/4.0

      Courses included:
      - Natural Language Processing
      - Machine Learning
      - Multivariate Data Analysis
      - Applied Data Analysis and Statistical Inference

      Thesis on fine-tuning DistilBERT for classifying forms of advocacy within 21 million tweets related to the Black Lives Matter movement. Achieved F1-score of 0.89, which was a 25% increase from traditional NLP methods. Identified shifting trends within the movement, including a increased emphasis on disruptive rather than within-the-system forms of action. 
    button:
      text: Read Thesis
      url: uploads/WCTC_2023_SchuetzeSinclaire_InsightsIntoANe.pdf
work:
  - position: Research Fellow
    company_name: Stanford RegLab
    company_url: 'https://reglab.stanford.edu/'
    company_logo: ''
    date_start: 2024-09-03
    date_end: 2025-09-02
    summary: |3-
      Responsibilities include:
      - Training PyTorch Geometric GraphSAGE GNN to classify partnerships’ risk of noncompliance using networks of taxpayer structures
      - Implementing self-supervision tasks on heterogeneous graph such as link prediction to  improve performance of GNN
      - Analyze model predictions to ensure businesses identified provide greatest opportunity for increased revenue
      - Utilize current ML and accounting research to guide decision making to improve the IRS’s audit selection process
  - position: Data Science Intern
    company_name: Mercury Insurance
    company_url: 'https://www.mercuryinsurance.com/'
    company_logo: ''
    date_start: 2023-06-08
    date_end: 2023-08-15
    summary: |2-
      Responsibilities include:
      - Analyzed XGBoost auto underwriting model to identify key areas for improvement, increasing predicted profit from model by 28% 
      - Created 15 new features using SQL queries, resulting in a 23% increase in predictive accuracy for high-risk policies
      - Optimized models using SHAP and XGBoost feature importances, maintaining performance after removing 60 features
      - Built R-shiny dashboard with lift charts and profit improvement visualizations, facilitating decision making by stakeholders
  - position: Software Engineering Intern
    company_name: JP Morgan Chase & Co.
    company_url: 'https://www.jpmorgan.com/global'
    company_logo: ''
    date_start: 2021-06-06
    date_end: 2022-08-12
    summary: |
      Responsibilities include:
      - Implemented contract testing framework, allowing for scalable testing of all microservice applications within data pipelines
      - Developed 2 Rest APIs and updated functionality of existing APIs responsible for handling $2 trillion in consumer payments daily
      - Built a new microservice to maintain logs using Java, Spring Boot, and Kafka
  - position: Software Engineering Intern
    company_name: JP Morgan Chase & Co.
    company_url: 'https://www.jpmorgan.com/global'
    company_logo: ''
    date_start: 2021-06-07
    date_end: 2022-08-13
    summary: |
      Responsibilities include:
      - Automated 6 data pipelines using ETL framework, ingesting and transforming consumer data using Spark SQL and JPMC libraries
      - Tested pipeline transformations and implemented step definitions using Cucumber files and deploying to DPL server

# Skills
# Add your own SVG icons to `assets/media/icons/`
skills:
  - name: Languages
    items:
      - name: Python
      - name: SQL
      - name: Java
      - name: R
      - name: Stata
  - name: Frameworks
    items: 
      - name: Machine Learning
      - name: Deep Learning
      - name: NLP
      - name: Graph ML
      - name: Hypothesis Testing
      - name: Statistical Inference
      - name: Multi-level Modeling
      - name: Data Visualization
  - name: Tools
    items: 
      - name: TensorFlow
      - name: PyTorch
      - name: PyTorch Geometric
      - name: Spark
      - name: NumPy
      - name: Scikit-Learn
      - name: Git
      - name: Networkx

languages:
  - name: English
    percent: 100
  - name: German
    percent: 60

# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.
awards:
  - title: Neural Networks and Deep Learning
    url: https://www.coursera.org/learn/neural-networks-deep-learning
    date: '2023-11-25'
    awarder: Coursera
    icon: coursera
    summary: |
      I studied the foundational concept of neural networks and deep learning. By the end, I was familiar with the significant technological trends driving the rise of deep learning; build, train, and apply fully connected deep neural networks; implement efficient (vectorized) neural networks; identify key parameters in a neural network’s architecture; and apply deep learning to your own applications.
  - title: Blockchain Fundamentals
    url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
    date: '2023-07-01'
    awarder: edX
    icon: edx
    summary: |
      Learned:
      - Synthesize your own blockchain solutions
      - Gain an in-depth understanding of the specific mechanics of Bitcoin
      - Understand Bitcoin’s real-life applications and learn how to attack and destroy Bitcoin, Ethereum, smart contracts and Dapps, and alternatives to Bitcoin’s Proof-of-Work consensus algorithm
  - title: 'Object-Oriented Programming in R'
    url: https://www.datacamp.com/courses/object-oriented-programming-with-s3-and-r6-in-r
    certificate_url: https://www.datacamp.com
    date: '2023-01-21'
    awarder: datacamp
    icon: datacamp
    summary: |
      Object-oriented programming (OOP) lets you specify relationships between functions and the objects that they can act on, helping you manage complexity in your code. This is an intermediate level course, providing an introduction to OOP, using the S3 and R6 systems. S3 is a great day-to-day R programming tool that simplifies some of the functions that you write. R6 is especially useful for industry-specific analyses, working with web APIs, and building GUIs.
---

## About Me

Sinclaire Schuetze is a Research Fellow at the Stanford RegLab working to optimize the IRS's process of auditing partnerships through graph machine learning. She received her Master's in Social Data Science from the University of Oxford, where she began her focus on graph machine learning through the application to identifying financial crises using trade networks. She aims to continue her work of improving government processes and public policy through the application of advanced data science and machine learning methods.
