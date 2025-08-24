# Primer Designing Tool

A Python tool to design **forward and reverse primers** from a DNA sequence. Calculates **GC content** and **melting temperature (Tm)** for each primer. Perfect for molecular biology, PCR experiments, and bioinformatics practice.

## Features
- Forward primer generation
- Reverse primer (reverse complement) generation
- GC content calculation
- Melting temperature (Tm) estimation
- Adjustable primer length (10–30 nucleotides)
- Simple and beginner-friendly Python code
- Optional Gradio web interface for interactive usage

## How to Use
1. Clone or download the repository.
2. Open `app.py` in Python IDE or **Google Colab**.
3. Paste your DNA sequence in the input box (or in the `dna_sequence` variable if using plain Python).
4. Adjust primer length if needed.
5. Run the script to get primers and properties.

### Example
```python
dna_sequence = "ATGCGTACGTTAGCTAGCTAGCTAGCTGACTGATCGATCG"
result = design_primers(dna_sequence)
print(result)
