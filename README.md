# SURGE-Ahead observational and AI development study
This GitHub repository contains the analysis and supporting materials for the prospective observational cohort study examining the appropriateness of discharge destinations for geriatric surgical inpatients within the Supporting SURgery with GEriatric Co-Management and AI (SURGE-Ahead) project.

## Project Overview
### Background
This study, part of the SURGE-Ahead project, investigates discrepancies between standard of care discharge decisions and expert geriatrician recommendations for surgical inpatients aged 70+. It identifies key factors influencing discharge decisions and associated outcomes.

### Key Findings
- 27% Incongruence between standard of care and expert recommendations for discharge destinations.
- Incongruent discharge decisions linked to increased frailty, dependence in ADLs, reduced mobility, higher readmission rates at 3-month follow-up, and decline in functional status (Barthel Index and Charité Mobility Index scores).

## Repository Structure
- [`data`](./data): Source data for the analysis
- [`LICENSE`](./LICENSE): License for this project (MIT License, as per the project's uniform approach)
- [`OKIE_data.csv`](./OKIE_data.csv): Pre-processed data for the study
- [`OKIE_main.ipynb`](./OKIE_main.ipynb): Jupyter Notebook for analysis (Dependencies: numpy, pandas, scipy, statsmodels, matplotlib)
- [`figure1.png`](./figure1.png): STROBE Chart from the accompanying manuscript
- [`figure2.png`](./figure2.png): Bar chart of the primary outcome
- [`supplementary_tables.xlsx`](./supplementary_tables.xlsx): Additional tables not included in the main manuscript

## Getting Started
1. Clone the Repository: `git clone https://github.com/IfGF-UUlm/SA_OKIE.git`
2. Create Virtual Environment: `python3 -m venv surgeahead`
3. Activate Virtual Environment (OS-Dependent):
    - Windows: `surgeahead\Scripts\activate`
    - macOS/Linux: `source surgeahead/bin/activate`
4. Install Dependencies: `pip install numpy pandas scipy statsmodels matplotlib jupyter`

Note: You may need to install jupyter on your Python base installation as well.

### Explore the Analysis:
- Open [`OKIE_main.ipynb`](./OKIE_main.ipynb) in your Jupyter environment.

Note: You can also explore the Jupyter Notebook in GitHub. However, you cannot run cells this way.

#### The analysis notebook utilizes:
- Python 3.x
- numpy
- pandas
- scipy
- statsmodels
- matplotlib

## License
This project is licensed under the MIT License.

## Citation
For academic use, please cite the underlying manuscript (details forthcoming, provided once published):

[pending]

## Contact
Questions, Feedback, or Concerns? Reach out to thomas.kocar@uni-ulm.de.
