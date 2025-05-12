# Odour_distance_paper

👋 Welcome to the `Odour_distance_paper` repo. Here you'll find essential code, and data supporting our study on how mice estimate odour source distance using fast temporal features of odour plumes.

**Mice discriminate odour source distance via sub-sniff temporal features of odour plumes** ([preprint link])

---

## 🔎 The story

How do animals estimate how far away an odour source is? In this study, we show that mice can extract spatial information from the **high-frequency temporal dynamics** of naturalistic odour plumes.

To investigate this, we combined:

- A **custom wind tunnel** to generate reproducible, distance-dependent odour plumes,
- An **olfactory virtual reality** system for automated behavioural training,
- And **two-photon calcium imaging** of mitral and tufted cells (MTCs) in the olfactory bulb (OB).

Our key findings:

- 🐭 **Mice discriminate odour sources at different distances** using sub-sniff temporal features in odour plumes.
- 📈 Behavioural performance was best explained by features such as **number of peaks** and **peak height**, not just mean odour concentration.
- 🧠 A small subset of MTCs responded differentially to plumes presented from different distances, and thus showed **distance-sensitive responses**.
- 🤖 Population activity encoded source distance, and correlated more strongly with fast temporal features than with average intensity.

Together, these results reveal that mice can use **rapid odour fluctuations** to discriminate the distance of odour sources.

---

## 👩‍💻 Getting started

1. Clone this repo:

```bash
git clone https://github.com/ackels-lab/Odour_distance_paper.git
```

2. Download datasets from our Zenodo archive [https://zenodo.org/records/15390336(https://zenodo.org/records/15390336?preview=1&token=eyJhbGciOiJIUzUxMiJ9.eyJpZCI6ImM5OWYxNzFmLWI2ZjQtNGJiZC04MDY4LTczNWFiOTM3YmRjZiIsImRhdGEiOnt9LCJyYW5kb20iOiI4YjY3MTA0YjA3YzVlYzhjYWQwYzFmNThiMzQ5ODI0MiJ9.LfeSrD1GmxcdXL5ryvMeYQwmVQr0d1jlsryrN8_IwYYBD35y9DAu_Jnqt6a8tee-c8Sq0ZE9T2_yfiz2EUETGA)].

3. Create a conda environment with required packages:
```bash
conda create -n odd_env python=3.9 numpy pandas scipy matplotlib seaborn jupyter scikit-learn
conda activate odd_env
```
4. Start Jupyter Notebook:
```bash
jupyter notebook
```
5. Update paths in scripts/analysis.main.py to reflect your local file structure.

6. Run the analysis notebook to reproduce key results from the main figures (additional scripts will be released after peer review).

---

## 🙌 Acknowledgements
This project was a collaboration among behavioural, systems, and computational neuroscientists. We thank the Francis Crick Institute, University College London, and the University of Bonn for their support. Please see the manuscript for full author contributions and funding sources.

## ☎️ Contact
For questions, data access, or collaboration inquiries, contact:
- **Tobias Ackels** – [tobias.ackels@ukbonn.de](mailto:tobias.ackels@ukbonn.de)
- **Andreas T. Schaefer** – [andreas.schaefer@crick.ac.uk](mailto:andreas.schaefer@crick.ac.uk)
