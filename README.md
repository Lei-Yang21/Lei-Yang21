# Hi, I'm Lei Yang 👋

**Data Science Graduate · Based in Arlon, Belgium**

Welcome to my GitHub! My projects explore machine learning, computer vision, and data interpretation using language models.

Here you'll find my master's thesis work, university projects, and experiments, with code and notebooks to explore the methods behind them.

[Explore my projects](#selected-projects) · [Discover my thesis](https://github.com/Lei-Yang21/SemTab) · [All repositories](https://github.com/Lei-Yang21?tab=repositories)

## About me

- **Data science & machine learning**: preparing data, building models, and comparing their performance.
- **Language models & knowledge representation**: exploring how small language models can interpret tables and link their contents to Wikidata.
- **Computer vision & algorithms**: working with images and algorithms that classify or describe them.

## Master's Thesis: SemTab

### [The Role of Small Language Models in Web Table Interpretation](https://github.com/Lei-Yang21/SemTab)

My master's thesis explores how small language models can interpret web tables. The goal is to link cells to Wikidata entities, identify column types, and determine relationships between columns.

The repository includes a preprocessing, candidate retrieval, and ranking pipeline, alongside LoRA / QLoRA fine-tuning experiments and evaluation tools.

**Selected results**: Cell Entity Annotation (CEA), linking table cells to Wikidata entities:

- **Fine-tuning gains:** on the main WikidataTables2024R1 evaluation set, fine-tuning Qwen2.5 3B improved CEA F1 from **0.717 to 0.778** (+6.1 percentage points) compared with its base context-aware configuration.
- **Best evaluated configuration:** fine-tuned Qwen2.5 7B achieved **0.836 CEA F1** on the main set and **0.814** on a separate held-out set of **500 tables and 22,448 target cells**.
- **Post-thesis evaluation:** on MammoTab, the updated pipeline supporting NIL annotations (cells with no matching entity) improved CEA F1 from **0.550 to 0.687** with fine-tuning, compared with the base context-aware SLM configuration. These additional results were presented at the thesis defense.

The [SemTab README](https://github.com/Lei-Yang21/SemTab#readme) covers the project structure and setup steps.

## Selected projects

| Project | What you'll find | Area |
| --- | --- | --- |
| [Belgium Railway](https://github.com/Lei-Yang21/Belgium-Railway) | Data modeling and PostgreSQL/PostGIS database design, deployed with Docker. Reduced the punctuality dataset from **37 GB to 21 GB (≈43%)** by encoding string values as integer IDs. Analysis and prediction of train delays using weather, calendar and geospatial data, including delay propagation across stops. | Data engineering & machine learning |
| [Fake or Proof](https://github.com/Lei-Yang21/Fake-or-Proof) · [Live demo](https://fakeorproof-streamlit-ffck35mifa-ew.a.run.app) | Streamlit application using MobileNetV2 to estimate whether an image is AI-generated or real, with GradCAM visualizations. Deployed on Google Cloud Run with a Vertex AI training pipeline. | Computer vision & cloud deployment |
| [Taxi Destination Prediction](https://github.com/Lei-Yang21/predict-taxi) | Data preparation and comparison of classical models and an LSTM to predict taxi trip destinations. | Machine learning |
| [Image Classifier](https://github.com/Lei-Yang21/Image-classifier) | Sketch classification using nearest neighbours and Dynamic Time Warping, implemented in C. Built with [Simon Gardier](https://github.com/simon-gardier). | Computer vision & algorithms |
| [Sudoku Solver](https://github.com/Lei-Yang21/Sudoku-Solver) | Solving Sudoku puzzles using a SAT solver. | Logic & reasoning |
| [Foundations of Data Science](https://github.com/Lei-Yang21/Foundation-of-Data-sciences) | Analysis of pulse oximetry data and estimation of blood oxygen saturation (SpO₂) from red and infrared PPG signals. Includes data cleaning, exploratory analysis, probabilistic modeling and Bayesian inference with MCMC to quantify uncertainty and assess model limitations. | Biomedical data analysis & Bayesian inference |

