# Odour_distance_paper

👋 Welcome to the `Odour_distance_paper` repo, where we release datasets and analysis scripts used for plots in:

**Mice discriminate odour source distance via sub-sniff temporal features of odour plumes** ([preprint link])

---

## 🔎 The story

How do animals estimate how far away an odour source is? In this study, we show that mice can extract spatial information from the **high-frequency temporal dynamics** of naturalistic odour plumes.

To investigate this, we combined:

- A **custom wind tunnel** to generate reproducible, distance-dependent odour plumes,
- An **olfactory virtual reality (oVR)** system for automated behavioural training,
- And **two-photon calcium imaging** of mitral and tufted cells (MTCs) in the olfactory bulb (OB).

Our key findings:

- 🐭 **Mice discriminate odour sources at different distances** using sub-sniff (faster than ~12 Hz) temporal features in odour plumes.
- 📈 Behavioural performance was best explained by features such as **onset slope**, **peak height**, and **intermittency**, not just mean odour concentration.
- 🧠 A small subset of MTCs showed **distance-sensitive responses** that tracked high-frequency odour fluctuations.
- 🤖 Population activity encoded source distance, and correlated more strongly with fast temporal features than with average intensity.

Together, these results reveal that mice can use **rapid odour fluctuations** to infer spatial properties of odour sources — an ability that enhances their environmental awareness without requiring physical movement.

---

## 👩‍💻 Getting started

1. Clone this repo:

```bash
git clone https://github.com/your-username/Odour_distance_paper.git
```

2. Download datasets from our Zenodo archive (links below).

3. Create a conda environment with required packages:
```bash
conda create -n odd_env python=3.9 numpy pandas scipy matplotlib seaborn jupyter scikit-learn
conda activate odd_env
```
4. Start Jupyter Notebook:
```bash
jupyter notebook
```

5. Update paths in scripts/startup.py and notebooks (e.g. notebooks/analysis_distance.ipynb) to reflect your local file structure.

6. Run analysis notebooks to reproduce key behavioural and imaging plots (with additional scripts released after peer review).


---

## 🧐 The datasets

```markdown
### Behavioural data

High-throughput recordings from head-fixed mice trained to discriminate odour source distances.

| Cohort | Description | Zenodo link |
|--------|-------------|-------------|
| C001   | Binary (near vs far) discrimination task | [link] |
| C002   | Multi-distance generalisation task | [link] |

---

### Odour plume data

Includes PID recordings and extracted temporal features for odours at multiple distances.

| File | Description | Link |
|------|-------------|------|
| `plume_features.csv` | Extracted plume statistics (peak slope, intermittency) | [link] |
| `pid_traces.npy`     | Raw PID signals used to estimate odour dynamics | [link] |

---

### Imaging data

Two-photon Ca²⁺ imaging of olfactory bulb projection neurons during plume playback.

| File | Description | Link |
|------|-------------|------|
| `imaging_summary.h5`    | ΔF/F responses with ROI metadata | [link] |
| `decoder_accuracy.csv` | Population-level decoding performance | [link] |


- **Ackels et al. 2021** – oVR and sub-sniff odour encoding
- **Dasgupta et al. 2022** – OB projection neurons and high-frequency coding
- **Tootoonian et al. 2025** – Models of spatial inference from odour dynamics
- **Marin et al. 2021** – Mouse navigation in turbulent odour plumes


## 📚 Related publications

- Ackels et al. 2021 – oVR system and sub-sniff temporal encoding in OB
- Dasgupta et al. 2022 – High-frequency odour signal tracking in projection neurons
- Tootoonian et al. 2025 – Theoretical work on spatial olfactory inference
- Marin et al. 2021 – Mouse navigation using turbulent odour plumes

## 🙌 Acknowledgements


## ☎️ Contact
For questions, data access, or collaboration inquiries, contact:
- **Tobias Ackels** – [tobias.ackels@ukbonn.de](mailto:tobias.ackels@ukbonn.de)
- **Andreas T. Schaefer** – [andreas.schaefer@crick.ac.uk](mailto:andreas.schaefer@crick.ac.uk)
