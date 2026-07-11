Frequency-Response-EfficientNetB3

This repository contains the implementation of a frequency-response
lag-lead compensation module integrated within EfficientNetB3 for benign and
malignant lung nodule classification.

 Datasets

The experiments use publicly available datasets:

- IQ-OTH/NCCD lung CT dataset
- JSRT chest X-ray dataset
- BreakHis histopathology dataset

The datasets are not included in this repository. Users should download them
from their official sources and update the dataset paths in the notebooks.

Proposed Method

The proposed method includes:

- fixed lag-inspired low-pass filtering;
- fixed lead-inspired edge enhancement;
- trainable feature fusion;
- EfficientNetB3 classification backbone;
- ablation and parameter-sensitivity analysis.

Repository Structure

- `notebooks/`: complete experimental notebooks


## Installation

```bash
pip install -r requirements.txt
