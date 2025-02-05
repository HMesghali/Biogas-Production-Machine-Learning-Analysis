
```markdown
# Biogas-Production-ML-Analysis

## Overview

This repository contains the source code and data for the paper titled:

# A Machine Learning Approach to Feature Selection and Uncertainty Analysis for Biogas Production in Wastewater Treatment Plants

**Authors:**
- Mahsa Samkhaniani
- Shabnam Sadri Moghaddam
- Hassan Mesghali
- Amirhossein Ghajari
- Nima Gozalpour

 The paper can be found at [this link]([PAPER_LINK]).

## Abstract

The rising need for effective waste management and renewable energy has driven research into predicting biogas production at wastewater treatment plants. This study outlines a process starting with data collection from an operational plant, followed by detailed analysis to resolve potential issues. A notable advancement is the use of a robust machine learning model, fine-tuned with advanced optimization techniques. To enhance its utility, prediction intervals were incorporated to quantify uncertainty, supporting regulators in making informed decisions. The model performed well, explaining 82% of the variability in test data and delivering predictions closely aligned with actual biogas production. This reliability empowers more confident decision-making in wastewater treatment operations. The study also identified key factors influencing biogas output, including sludge characteristics, operational practices, and sludge quantity. By focusing on these variables, operators can optimize processes and significantly improve biogas yields. This predictive capability, combined with an understanding of influencing factors and quantified reliability, offers notable advantages. It enables operators to enhance plant efficiency and biogas production while providing regulators with reliable predictions to guide policy and resource management. These developments contribute to more sustainable and efficient waste management practices.

## Software Implementation

All source code used to generate the results and figures in the paper is contained within Jupyter Notebook files (`.ipynb`).

## Data Availability

All data, material, and/or code are available on request from the corresponding author.

## Dependencies

The following dependencies are required to run the code:

```plaintext
pandas==2.2.2
numpy==1.26.4
matplotlib==3.10.0
seaborn==0.13.2
scienceplots==2.1.1
scikit-learn==1.5.2
lightgbm==4.5.0
optuna==4.2.0
optuna-integration==4.2.1
scipy==1.13.1
tqdm==4.67.1
puncc==0.8.0
mapie==0.9.2
```

These dependencies are listed in the `requirements.txt` file. To install them, run:

```sh
pip install -r requirements.txt
```

## License

All source code is made available under a BSD 3-clause license. You can freely use and modify the code, without warranty, so long as you provide attribution to the authors. See `LICENSE` for the full license text.

The manuscript text is not open source. The authors reserve the rights to the article content, which is currently submitted for publication in the **Waste Management**.

## Contact

For any inquiries or to request data, please contact the corresponding author.
Corresponding author; E-mail address: sadrimoghaddam@kntu.ac.ir

```
