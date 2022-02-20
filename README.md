# 07_etf_passive_investing
Analysis of ETF data and supporting visualizations

This jupyter notebook offers insights into ETF investing using data from a database with respresentative visualizations.

## Technologies

This passive investing analyzer is a Jupyter notebook built with the following technologies:

### Language

| Language | Version |
|----------|---------|
| Python   | 3.7.11  |

### Libraries and Frameworks

| Component | Version |
|-----------|---------|
| Anaconda  | 1.9.0   |
| Conda     | 4.11.0  |
| Jupyter   | 3.2.1   |

### Operating System

This version of the software is operating system agnostic.

---
## Installation Guide

### Pre-requisites

- Python 3.7
- Anaconda 1.9.0
- Conda 4.11.0
- Jupyter 3.2.1
- A conda environment created specially for this project.


### Required Python Packages

- ipykernel
- hvplot
- pyviz
- sqlalchemy

### Running the Analyzer

Install a new conda environment for this project. We will be using `python 3.7.11` for this repository.

```bash
conda create -n dev_etf python=3.7.11 anaconda
```

Activate the newly created environment and verify the python version.

```bash
conda activate dev_etf
python --version
```

Install and add the ipykernel environment to your jupyter notebook.

```bash
conda install -c anaconda ipykernel
python -m ipykernel install --user --name=dev_etf
```

Install the required python packages.

```bash
conda install hvplot
conda install sqlalchemy
```

Clone the remote repository to your local developer environment and `cd` into the folder.
```bash
git clone git@github.com:msashokkumar/07_etf_passive_investing.git
cd 07_etf_passive_investing
```

Start the jupyter lab server from the terminal as follows:

```bash
jupyter lab
```

Open and execute the file `etf_analyzer.ipynb`

---
## Contributors

```markdown
{
  "name": "Ashok Kumar Madhavi Selvaraj",
  "email": "ashok.ms.kumar@gmail.com",
  "linkedin": "https://www.linkedin.com/in/msashokkumar"
}
```
---

## License

Please refer to LICENSE.