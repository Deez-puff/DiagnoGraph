markdown# DiagnoGraph: Streamlit-Based Patient Health Diagnosis Report

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

**DiagnoGraph** is a healthcare data analysis and visualization tool designed to help doctors and patients track health trends over time. It provides interactive Streamlit dashboards with patient-specific records, BMI calculation, and summary-based health status classification using graphs and standardized values.

> ⚠️ **Disclaimer:** DiagnoGraph is a data visualization and reporting tool intended to support — not replace — professional medical judgment. It is not a diagnostic device and should not be used as a substitute for advice from a qualified healthcare provider.

## Table of Contents

- [Features](#features)
- [Project Structure](#project-structure)
- [Project Images](#project-images)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Why DiagnoGraph?](#why-diagnograph)
- [Contributors](#contributors)
- [License](#license)

## Features

- **Streamlit Dashboard** — Interactive, real-time visualization of patient health data
- **Patient-specific analysis** — Enter a patient ID to view records for that individual only
- **Standardized data plots** — Consistent scaling for accurate comparisons across tests
- **Summary Report** including:
  - BMI calculation (displayed at the start and in the summary)
  - Values across multiple medical tests *(in progress)*
  - Final health status classification (Healthy / At Risk)
  - Predicted disease, if detected *(in progress)*

## Project Structure
DiagnoGraph/
│
├── app.py              # Main Streamlit application (frontend + visualization)
├── backend/            # Data standardization and preprocessing
├── graphs/             # Graph generation logic
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation

## Project Images

<img width="800" height="400" alt="DiagnoGraph dashboard view 1" src="https://github.com/user-attachments/assets/b5604580-248c-4c54-9f09-6f26bd45bb60" />
<img width="800" height="400" alt="DiagnoGraph dashboard view 2" src="https://github.com/user-attachments/assets/359871c2-3e82-4831-93ca-0f39f8ed67b5" />
<img width="800" height="400" alt="DiagnoGraph dashboard view 3" src="https://github.com/user-attachments/assets/5b7e6939-60d3-4ee6-acbf-c871ac2f27ac" />
<img width="800" height="400" alt="DiagnoGraph dashboard view 4" src="https://github.com/user-attachments/assets/347e2fdf-6f1c-4f25-b91f-7b5bc1ae5731" />
<img width="800" height="400" alt="DiagnoGraph dashboard view 5" src="https://github.com/user-attachments/assets/e8bedd0b-e00a-441c-9961-bd66ba1a2cfb" />
<img width="800" height="400" alt="DiagnoGraph dashboard view 6" src="https://github.com/user-attachments/assets/a3681b30-51ab-45a3-9e1b-f762faef23c4" />

- Streamlit dashboard
- Patient-specific graphs
- Summary report with BMI and health status

## Technology Stack

| Layer | Technology | Purpose |
|-------|-----------|---------|
| Interface | Streamlit | Interactive dashboard and graph rendering |
| Language | Python 3.10+ | Core application logic |
| Data Handling | NumPy & Pandas | Data standardization and preprocessing |

## Getting Started

### Prerequisites

- Python 3.10+
- Required Python packages (listed in `requirements.txt`)

### Installation

1. Clone the repository:
```bash
   git clone https://github.com/Sai-Deepan/DiagnoGraph.git
   cd DiagnoGraph
```
2. Install required Python packages:
```bash
   pip install -r requirements.txt
```
3. Add your patient data by feeding the relevant CSV files into the application.

## Usage

1. Start the Streamlit application:
```bash
   streamlit run app.py
```
2. Enter a patient ID in the interface.
3. View graphs of different test results for that patient.
4. Review the generated summary, including:
   - BMI and test values
   - Health status (Healthy / At Risk)
   - Predicted disease, if health deviates from normal *(in progress)*

## Why DiagnoGraph?

Monitoring health over time is critical. DiagnoGraph combines data standardization, visualization, and health summarization with a simple Streamlit interface, making it easier for doctors and patients to:

- Track progress
- Understand health status
- Make informed decisions

## Contributors

- Deepan Sai
- Aadithya V
- Viswasainath Vijayakumar
- Deepak R

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
