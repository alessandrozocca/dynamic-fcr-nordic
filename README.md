# Dynamic Dimensioning of Frequency Containment Reserves: The Case of the Nordic Grid

This repository contains the companion code for the article **"Dynamic Dimensioning of Frequency Containment Reserves: The Case of the Nordic Grid"**, authored by Jobke Janssen, Alessandro Zocca, Bert Zwart, and Jalal Kazempour. The preprint is available at [arxiv](https://arxiv.org/). The code supports the reproducibility of the results presented in the manuscript and facilitates further exploration of the proposed methodologies.

---

## Abstract

One of the main responsibilities of a Transmission System Operator (TSO) operating an electric grid is to maintain a designated frequency (e.g., 50 Hz in Europe). To achieve this, TSOs have created several products called frequency-supporting ancillary services. The Frequency Containment Reserve (FCR) is one of these ancillary service products. This article focuses on the TSO problem of determining the volume procured for FCR. Specifically, we investigate the potential benefits and impact on grid security when transitioning from a traditionally static procurement method to a dynamic strategy for FCR volume. We take the Nordic synchronous area in Europe as a case study and use a diffusion model to capture its frequency development. We introduce a controlled mean reversal parameter to assess changes in FCR obligations, in particular for the Nordic FCR-N ancillary service product. We establish closed-form expressions for exceedance probabilities and use historical frequency data as input to calibrate the model. We show that a dynamic dimensioning approach for FCR has the potential to significantly reduce the exceedance probabilities (up to 37%) while keeping the total yearly procured FCR volume the same as compared to the current static approach.

---

## Repository Contents

- `Dynamic FCR Nordic - Code for figures and tables.ipynb`: Jupyter notebook for step-by-step reproduction of key results, including visualizations.
- `data/`: Preprocessed datasets used in the study.
- `figures/`: Figure files created in the notebook.
- `results/`: .csv files created in the notebook where violation probabilities are recalculated depending on the heuristic.
- `README.md`: This file.

---

## Citation
If you use this code in your work, please cite our preprint as follows:

```
@article{Janssen2024,
  author = {Janssen, Jobke and Zocca, Alessandro and Zwart, Bert and Kazempour, Jalal},
  doi = {10.48550/arXiv.2411.xxxxx},
  journal = {arXiv},
  month = nov,
  title = {{Dynamic Dimensioning of Frequency Containment Reserves: The Case of the Nordic Grid}},
  url = {https://arxiv.org/abs/2411.xxxxx},
  year = {2024}
}
```

### License
This project is licensed under the MIT License.
