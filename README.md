<div align="center">

# 🚀 MLFlow Experiment Tracking with DagsHub

### _Seamless ML Experiment Management & Model Versioning_

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![MLflow](https://img.shields.io/badge/MLflow-2.2.2-0194E2?logo=mlflow&logoColor=white)](https://mlflow.org/)
[![DagsHub](https://img.shields.io/badge/DagsHub-Integrated-blue?logo=github&logoColor=white)](https://dagshub.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

<p align="center">
  <img src="https://img.shields.io/badge/ML-Experiment%20Tracking-orange" alt="ML"/>
  <img src="https://img.shields.io/badge/DVC-Version%20Control-purple" alt="DVC"/>
  <img src="https://img.shields.io/badge/Status-Production%20Ready-success" alt="Status"/>
</p>

---

**[Features](#-features) • [Quick Start](#-quick-start) • [Documentation](#-documentation) • [Examples](#-examples) • [Contributing](#-contributing)**

</div>

## 📋 Overview

Harness the power of **MLflow** and **DagsHub** for comprehensive machine learning experiment tracking! This project demonstrates a production-ready implementation of ML experiment management with:

- 🔬 **Automated Experiment Tracking** - Log metrics, parameters, and artifacts seamlessly
- 📊 **Model Versioning** - Track model evolution across experiments
- 🌐 **Cloud-Based Collaboration** - Git-based ML workflow with DagsHub integration
- 🔄 **Reproducibility** - Ensure consistent results across team members
- 📈 **Visualization** - Compare experiments and analyze performance trends

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🎯 **Parameter Tracking** | Automatically log hyperparameters (alpha, l1_ratio, etc.) |
| 📊 **Metrics Logging** | Track RMSE, MAE, R² scores and custom metrics |
| 🗂️ **Artifact Management** | Store models, plots, and data files |
| 🔗 **DagsHub Integration** | Seamless cloud-based experiment tracking |
| 🤖 **Model Registry** | Version and deploy models efficiently |
| 📉 **Visualization** | Compare experiments with interactive dashboards |

## 🚀 Quick Start

### Prerequisites

- Python 3.8 or higher
- Git
- DagsHub account (free tier available)

### Installation

```bash
# Clone the repository
git clone https://github.com/NayeemHossenJim/MLFlow-Experiment-Tracking-with-Dagshub.git
cd MLFlow-Experiment-Tracking-with-Dagshub

# Install dependencies
pip install -r requirements.txt
```

### Basic Usage

```bash
# Run with default parameters
python demo.py

# Run with custom hyperparameters
python demo.py 0.3 0.7
```

**Parameters:**
- `alpha`: ElasticNet regularization strength (default: 0.5)
- `l1_ratio`: L1 penalty ratio (default: 0.5)

## 📚 Documentation

### Project Structure

```
MLFlow-Experiment-Tracking-with-Dagshub/
│
├── demo.py              # Main experiment script
├── requirements.txt     # Python dependencies
├── README.md           # Project documentation
└── LICENSE             # License information
```

### How It Works

1. **Data Loading**: Fetches wine quality dataset from MLflow repository
2. **Data Splitting**: Divides data into training and testing sets
3. **Model Training**: Trains ElasticNet regression model
4. **Evaluation**: Calculates RMSE, MAE, and R² metrics
5. **Logging**: Tracks all parameters, metrics, and models to MLflow/DagsHub
6. **Model Registry**: Registers model for version control and deployment

### Configuration

Update the DagsHub connection in `demo.py`:

```python
dagshub.init(
    repo_owner='your-username',
    repo_name='your-repo-name',
    mlflow=True
)
```

## 🎯 Examples

### Example Output

```
Elasticnet model (alpha=0.500000, l1_ratio=0.500000):
  RMSE: 0.7463
  MAE: 0.5814
  R2: 0.1839
```

### Viewing Results

1. **Local MLflow UI**:
   ```bash
   mlflow ui
   ```
   Navigate to `http://localhost:5000`

2. **DagsHub Dashboard**:
   Visit your DagsHub repository to view experiments in the cloud

## 🛠️ Tech Stack

<div align="center">

| Technology | Purpose |
|------------|---------|
| ![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white) | Experiment tracking & model management |
| ![DagsHub](https://img.shields.io/badge/DagsHub-2088FF?style=for-the-badge&logo=github&logoColor=white) | Cloud collaboration & versioning |
| ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) | Core programming language |
| ![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white) | Machine learning framework |
| ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) | Data manipulation |
| ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white) | Numerical computing |

</div>

## 🤝 Contributing

Contributions are what make the open-source community amazing! Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📈 Roadmap

- [x] Basic MLflow integration
- [x] DagsHub cloud tracking
- [ ] Advanced model comparison features
- [ ] Automated hyperparameter tuning
- [ ] Docker containerization
- [ ] CI/CD pipeline integration
- [ ] Multi-model comparison dashboard
- [ ] Real-time monitoring

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

## 🌟 Acknowledgments

- [MLflow Documentation](https://mlflow.org/docs/latest/index.html)
- [DagsHub Platform](https://dagshub.com/)
- [Scikit-learn](https://scikit-learn.org/)
- Wine Quality Dataset from UCI Machine Learning Repository

## 📧 Contact

**NayeemHossenJim** - [@NayeemHossenJim](https://github.com/NayeemHossenJim)

Project Link: [https://github.com/NayeemHossenJim/MLFlow-Experiment-Tracking-with-Dagshub](https://github.com/NayeemHossenJim/MLFlow-Experiment-Tracking-with-Dagshub)

---

<div align="center">

### ⭐ Star this repository if you find it helpful!

Made with ❤️ by [NayeemHossenJim](https://github.com/NayeemHossenJim)

</div>
