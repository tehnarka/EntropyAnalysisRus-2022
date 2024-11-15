# EntropyAnalysisRus

## Short Description
A Python-based repository for experimental evaluation of entropy and redundancy in Russian text. Includes calculations for letter frequencies, bigrams, entropy values (H1, H2, H(n)), and redundancy using prebuilt and custom tools.

## Overview
This repository is designed for analyzing the entropy and redundancy of Russian texts using custom Python programs and external tools. It enables the calculation of:

- **H1 (single-letter entropy):** Measures the average information per character.
- **H2 (bigram entropy):** Considers pairs of consecutive characters.
- **H(n) (block entropy):** Estimates entropy for blocks of n characters.
- **Redundancy:** Indicates the compressibility of the text.

## Features
- Frequency analysis of Russian text with and without spaces.
- Bigram frequency computation with and without overlap.
- Entropy evaluation for varying block sizes using custom scripts and the CoolPinkProgram.
- Redundancy calculation for different entropy models.
- Results exportable to Excel for further analysis.

## Requirements
- Python 3.7+
- pandas
- math
- A text file (`TEXT.txt`) containing Russian text for analysis.
- CoolPinkProgram (optional for advanced entropy calculations).

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/EntropyAnalysisRus.git
   cd EntropyAnalysisRus
   ```
2. Place your Russian text file in the repository folder as `TEXT.txt`.
3. Run the Python script for frequency and entropy calculations:
   ```bash
   python SymCryptoLab1.py
   ```
4. Use CoolPinkProgram for advanced entropy evaluations (H(10), H(20), H(30)).
5. Analyze the exported Excel files for detailed frequency and entropy data.

## Outputs
- **`букви з пробілом.xlsx`:** Frequencies of characters (with spaces).
- **`with_a_cross.xlsx`:** Bigram frequencies with overlap.
- **`without_a_cross.xlsx`:** Bigram frequencies without overlap.
- Printed entropy values (H1, H2).

## Example Results
- **Entropy Values:**
  - H1 = 4.36 (with spaces), 4.45 (without spaces).
  - H2 = 3.99 (with overlap), 4.15 (without overlap).
- **Redundancy:**
  - H1 Model: 12.7%
  - H2 Model: 20.2%
