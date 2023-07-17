# Computational-Drug-Discovery-Neural-Network

This GitHub repository contains code for a computational drug discovery project utilizing neural networks. The goal of the project is to explore bioactivity data for a specific target protein related to Herpes virus and use it to classify compounds as active, inactive, or intermediate based on their bioactivity values. Additionally, molecular descriptors are calculated to aid in the analysis.

## Table of Contents

- [Data Collection](#data-collection)
- [Handling Missing Data](#handling-missing-data)
- [Data Preprocessing](#data-preprocessing)
- [Calculate Lipinski's Descriptors](#calculate-lipinskis-descriptors)
- [Convert IC50 to pIC50](#convert-ic50-to-pic50)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Statistical Analysis](#statistical-analysis)
- [Descriptor Calculation and Dataset Preparation](#descriptor-calculation-and-dataset-preparation)

## Data Collection <a name="data-collection"></a>

The data is collected from the ChEMBL database using the ChEMBL web service package. The target protein for Herpes virus is searched, and the bioactivity data is retrieved.

## Handling Missing Data <a name="handling-missing-data"></a>

Any compounds with missing values for the standard_value column are dropped from the dataset.

## Data Preprocessing <a name="data-preprocessing"></a>

The bioactivity data is preprocessed, and compounds are labeled as active, inactive, or intermediate based on their IC50 values.

## Calculate Lipinski's Descriptors <a name="calculate-lipinskis-descriptors"></a>

Lipinski's descriptors are calculated for the compounds, which are essential molecular properties used in drug discovery and medicinal chemistry.

## Convert IC50 to pIC50 <a name="convert-ic50-to-pic50"></a>

IC50 values are converted to pIC50, a negative logarithmic scale, to ensure uniform distribution and facilitate analysis.

## Exploratory Data Analysis <a name="exploratory-data-analysis"></a>

Frequency plots, scatter plots, and box plots are used to explore the distribution of bioactivity classes and molecular properties.

## Statistical Analysis <a name="statistical-analysis"></a>

The Mann-Whitney U test is performed to assess whether there is a significant difference between the distributions of active and inactive compounds for various molecular properties.

## Descriptor Calculation and Dataset Preparation <a name="descriptor-calculation-and-dataset-preparation"></a>

PaDEL-Descriptor software is used to calculate molecular descriptors and prepare the dataset for further analysis.

Please feel free to explore the code and datasets in this repository to understand the drug discovery process for the target protein related to Herpes virus. If you have any questions or suggestions, feel free to open an issue or contribute to the project. Happy drug discovery!

