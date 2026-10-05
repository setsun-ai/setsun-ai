## Hi there 👋

MSc **InfoBioChem** student at **Gdańsk University of Technology**, building reproducible cheminformatics and data-analysis pipelines, from molecular descriptors and QSPR models to LC-MS lipidomics. I care about validation: what a model can and cannot predict, and whether a result reproduces from the data.

- **Core:** Python · pandas / NumPy / SciPy · scikit-learn · RDKit · SQL
- **Scientific:** chemometrics · QSAR/QSPR · cheminformatics · omics statistics (LC-MS lipidomics) · mechanistic modelling
- **Other:** MATLAB · SAS · PostgreSQL · pytest and GitHub Actions

### ⭐ Featured projects

| Project | Problem → result | Tech |
|---|---|---|
| [**qspr-microplastic-sorption**](https://github.com/setsun-ai/qspr-microplastic-sorption) | Predicting pollutant sorption on PP microplastics from 35 compounds. High-Q² models were rejected for chance correlation; a 2-descriptor MLR was stable over 200 splits. One command reproduces the report, with leakage tests in CI. | Python, scikit-learn, PaDEL, MOPAC |
| [**lipidomics-human-milk-untargeted**](https://github.com/setsun-ai/lipidomics-human-milk-untargeted) | Untargeted LC-MS of human milk, month 1 vs 12. QC-driven filtering (752 → 94 features) and donor-level paired statistics, with restricted data handled through pseudonymisation and synthetic-data tests. | Python, SciPy, scikit-learn |
| [**cheminformatics-chemical-space**](https://github.com/setsun-ai/cheminformatics-chemical-space) | Does molecular representation change what "similar" means? Physchem vs MACCS vs Morgan on 90 fragrance molecules; odour class is only weakly encoded by structure. | RDKit, PubChem, PCA / t-SNE / UMAP |
| [**moodle-sync**](https://github.com/setsun-ai/moodle-sync) | A self-hosted tool that syncs Moodle files, deadlines and grades to the cloud, a calendar and notifications. Cross-platform CI, secret masking in logs, a documented data-retention table. | Python, REST APIs, GitHub Actions |

### 🎓 More coursework (MSc InfoBioChem, 2026)

- [**biochemical-process-modeling**](https://github.com/setsun-ai/biochemical-process-modeling): kinetics, CSTR and Monod chemostat fits with bootstrap CIs; spectral pKa.
- [**statistics-coursework**](https://github.com/setsun-ai/statistics-coursework): genetic association analysis in SAS; GC-MS signal processing in MATLAB.
- [**open-databases-structural-analysis**](https://github.com/setsun-ai/open-databases-structural-analysis): crystal structure of a cisplatin analogue (CSD, Hirshfeld surfaces); PCR primer design.
- [**postgresql-database-apps**](https://github.com/setsun-ai/postgresql-database-apps): normalised PostgreSQL schema with a least-privilege role.
- [**delhi-climate-analysis**](https://github.com/setsun-ai/delhi-climate-analysis): pandas data cleaning and seasonality.

### 🛠 Side projects

- [**amp-cubecoders-tg-bot**](https://github.com/setsun-ai/amp-cubecoders-tg-bot): Telegram bot for AMP game servers, with checksum-verified self-update.
- [**family-pet-bot**](https://github.com/setsun-ai/family-pet-bot): an AI "pet" for family chats, with a clear statement of what goes to the model provider.

### 🤖 A note on AI

AI-assisted development was used for implementation and documentation. Method choice, validation strategy, data-handling decisions, result verification and interpretation were reviewed and owned by me. Each repository says this in its README.

---

🇵🇱 Student studiów II stopnia na kierunku InfoBioChem na Politechnice Gdańskiej. Buduję odtwarzalne pipeline'y chemoinformatyczne i analityczne. Powyżej są projekty studenckie i poboczne; projekty studenckie mają krótką sekcję po polsku.
