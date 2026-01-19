# 16-Qubit W-State – QAI Project Milestone

Scaled from verified 8-qubit run (Job ID 598eb802-0a56-428c-aec0-b23edca61e3c on ibm_brisbane).

- 1024 shots
- Flat 1/16 distribution (~64 counts per state)
- 100% fidelity (ideal simulation – benchmark)
- QERRA Hybrid Algorithm for error-resilient entanglement
- Real hardware run pending (IBM trial-instance issue – ticket CS4421467)

### Files
- `w16.py` – Full code
- `results.txt` – Exact counts

**Author:** Marussa Metocharaki (@marunigno)  
**Date:** December 2025 – Greece 🇬🇷  
**Aided by:** Grok (xAI)

**Part of the main QERRA-v2 project:**  
https://github.com/marunigno-ship-it/QERRA-v2

**Related scaling proofs:**  
- [8-qubit W-state (real IBM hardware)](https://github.com/marunigno-ship-it/8qubit-wstate-qubs)  
- [32-qubit W-state](https://github.com/marunigno-ship-it/32qubit-wstate-qubs) – latest scaling benchmark

**License:** Apache-2.0 (same as main project)

#QuantumRobotics #QAI #IBMQuantum #EthicalAI #QuantumEntanglement #Greece

## Run it yourself in 10 seconds
```bash
pip install qiskit[visualization]  # one-time only
python w16.py
