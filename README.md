<div align="center">

<h1>Seunghyun Lee</h1>

<p>
<b>Undergraduate Researcher · Korea University</b><br>
<sub>B.S. Industrial and Management Engineering · Double major in Mathematics · March 2023 – February 2027 (expected)</sub>
</p>

<p><i>Explainable regularization — deciding what a network should suppress <b>during</b> training,<br>
instead of reading explanations off a model after it has finished learning.</i></p>

<p>
<a href="https://orcid.org/0009-0006-1926-653X"><img src="https://img.shields.io/badge/ORCID-0009--0006--1926--653X-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID"></a>
<a href="mailto:leesh4660@gmail.com"><img src="https://img.shields.io/badge/Email-leesh4660@gmail.com-3A4A5A?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://github.com/lshpy/sdrop"><img src="https://img.shields.io/badge/Code-SDrop-0D1117?style=for-the-badge&logo=github&logoColor=white" alt="SDrop"></a>
</p>

<p>
<img src="https://img.shields.io/badge/xAI_2026-Demo_Track,_sole_author-00695C?style=flat-square" alt="xAI 2026">
<img src="https://img.shields.io/badge/Physica_Scripta-101_(2026)_225216-1B5E20?style=flat-square" alt="Physica Scripta">
<img src="https://img.shields.io/badge/Neurocomputing-under_review-B26500?style=flat-square" alt="Neurocomputing">
</p>

</div>

---

> [!IMPORTANT]
> ### Suppressive Dropout (SDrop)
> Standard dropout removes units at random; targeted dropout removes the weakest ones.
> **SDrop removes the most dominant channels** — those that are both high-energy and
> spatially diffuse — on the argument that, through lateral inhibition, they monopolize
> the representation and starve detectors for rare or minority-class features of gradient.
> Dominance is scored by `s_c = E_c (1 − P_c)` from the activation map in a **single
> forward pass**, cheap enough to run at every step of training.
>
> Reference implementation, the ViT head-level variant, and baselines (DropBlock, SE, CBAM):
> **[lshpy/sdrop](https://github.com/lshpy/sdrop)**

## Research interests

`Explainable AI` · `mechanistic interpretability` · `regularization and generalization` ·
`topological data analysis` · `biomedical signals and images`

## Publications

<img src="https://img.shields.io/badge/published-1B5E20?style=flat-square" alt="published">

**Obtuse stick presentation of a knot.**
Chanhyuk Choi, **Seunghyun Lee**, Sungjong No, Seungsang Oh.
*Physica Scripta* **101** (2026) 225216.
Received 20 March 2026 · accepted 22 May 2026 · published 4 June 2026.
[**[doi]**](https://doi.org/10.1088/1402-4896/ae7217)

<img src="https://img.shields.io/badge/in%20press-00695C?style=flat-square" alt="in press">

**Suppressive Dropout: A Demonstration of Explainable Channel-Selective Regularization
for Preserving Rare Features.** *Sole author.*
*Joint Proceedings of the xAI 2026 Late-breaking Work, Demos and Doctoral Consortium*,
CEUR Workshop Proceedings (ISSN 1613-0073), **pp. 225–232**.
Camera-ready 10 April 2026; presented as a poster and live demo at **xAI 2026**, the 4th
World Conference on eXplainable Artificial Intelligence, Demo Track (Paper 8770),
Fortaleza, Brazil, **1–3 July 2026**.
[**[paper]**](https://github.com/lshpy/sdrop/blob/main/paper/SDrop_XAI2026_demo.pdf)
[**[code]**](https://github.com/lshpy/sdrop)

<img src="https://img.shields.io/badge/under%20review-B26500?style=flat-square" alt="under review">

**Suppressive Dropout: An Explainable Channel-Selective Regularization Method for
Preserving Rare Features.** *Sole author.* *Neurocomputing* (Elsevier).
Submitted 10 April 2026. The journal-length extension of the paper above.

<img src="https://img.shields.io/badge/in%20preparation-546E7A?style=flat-square" alt="in preparation">

**Extended study of Suppressive Dropout, with a head-level variant for vision
transformers.** With **Prof. Luca Longo** (University College Cork).
Manuscript in preparation for *Machine Learning* (Springer), as of August 2026.

## Repositories

**Research code**

| Repository | Description |
|---|---|
| **[sdrop](https://github.com/lshpy/sdrop)** | Suppressive Dropout — reference implementation, ViT head-level variant, baselines, and the xAI 2026 paper |
| **[explainable-heart-risk](https://github.com/lshpy/explainable-heart-risk)** | Per-patient SHAP attributions for cardiovascular risk prediction (CV AUC 0.907) |

**Preliminary studies** — technical reports, not peer-reviewed, not clinically validated

| Repository | Description |
|---|---|
| [explainable-early-caries-dentex](https://github.com/lshpy/explainable-early-caries-dentex) | Early-caries detection on DENTEX, using SDrop for rare-class recall plus Grad-CAM evidence |
| [tooth-topology-persistent-homology](https://github.com/lshpy/tooth-topology-persistent-homology) | Persistent homology of tooth morphology on panoramic radiographs · v1.0.0, 4 July 2026 · [DOI](https://doi.org/10.5281/zenodo.21193193) |
| [oral-health-equity-rag](https://github.com/lshpy/oral-health-equity-rag) | Citation-first retrieval-augmented QA over oral-health literature · v1.0.1, 4 July 2026 · [DOI](https://doi.org/10.5281/zenodo.21193726) |
| [egfr-resistance-topology](https://github.com/lshpy/egfr-resistance-topology) | Persistent homology applied to EGFR targeted-therapy resistance mutations |

**Coursework and side projects**

| Repository | Description |
|---|---|
| [imen315-syllabus-meta](https://github.com/lshpy/imen315-syllabus-meta) | Meta-analysis of course design through human-factors theory |
| [trackB-simulation](https://github.com/lshpy/trackB-simulation) | ACT-R base-level activation model comparing single-exam and biweekly-quiz designs |
| [safety_map](https://github.com/lshpy/safety_map) | Children's safety map for Hwaseong City (2025 policy competition) |
| [korea-completion-map](https://github.com/lshpy/korea-completion-map) | Interactive map tracking regions of Korea visited |

## Talks and posters

| Date | Venue | Format |
|---|---|---|
| **1–3 July 2026** | xAI 2026, Fortaleza, Brazil | Poster and live demo |
| September 2025 | KU AI Forum, Korea University | Poster |
| Fall 2025 | AIML@K Workshop 2025 Fall, Korea University | Oral |
| 30 June – 3 July 2025 | 9th School on Advanced Deep Learning (SADL), Jeonbuk National University | Seminar |

## Experience

| Period | Role |
|---|---|
| Mar – Dec 2025 | **Undergraduate research intern**, DLmath Lab, Korea University, under Prof. Seungsang Oh |
| Sep – Dec 2025 | **Student researcher**, national research projects — quantum knot invariants and the spatial stability of DNA supercoils (R2411422); deep learning for speech data discrimination (M1000991) |
| Mar – Dec 2025 | **Industry collaboration with Telecons**, via DLmath Lab — thermal-imaging patient status classification for contactless monitoring in nursing hospitals |
| 2025 – present | **EEG/ECG foundation model research team**, Korea University — responsible for the ECG heartbeat-detection component |
| Feb 2026 | **IES Winter School**, King's College London — two-week module *Foundations of Artificial Intelligence*; project on adversarial pursuit over the London Underground graph, comparing heuristic, MCTS, and RL agents |

## Awards

| Year | Award |
|---|---|
| 2026 | **Silver Award**, Energy AI Workflow Education & Hackathon *(project lead)* |
| 2025 | **Startup Jinri Scholarship**, Korea University |
| 2025 | **Challenge Award**, Hwaseong City Policy Competition |
| 2024 | **Dean's List and Academic Excellence Award** *(Spring 2024)* |

## Technical

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![MNE](https://img.shields.io/badge/MNE-2E7D32?style=flat-square)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)

---

<div align="center">

## Get in touch

I read everything that comes in. Write to me if you want to use SDrop in your own
training pipeline, have found a problem with it, or work on interpretability-guided
training and want to compare notes.<br>
<sub>Bug reports and questions about the code are best filed as an issue on the relevant repository; anything else by email.</sub>

<p>
<a href="mailto:leesh4660@gmail.com"><img src="https://img.shields.io/badge/leesh4660@gmail.com-3A4A5A?style=for-the-badge&logo=gmail&logoColor=white" alt="personal email"></a>
<a href="mailto:sh200411@korea.ac.kr"><img src="https://img.shields.io/badge/sh200411@korea.ac.kr-8B0000?style=for-the-badge&logo=maildotru&logoColor=white" alt="university email"></a>
<a href="https://orcid.org/0009-0006-1926-653X"><img src="https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID"></a>
</p>

<sub>Last updated 21 August 2026</sub>

</div>
