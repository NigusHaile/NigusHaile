
<div align="center">

# Hi there, I'm Nigus Bezabh Haile 👋

### AI/ML Engineer | Computer Vision | Medical AI | Deep Learning | Software Engineering

**Building intelligent systems that connect AI research with real-world impact.**

<p align="center">
  <a href="https://github.com/NigusHaile">
    <img src="https://img.shields.io/badge/GitHub-NigusHaile-181717?style=for-the-badge&logo=github" alt="GitHub">
  </a>
  <a href="https://www.linkedin.com/in/nigushaile/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn">
  </a>
  <a href="mailto:n.haile@campus.unimib.it">
    <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

📍 Milan, Italy | 🌍 Originally from Ethiopia

</div>

---

## 👨‍💻 About Me

I hold a BSc in Computer Science and Engineering from Mekelle University, Ethiopia, graduating with a **3.96/4.00 CGPA and ranking in the top 1% of 800+ engineering students**. I bring over four years of experience spanning software engineering, data analytics, and machine learning.

My interests lie at the intersection of **Computer Vision, Medical AI, Deep Learning, Explainable AI, and AI Engineering**. I enjoy designing experiments, comparing model architectures, analyzing model behavior, and translating technical ideas into practical applications.

I believe effective AI development requires more than achieving a high accuracy score. It requires thoughtful evaluation, reliable data pipelines, understanding failure cases, and building systems that are useful beyond a research notebook.

### 🎯 What I Work On

- 🔬 **Computer Vision:** Image classification, CNNs, Vision Transformers, transfer learning, and visual explainability.
- 🏥 **Medical AI:** Retinal OCT classification, medical image analysis, and healthcare decision-support prototypes.
- 🧠 **Machine Learning:** Supervised and unsupervised learning, ensemble methods, statistical analysis, and model evaluation.
- ⚙️ **Efficient AI:** Parameter-efficient fine-tuning, LoRA, hyperparameter optimization, and model comparison.
- 📊 **Data Science:** Exploratory data analysis, feature engineering, clustering, visualization, and interpretable models.
- 💻 **AI Engineering:** Python applications, REST APIs, databases, backend development, and deployment.
- 🌍 **AI for Impact:** Healthcare, environmental applications, cultural heritage digitization, and technology access.

---

## 🧪 Featured Research & AI Projects

### 1 VisionCare AI:  Retinal OCT Disease Classification

**Focus:** Deep learning for retinal imaging and multi-class medical image classification.

VisionCare AI explores deep learning approaches for classifying retinal optical coherence tomography (OCT) scans into four categories:

- Choroidal neovascularization (CNV)
- Diabetic macular edema (DME)
- Drusen
- Normal

**Key contributions and reported results**

- Worked with a dataset of **83,605 OCT scans**.
- Fine-tuned four CNN architectures: VGG16, InceptionV3, ConvNeXt-Tiny, and EfficientNetV2-S.
- Explored soft-voting ensembles and XGBoost stacking.
- Achieved **97.08% accuracy and F1** with the reported ensemble approach.
- Addressed class imbalance using class-weighted loss, weighted sampling, and label smoothing.
- Evaluated per-class F1 scores to examine differences in model performance across categories.
- Used differential learning rates, OneCycleLR, and mixed-precision training.

**Technologies**

`Python` `PyTorch` `CNNs` `Transfer Learning` `XGBoost` `Ensemble Learning`

**Why it matters:** Medical imaging models should be evaluated across disease categories, not only by overall accuracy. This project explores model comparison, class imbalance, and complementary ensemble predictions.

---

### 2. Aerial Scene AI: Land-Use Classification

**Focus:** Computer vision, Vision Transformers, parameter-efficient fine-tuning, and visual explainability.

This project investigates image classification across **21 land-use categories** using 2,100 aerial images from the UC Merced dataset.

**Key contributions and reported results**

- Compared a custom residual-attention CNN, DenseNet-121, and ViT-B/16 adapted using LoRA.
- Achieved **99.05% test accuracy** with ViT-B/16 + LoRA in the reported experiment.
- Evaluated DenseNet-121, which achieved 96.67% accuracy in the reported experiment.
- Used perceptual-hash deduplication and stratified splitting to help reduce data leakage risks.
- Applied Optuna for hyperparameter optimization.
- Used macro-F1 alongside accuracy to evaluate classification performance.
- Applied Grad-CAM to inspect model predictions.
- Built a Streamlit dashboard supporting single-image and batch inference.

**Technologies**

`Python` `PyTorch` `Vision Transformers` `LoRA` `Optuna` `Grad-CAM` `Streamlit`

**Why it matters:** This project explores how parameter-efficient adaptation and careful evaluation can be used for visual recognition tasks, while making model predictions accessible through an interactive application.

---

### 3. MindX AI: Data Analysis & Explainable AI

**Focus:** Unsupervised learning, Bayesian networks, and interpretable machine learning.

This project explores patterns in a dataset containing approximately **413,000 records and 16 variables**, combining clustering, probabilistic modeling, and explainability.

**Key contributions and reported results**

- Compared six clustering methods: K-Means++, K-Prototypes, K-Modes, agglomerative clustering, DBSCAN, and Gaussian mixture models.
- Achieved reported cluster purity between 69.6% and 73.6%.
- Used Gower distance to work with mixed categorical and numerical features.
- Applied PCA and t-SNE to visualize data structure.
- Learned Bayesian network structures using BIC, AIC, and domain constraints.
- Reported 68.8% held-out accuracy for the Bayesian network modeling task.
- Applied SHAP and a decision-tree surrogate to help interpret model behavior.

**Technologies**

`Python` `scikit-learn` `Bayesian Networks` `SHAP` `PCA` `t-SNE` `Statistical Analysis`

**Why it matters:** The project emphasizes understanding data structure and interpreting model behavior instead of relying exclusively on predictive metrics.

---

### 4. Afya: Multiple Disease Prediction System

**Focus:** Machine learning for healthcare decision support.

Afya is a prototype that explores predicting risk for diabetes, malaria, and heart disease from patient-history data.

**Key contributions**

- Processed patient data and performed feature selection.
- Trained and evaluated multiple machine learning models.
- Tested the prototype on 1,000 patient records.
- Integrated the prediction workflow into a web-based application using Flask and Django.
- Explored how data-driven decision-support tools could be made accessible in settings with limited specialist care.

**Technologies**

`Python` `scikit-learn` `Flask` `Django` `Machine Learning`

**Why it matters:** The project connects machine learning workflows with software development to explore practical healthcare applications.

*This is a prototype, not a clinically validated diagnostic system.*

---

### 5. Ethiopian Manuscript OCR: Ge'ez, Amharic & Tigrigna

**Focus:** Optical character recognition and cultural heritage digitization.

This project explores OCR for handwritten manuscripts in Ge'ez, Amharic, and Tigrigna, including historical religious, scientific, and medical texts.

**Key contributions**

- Developed and evaluated an OCR pipeline using more than 150 manuscript pages.
- Reported 87% accuracy in the project.
- Used image-processing techniques to support manuscript recognition.
- Explored digital access to fragile historical documents.

**Technologies**

`Python` `OpenCV` `TensorFlow` `OCR` `Image Processing`

**Why it matters:** Language technology and document digitization can help preserve historical knowledge and make valuable manuscript collections easier to search and study.

---

## Software Engineering & Data Analytics

My experience extends beyond model development into production-oriented software, analytics, and backend systems.

### Data Analyst — Kabana Design PLC

- Analyzed sales, customer, website, and marketing KPIs.
- Produced reports and recommendations for management.
- Contributed to reported improvements of 40% in web traffic and 25% in conversion.
- Automated recurring reports, reducing manual processing by 30%.
- Maintained databases with attention to data quality and integrity.

### Data Scientist Intern — Prodigy InfoTech

- Applied statistical and machine learning methods to large datasets.
- Produced more than 10 predictive models and analytical insights.
- Built interactive Python visualizations that improved data interpretation and reporting efficiency.

### Software Engineer — Kabana Design PLC

- Developed web applications using Django and React.js.
- Worked on API integrations and application performance.
- Contributed to a reported 35% reduction in API integration time and 26% improvement in page-load time.

### Full-Stack Developer — Convex ICT Technology

- Built REST endpoints using Java and Spring Boot.
- Delivered more than 20 REST endpoints.
- Optimized database queries from approximately three seconds to under 500 milliseconds.
- Improved average API response time by 30%.

These experiences shape my approach to AI: I value clean implementations, efficient data handling, maintainable APIs, and practical delivery.

---

## 🛠️ Technical Skills

### Programming Languages & Data

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white" alt="SciPy">
</p>

### Machine Learning & Deep Learning

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV">
</p>

Methods: classification, clustering, CNNs, transfer learning, Vision Transformers, LoRA, ensemble learning, hyperparameter optimization, statistical analysis, and model evaluation.

### Backend, Databases & Tools

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" alt="Django">
  <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask">
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
</p>

Additional experience: REST APIs, Swagger/OpenAPI, Node.js, MySQL, PostgreSQL, database management, and full-stack application development.

---

## 📚 Education
Relevant areas of I am exploring noe includes:

- Machine learning and deep learning
- Computer vision and AI for signal/image processing
- Signal and imaging acquisition and modeling in healthcare
- Environmental sensing and imaging
- Advanced computational techniques for large imaging and signal datasets
- Statistics, mathematics, and data privacy

### BSc in Computer Science and Engineering
**Mekelle Institute of Technology, Mekelle University**  
Mekelle, Ethiopia | September 2016 – October 2021

- CGPA: **3.96/4.00**
- Graduated with Very Great Distinction
- Ranked in the **top 1% of 800+ engineering students**
- Achieved a perfect 4.00 GPA in six of ten semesters

### Additional Learning

**A2SV Community Education** — Selected for training in Python, data structures, and algorithm design and analysis.

---

## 🌍 Leadership, Mentoring & Community

I believe technical growth is even more meaningful when knowledge and opportunities are shared.

- **Global Mentorship Initiative:** Volunteer career mentor supporting mentees with career planning, interview preparation, and professional development.
- **YES Ethiopia:** Volunteer career mentor supporting students in exploring educational and professional opportunities.
- **Student mentoring and tutoring:** Supported students through tutoring and mentorship activities in Tigray.
- **Black in AI:** Member and selected participant in the Emerging Leaders in AI graduate program in 2026.
- **AI community:** Interested in contributing to a stronger, more inclusive AI ecosystem, particularly across Africa and underserved communities.

---

## 🔭 Current Research Interests

I am especially interested in exploring:

- **Medical image analysis:** Deep learning for retinal imaging and other healthcare imaging modalities.
- **Label-efficient learning:** Learning useful representations when labeled medical data is limited.
- **Parameter-efficient fine-tuning:** LoRA and related methods for adapting pretrained models.
- **Generalization and robustness:** Understanding how models behave across datasets and imaging conditions.
- **Explainable AI:** Using tools such as Grad-CAM and SHAP to inspect model behavior and failure cases.
- **Computer vision for the environment:** Image-based analysis for environmental monitoring and land-use applications.
- **AI engineering:** Building maintainable applications that integrate models, APIs, databases, and retrieval systems.

I'm interested in research that combines sound experimental design, reproducible evaluation, and meaningful real-world applications.

---

## 📌 Public GitHub Repositories

### [Supervised_Learning](https://github.com/NigusHaile/Supervised_Learning)

A learning repository covering machine learning and deep learning topics, including classical algorithms, ensemble methods, CNNs, RNNs, object detection, Transformers, and self-supervised learning.

### [A2SV-Community-Education](https://github.com/NigusHaile/A2SV-Community-Education)

A structured collection of Python learning materials and exercises covering data structures, algorithms, complexity analysis, and competitive programming concepts.

Explore more projects in my [GitHub repositories](https://github.com/NigusHaile?tab=repositories).

---

## 📈 GitHub Activity

<div align="center">

<a href="https://github.com/NigusHaile">
  <img src="https://github-readme-stats.vercel.app/api?username=NigusHaile&show_icons=true&hide_border=true&rank_icon=github" alt="Nigus's GitHub statistics">
</a>

<a href="https://github.com/NigusHaile">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=NigusHaile&layout=compact&hide_border=true" alt="Most used languages">
</a>

<a href="https://git.io/streak-stats">
  <img src="https://streak-stats.demolab.com?user=NigusHaile&hide_border=true" alt="GitHub contribution streak">
</a>

</div>

*Note: These statistics are generated by third-party services and may not always load or reflect every repository accurately.*

---

## 🤝 Let's Connect

I'm happy to connect with AI researchers, software engineers, students, and organizations working on meaningful technology.

- 💼 **LinkedIn:** [linkedin.com/in/nigushaile](https://www.linkedin.com/in/nigushaile/)
- 📧 **Email:** [n.haile@campus.unimib.it](mailto:n.haile@campus.unimib.it)
- 🐙 **GitHub:** [github.com/NigusHaile](https://github.com/NigusHaile)

If you are interested in computer vision, medical AI, machine learning, or building practical AI applications, feel free to reach out.

---

<div align="center">

### "Building thoughtfully. Learning continuously. Applying AI to problems that matter."

⭐ If you find something useful in my work, feel free to explore the repositories and share your feedback.

</div>
