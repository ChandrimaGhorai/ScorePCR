# ScorePCR 🧪

ScorePCR is an in-silico PCR simulation and primer evaluation pipeline designed to catch amplification failures before physical bench experiments. It validates template sequences, checks primer binding orientation and stability, and scores primer pairs based on specificity, melting temperature ($T_m$), and GC content.

## Key Features
- **Sequence Validation:** Automatically verifies that entered DNA templates conform to standard nucleotide alphabets.
- **Comprehensive Primer Analysis:** Calculates length, GC content, and estimated $T_m$ while checking primer compatibility.
- **Binding & Orientation Check:** Scans templates for viable primer binding sites and confirms correct directional orientation for successful amplification.
- **In-Silico Amplification:** Predicts expected product regions and calculates exact amplicon sizes.
- **Automated Troubleshooting:** Explains probable causes and highlights problematic parameters when amplification looks unlikely.

## Workflow Overview
1. **Input:** User provides a DNA template along with forward and reverse primers.
2. **Analysis & Validation:** Sequences are validated, primer properties are calculated, and binding sites are mapped.
3. **In-Silico Simulation:** Orientation is verified and the expected amplicon product is predicted.
4. **Scoring & Reporting:** Parameters are distilled into a composite score and diagnostic verdict (Good, Needs Attention, or Poor).

## Usage
You can run the complete analysis pipeline interactively via Google Colab:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1tc0u-jo5FxXNjupQydCpTHa8Ie8l8uTi?usp=sharing)
