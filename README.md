# ☀️ Solar Challenge Week 0: Project Setup
This repository contains the initial structure and environment configuration for the Solar Data Analysis Challenge. The primary objective of this week is to establish a robust and reproducible development environment.

## 🚀 Getting Started

### 1. Repository Structure

├── .github/
│   └── workflows/          # GitHub Actions CI/CD workflows
├── notebooks/              # Exploratory Data Analysis (EDA) and final report notebooks
├── src/                    # Custom Python modules (e.g., data cleaning functions)
├── scripts/                # Utility scripts (e.g., data download, model execution)
├── tests/                  # Unit and integration tests
├── .gitignore
├── requirements.txt
└── README.md



### 2. Reproducing the Environment

To ensure everyone is working with the same dependencies, follow these steps to set up your environment:

#### A. Clone the Repository
git clone https://github.com/birhanu-ma/solar-challenge-week0.git
cd solar-challenge-week0


#### B. Create and Activate a Virtual Environment
# Create the environment
python -m venv .venv

# Activate the environment
# On macOS/Linux:
source .venv/bin/activate
# On Windows (Command Prompt):
.venv\Scripts\activate


#### C. Install Dependencies
pip install -r requirements.txt