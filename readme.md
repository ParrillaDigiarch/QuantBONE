# QuantBone

**Quantification of Bone Organics by Non-Invasive Evaluation**

QVisNIR spectroscopy (350–2500 nm) and Machine Learning to estimate organic preservation in archaeological bone, such as collagen yield, without destroying the sample. The aim is to give researchers a fast, low-cost way to screen bones before sending them for radiocarbon dating or isotope analysis.

👉 **New to spectroscopy or machine learning?** Start with the [5-minute explainer](https://ParrillaDigiarch.github.io/quantBONE/).

## Current stage

We are validating a published collagen prediction model on new archaeological material:

> Ryder, C. et al. (2026). Refining near-infrared spectroscopy for collagen quantification: A new predictive model for archaeological bone. *Journal of Archaeological Science*, 185, 106448. [doi:10.1016/j.jas.2025.106448](https://doi.org/10.1016/j.jas.2025.106448)

The code, data and models for that study are available at [Gnpd/NIR-Collagen-Prediction](https://github.com/Gnpd/NIR-Collagen-Prediction).

## Collaborators and tools

- **[Gnpd](https://github.com/Gnpd)**: [openmodels](https://github.com/Gnpd/openmodels) saves and shares trained machine learning models (e.g. scikit-learn) in portable formats such as JSON or YAML, so they can be reused across different projects.
- **[Pau Cabaneros](https://github.com/paucablop)**: [chemotools](https://github.com/paucablop/chemotools) handles spectral preprocessing (baseline correction, smoothing, scatter correction…) as scikit-learn transformers, so spectra can go straight into machine learning workflows.

## Contact

**Rubén Parrilla**, ICArEHB – Universidade do Algarve
✉️ [rpgiraldez@ualg.pt](mailto:rpgiraldez@ualg.pt) · ORCID [0000-0002-9894-512X](https://orcid.org/0000-0002-9894-512X)

## Funding

Part of *Imaging an Invisible Archaeology: Identifying physicochemical properties with contactless optical technologies and Artificial Intelligence* ([2023.07698.CEECIND/CP2883/CT0003](https://doi.org/10.54499/2023.07698.CEECIND/CP2883/CT0003)).