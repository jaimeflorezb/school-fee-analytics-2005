# School Fee Analytics 2005

This repository reconstructs and documents an undergraduate Economics project
developed at Universidad Autónoma de Occidente, Colombia, in 2005.

The project examined how household socioeconomic characteristics could be used
to design a school tuition and fee system consistent with affordability, equity,
willingness to pay, and the financial sustainability of the educational
institution.

## Original study

**Title:**  
*Metodología para la determinación de tarifas con base a los indicadores
socioeconómicos de la familia: el caso del Colegio Luis Horacio Gómez*

**Authors:**

- Jaime Flórez Bolaños
- Lear Yadim Murillo Henao

**Institution:** Universidad Autónoma de Occidente  
**Program:** Economics  
**Year:** 2005

## Project overview

The original study combined household socioeconomic information, econometric
modeling, willingness-to-pay analysis, affordability constraints, and financial
scenario evaluation to develop alternative school fee structures.

From a contemporary data analytics perspective, the project contains several
analytical components:

- Descriptive analytics
- Econometric modeling
- Predictive analysis
- Household segmentation
- Scenario analysis
- Prescriptive decision-making
- Financial analysis

The original analysis evaluated several functional forms, including linear,
lin-log, log-lin, and log-log specifications, together with different
combinations of socioeconomic variables.

Model selection considered statistical significance, goodness of fit,
expected coefficient signs, residual behavior, and predictive usefulness.

## Analytical workflow

The original project can be summarized as:

Household socioeconomic data

→ Data coding and systematization

→ Descriptive socioeconomic analysis

→ Econometric model estimation

→ Model comparison and selection

→ School fee prediction

→ Ability-to-pay assessment

→ Willingness-to-pay analysis

→ Household income segmentation

→ Alternative tariff scenarios

→ Financial sustainability evaluation

→ Recommended fee structure

## Repository objectives

This repository has four main objectives:

1. Preserve the analytical logic of the original 2005 project.
2. Reproduce the original econometric and descriptive results using modern
   reproducible tools.
3. Provide downloadable replication datasets and documentation.
4. Compare the original methodology with a modern econometric re-estimation.

## Original analysis and modern re-estimation

The repository distinguishes between two analytical exercises.

### Original analysis — 2005

The original study relied on classical applied econometrics and economic
criteria for model selection.

The original methodology did not use modern machine-learning procedures such
as train/test splitting or cross-validation. Instead, model evaluation relied
on econometric diagnostics, theoretical consistency, goodness of fit, and
predictive usefulness.

### Modern re-estimation

A separate section of the repository reproduces and extends the original
analysis using contemporary tools.

Potential extensions include:

- Robust standard errors
- Out-of-sample evaluation
- Cross-validation
- Alternative model specifications
- Sensitivity analysis
- Modern visualization
- Reproducible Python workflows

These extensions are clearly separated from the original 2005 methodology.

## Data

The original project used household-level socioeconomic information.

This repository provides public replication datasets containing the analytical
information required to reproduce the reported models, descriptive results,
and tariff scenarios.

The original administrative files are not distributed directly because they
contain potentially identifiable household and student information.

Public replication files are documented in:

`data/README.md`

and

`data/replication/data_dictionary.csv`

## Reproducibility

Replication files are organized according to the analytical component they
reproduce.

### Econometric models

`data/replication/model_data_2005.csv`

contains the analytical observations required to reproduce the original
econometric specifications.

### Descriptive analysis

`data/replication/descriptive_data_2005.csv`

contains the information required to reproduce the main socioeconomic
descriptive results.

### Tariff scenarios

`data/replication/tariff_scenarios_2005.csv`

contains the analytical information required to reproduce the alternative
school fee scenarios and financial calculations.

## Software

The original econometric analysis was conducted using EViews.

The replication and modern re-estimation are being developed using:

- Python
- pandas
- statsmodels
- scikit-learn
- matplotlib
- Jupyter Notebook

## Repository structure

```text
data/        Replication datasets and documentation
notebooks/   Reproducible analytical notebooks
scripts/     Python replication scripts
results/     Tables and figures
docs/        Methodology and replication documentation
