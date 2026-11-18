# Microstructure Analysis using Python

## About the Project

This project performs a basic analysis of material microstructure using Python.

The program generates a 20×20 matrix with random pixel brightness values and classifies each pixel into three phases: pores, silicon carbide (SiC), and silicon (Si).

## Features

- Generation of a random 20×20 brightness matrix.
- Pixel classification based on brightness ranges.
- Calculation of phase area percentages.
- Calculation of mass percentages using material densities.
- Verification of sample requirements.
- Visualization of the classified microstructure.

## Classification Criteria

| Brightness | Phase |
|---|---|
| 0–29 | Pores |
| 30–139 | SiC |
| 140–255 | Si |

## Material Properties

| Material | Density |
|---|---:|
| SiC | 3.21 g/cm³ |
| Si | 2.33 g/cm³ |

## Requirements

- Python 3
- NumPy
- Matplotlib

## Installation

Install the required libraries:

```bash
pip install -r requirements.txt
```

## Running the Program

Run the following command:

```bash
python main.py
```

## Sample Requirements

The program checks whether the sample meets the following criteria:

- Porosity ≤ 5%
- Silicon mass fraction ≤ 15%

## Technologies Used

- Python
- NumPy
- Matplotlib

## Author

Educational project focused on Python programming and basic material microstructure analysis.
