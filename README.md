# QCPDTool-Test 🧪💻
This repository contains a catalogue of 20 quantum algorithm expressed as quantum circuits written in the JSON-based format, obtained from QPainter quantum circuit representation tool.

The main goal of this collection is for validating the functional behavior of QCPDTool features, more specifically: 
- The **automatic design pattern detection** within the given quantum circuit in the previously mentioned QPainter JSON-based format.
- The **recommendation generation for design pattern usage** within the given circuit also, for a better comprehension about these design pattern usage and application in real solutions based on quantum circuits.

## Contents 📑
This repository is organized as follows:
- `Test_cases`: Folder containing a total of 20 data cards stored in plain text files including
  - An **identifier** for each quantum algorithm.
  - A **textual description** of the circuit that is being stored.
  - The **list of pattern matches** to be compared with QCPDTool response for validating the automatic pattern detection.
  - The **list of recommendations** to be compared with QCPDTool response for validating the recommendation module functioning.
- `README.md`: This file containing where this description is written in markdown format.
- `Test_cases_20.txt`: Plain text file with the whole collection of quantum circuits including the theoretical solution to be compared with QCPDTool response.

## Results 🚩
These circuits were launched in QCPDTool obtaining a 100% of accuracy, getting correct evaluations for all the pattern matches found and the given recommendations.

## Notation ✏️
Regarding the notation used for describing these cases, some abbreviations were used for denoting the design patterns names. These were:
- [_uncom_](https://www.quantumcomputingpatterns.org/#/patterns/20): Uncompute design pattern.
- [_init_](https://www.quantumcomputingpatterns.org/#/patterns/15): Initialization design pattern.
- [_super_](https://www.quantumcomputingpatterns.org/#/patterns/16): Superposition design pattern.
- [_ora_](https://www.quantumcomputingpatterns.org/#/patterns/19): Oracle design pattern.
- [_ent_](https://www.quantumcomputingpatterns.org/#/patterns/17): Entanglement design pattern.

The given links lead to the formal definition of these design patterns according to the [QuantumComputingPatterns](https://www.quantumcomputingpatterns.org/#/) webpage.
