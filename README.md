# What is this?

This code numerically computes the energy levels for a hetronuclear molecule modeled as a rigid rotor within in a DC electric field.

![Animation of angular wavefunction with increasing E](/images/Animation.gif)

![energy level splitting diagram](/images/DCStarkRigidRotor.png)

# Installation

```bash
# Create virtual environment
python3 -m venv "venv"
# Activate virtual environment
source ./venv/bin/acticate
# Install pip tools
pip install pip-tools
# Compile dependencies
pip-compile
# Install dependencies
pip-sync
# Run program
python ./main.py
```