# Dimensionality-Reduction-CGM
Dimensionality Reduction for Studying Diffuse Circumgalactic Medium.

Implemented dimensionality reduction techniques to (best) preserve classification accuracy on reduce feature space.

Used Deep Autoencoders for dimensionality reduction; and DNN, XGBoost for classification. Results and procedures described in Technical Report.

## TLDR:

### Part 1

[Solution_Part_1.pdf](Part_1/Solution_Part_1.pdf)

### Part 2

[SpectrumCalc.pdf](Part_2/SpectrumCalc.pdf)

### Part 3

[CGM_Technical_Report.pdf](Part_3/CGM_Technical_Report.pdf)

## Repository Structure
```
├── LICENSE
├── Part_1
│   ├── Solution_Part_1.md
│   └── Solution_Part_1.pdf
├── Part_2
│   ├── SpectrumCalc.ipynb
│   └── SpectrumCalc.pdf
├── Part_3
│   ├── CGM_Technical_Report.pdf
│   ├── ColabNotebooks
│   │   ├── DAE_DNN.ipynb
│   │   ├── DAE.ipynb
│   │   ├── DAE_XGB.ipynb
│   │   ├── VanillaDNN.ipynb
│   │   └── VanillaXGB.ipynb
│   └── NotebookOutputsPDF
│       ├── DAE_DNN.pdf
│       ├── DAE.pdf
│       ├── DAE_XGB.pdf
│       ├── VanillaDNN.pdf
│       └── VanillaXGB.pdf
└── README.md
```

## Usage

```
$ git clone https://github.com/ShivenTripathi/Dimensionality-Reduction-CGM.git
```
### Part 2:

* Run code cells in [SpectrumCalc.ipynb](Part_2/SpectrumCalc.ipynb), to generate spectrum outputs

### Part 3:

1. Create a shortcut of [Drive Folder](https://drive.google.com/drive/folders/1f8qW3uE-O-YoQHK0CWj9tfuEanH_JZZO?usp=sharing), containing dataset, models and encodings, to your drive

2. Run the Colab Notebooks after changing the user directory to your Drive.