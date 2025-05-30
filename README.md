# Gini Bias in Random Forest Models

## Overview
This repository investigates Gini bias in Random Forest feature importance metrics, comparing methods like Gini Importance, Permutation Importance, Drop-Column Importance, and Actual Impurity Reduction (AIR). The primary goal is to transfer R-based solutions (e.g., AIR) to Python, enhancing the scikit-learn library for unbiased feature importance assessment.

## Project Structure
- `code/`: Python scripts for Random Forest models and feature importance methods.
- `report/`: LaTeX files for the project report.
- `data/`: Placeholder for datasets (to be added).

## Installation
1. Clone the repository: `git clone https://github.com/yourusername/gini-bias-random-forest.git`
2. Install dependencies: `pip install -r requirements.txt`

## Usage
- Run the main script to evaluate feature importance methods: `python code/main.py`

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Inspired by Sandri & Zuccolotto (2018), "The revival of the Gini importance?"
