# Retina‑Flow‑Pipeline

End‑to‑end Python 3.12 tool that converts a fundus photograph into a
personalised 3‑D haemodynamic eye model.

## Features
- ruler‑based ISO 10940 calibration
- FV‑OD localisation (manual → DL ready)
- vessel segmentation & skeletonisation
- 2‑D network flow solver (FiPy)
- ellipsoid mapping + 3‑D CFD prototype
- one‑click CLI (`python main.py`)

## Quick start
```bash
git clone https://github.com/ORG/retina-flow-pipeline
cd retina-flow-pipeline
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
python main.py --help
