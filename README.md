## Seunghyun Lee

Undergraduate researcher at Korea University — B.S. in Industrial and Management
Engineering with a double major in Mathematics (March 2023 – expected February 2027).
Undergraduate research intern at [DLmath Lab](https://github.com/DLmath-Lab) under
Prof. Seungsang Oh since March 2025.

I work on **explainable regularization**: using interpretability signals to decide what
a network should suppress *during* training, instead of reading explanations off a model
after it has finished learning. The method started with convolutional channels, now
covers vision-transformer attention heads, and I am extending the same score to token
distributions in reasoning models.

ORCID [0009-0006-1926-653X](https://orcid.org/0009-0006-1926-653X) ·
[leesh4660@gmail.com](mailto:leesh4660@gmail.com)

### Research interests

Explainable AI and mechanistic interpretability · regularization and generalization ·
topological data analysis · applications to biomedical signals and images.

### Publications

**Obtuse stick presentation of a knot.**
Chanhyuk Choi, **Seunghyun Lee**, Sungjong No, Seungsang Oh.
*Physica Scripta* **101** (2026) 225216.
Received 20 March 2026 · accepted 22 May 2026 · published 4 June 2026.
[[doi]](https://doi.org/10.1088/1402-4896/ae7217)

**Suppressive Dropout: A Demonstration of Explainable Channel-Selective Regularization
for Preserving Rare Features.** Sole author.
*Joint Proceedings of the xAI 2026 Late-breaking Work, Demos and Doctoral Consortium*,
CEUR Workshop Proceedings (ISSN 1613-0073), pp. 225–232 — *volume in press.*
Camera-ready 10 April 2026; presented as a poster and live demo at **xAI 2026**, the 4th
World Conference on eXplainable Artificial Intelligence, Demo Track (Paper 8770),
Fortaleza, Brazil, 1–3 July 2026.
[[paper]](https://github.com/lshpy/sdrop/blob/main/paper/SDrop_XAI2026_demo.pdf)
[[code]](https://github.com/lshpy/sdrop)

**Suppressive Dropout: An Explainable Channel-Selective Regularization Method for
Preserving Rare Features.** Sole author. *Neurocomputing* (Elsevier).
Submitted 10 April 2026, under review. The journal-length extension of the paper above.

**Extended study of Suppressive Dropout, with a head-level variant for vision
transformers.** With Prof. Luca Longo (University College Cork).
Manuscript in preparation for *Machine Learning* (Springer), as of August 2026.

### What SDrop does, in one paragraph

Standard dropout removes units at random; targeted dropout removes the weakest ones.
SDrop removes the **most dominant** channels — those that are both high-energy and
spatially diffuse — on the argument that, through lateral inhibition, they monopolize
the representation and starve detectors for rare or minority-class features of gradient.
Dominance is scored by `s_c = E_c (1 − P_c)`, computed from the activation map in a
single forward pass, so the interpretability signal is cheap enough to run at every step
of training. Reference implementation, the ViT head-level variant, and baselines
(DropBlock, SE, CBAM) are in [lshpy/sdrop](https://github.com/lshpy/sdrop).

### Repositories

**Research code**

| Repository | Description |
|---|---|
| [sdrop](https://github.com/lshpy/sdrop) | Suppressive Dropout — reference implementation, ViT head-level variant, baselines, and the xAI 2026 paper |
| [explainable-heart-risk](https://github.com/lshpy/explainable-heart-risk) | Per-patient SHAP attributions for cardiovascular risk prediction (CV AUC 0.907) |

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

### Talks and posters

| Date | Venue | Format |
|---|---|---|
| 1–3 July 2026 | xAI 2026, Fortaleza, Brazil | Poster and live demo |
| September 2025 | KU AI Forum, Korea University | Poster |
| Fall 2025 | AIML@K Workshop 2025 Fall, Korea University | Oral |
| 30 June – 3 July 2025 | 9th School on Advanced Deep Learning (SADL), Jeonbuk National University | Seminar |

### Experience

- **Undergraduate research intern**, DLmath Lab, Korea University (March 2025 – present)
- **Student researcher**, national research projects (September – December 2025):
  quantum knot invariants and the spatial stability of DNA supercoils (R2411422), and
  deep learning for speech data discrimination (M1000991)
- **Industry collaboration with Telecons**, via DLmath Lab (March – December 2025) —
  thermal-imaging patient status classification for contactless monitoring in
  nursing hospitals
- **EEG/ECG foundation model research team**, Korea University (2025 – present) —
  responsible for the ECG heartbeat-detection component
- **IES Winter School 2026**, King's College London (February 2026) — two-week module
  *Foundations of Artificial Intelligence*; project on adversarial pursuit over the
  London Underground graph, comparing heuristic, MCTS, and RL agents

### Awards

| Year | Award |
|---|---|
| 2026 | Silver Award, Energy AI Workflow Education & Hackathon (project lead) |
| 2025 | Startup Jinri Scholarship, Korea University |
| 2025 | Challenge Award, Hwaseong City Policy Competition |
| 2024 | Dean's List and Academic Excellence Award (Spring 2024) |

### Technical

Python, PyTorch, TensorFlow, scikit-learn, Hugging Face, MNE, Neo4j, SQL, n8n, LaTeX

### Contact

I read everything that comes in, and I am glad to hear from you if you want to use SDrop
in your own training pipeline, have found a problem with it, or work on
interpretability-guided training and want to compare notes. Bug reports and questions
about the code are best filed as an issue on the relevant repository; anything else by
email.

[leesh4660@gmail.com](mailto:leesh4660@gmail.com) ·
[sh200411@korea.ac.kr](mailto:sh200411@korea.ac.kr) ·
ORCID [0009-0006-1926-653X](https://orcid.org/0009-0006-1926-653X)

<sub>Last updated 21 August 2026.</sub>
