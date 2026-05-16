# AI for Healthcare Data Analysis — Skills Lab

Source materials and instructions for **Lesson 15** of *Fundamentals of Applied Artificial Intelligence in Health Care*.

Published at: https://black-jl.github.io/data-analysis-lab/

## Contents

- `index.html` — the lab page (instructions + dataset downloads)
- `files/patient-satisfaction-data.xlsx` — Exercise 1 dataset (fictionalized JOES data)
- `files/medlog-supply-chain-data.xlsx` — Exercise 2 dataset (fictionalized DMLSS transactions)
- `generate-qr.py` — regenerate the QR code if the URL changes
- `qr-code.png` — the QR code displayed on the page

## Regenerating the QR

```bash
pip install qrcode pillow
python3 generate-qr.py https://black-jl.github.io/data-analysis-lab/
```

## Data notes

All scenario data is **fictionalized** for instructional purposes. No real patient or operational records are included.
