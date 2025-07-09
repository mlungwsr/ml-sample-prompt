# Machine Learning Demos Repository

A collection of hands-on machine learning demonstrations and tutorials designed for educational purposes, featuring AWS SageMaker implementations and end-to-end ML workflows.

## 📋 Repository Contents

### Core Notebooks
- **`sample-prompts.ipynb`** - Main demonstration notebook with sample prompts and SageMaker setup examples

### Demo Projects

#### Demo 2: SageMaker Pipelines
- **Location**: `demo2/`
- **Notebook**: `Demo2-v2-sage-maker-pipelines-preprocess-train-evaluate-batch-transform.ipynb`
- **Focus**: Complete ML pipeline implementation using SageMaker Pipelines
- **Features**:
  - Data preprocessing
  - Model training
  - Model evaluation
  - Batch transformation
  - Pipeline orchestration

#### Demo 4: Customer Churn Analysis
- **Location**: `demo4/`
- **Notebook**: `Demo4-latest.ipynb`
- **Dataset**: Customer churn data (`churn.txt`, `train.csv`, `validation.csv`)
- **Focus**: End-to-end churn prediction workflow
- **Features**:
  - Data exploration and preprocessing
  - Feature engineering
  - Model training and validation
  - Performance evaluation

#### Demo 6: SageMaker Inference Recommender
- **Location**: `demo6/`
- **Notebook**: `InfRecommender.ipynb`
- **Dataset**: UCI Abalone dataset (regression)
- **Focus**: Automated performance benchmarking and model deployment optimization
- **Features**:
  - Model training with Linear Learner algorithm
  - Inference Recommender for performance testing
  - Cost-performance optimization
  - Real-time endpoint deployment recommendations
  - Load testing across different instance types

## 🚀 Getting Started

### Prerequisites
- AWS Account with appropriate permissions
- Python 3.7+
- Jupyter Notebook or JupyterLab
- Required Python packages (see individual notebooks for specific requirements)

### Essential Libraries
```python
import sagemaker
import boto3
import pandas as pd
import numpy as np
```

### Setup Instructions
1. Clone this repository
2. Configure AWS credentials
3. Install required dependencies
4. Launch Jupyter and open the desired demo notebook

## 🏗️ Architecture Overview

These demos demonstrate various AWS SageMaker capabilities:
- **SageMaker Pipelines** for ML workflow orchestration
- **Built-in algorithms** for common ML tasks
- **Custom training jobs** with your own code
- **Batch transformation** for inference at scale
- **Model evaluation** and performance monitoring

## 📚 Learning Objectives

By working through these demos, you'll learn:
- How to set up and configure SageMaker environments
- Best practices for ML pipeline development
- Data preprocessing techniques for ML workflows
- Model training and evaluation strategies
- Deployment patterns for ML models
- Cost optimization techniques for ML workloads

## 🔧 Configuration Notes

- Update the `databucket` variable in notebooks to match your S3 bucket
- Ensure your AWS region is correctly configured
- Verify IAM permissions for SageMaker operations

## 📊 Datasets

### Demo 4 Dataset Details
- **Training Data**: `train.csv` (~711KB)
- **Validation Data**: `validation.csv` (~203KB)
- **Raw Data**: `churn.txt` (~969KB)
- **Domain**: Customer churn prediction

## 🎯 Use Cases

These demos are ideal for:
- ML engineering workshops
- AWS SageMaker training sessions
- Academic coursework
- Self-paced learning
- Proof-of-concept development

## 📝 Best Practices Demonstrated

- Proper data splitting and validation
- Pipeline-based ML workflows
- Resource management and cleanup
- Error handling and logging
- Cost-effective training strategies

## 🤝 Contributing

Feel free to:
- Add new demo scenarios
- Improve existing notebooks
- Update documentation
- Share feedback and suggestions

## 📄 License

This repository is intended for educational purposes. Please ensure compliance with AWS service terms and any dataset licensing requirements.

## 🆘 Troubleshooting

Common issues and solutions:
- **Permission errors**: Verify IAM roles and policies
- **Resource limits**: Check service quotas in your AWS region
- **Data access**: Ensure S3 bucket permissions are correctly configured

---

*Last updated: July 2025*
