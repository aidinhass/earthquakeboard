
# EQuake Board

## Background

## Methodology

## Data

## Report

## Requirements

## Directory Structure
```
.
├── docs                <- Documents related to this project
├── images              <- Images for README.md files
├── notebooks           <- Ipythoon Notebook files
├── reports             <- Generated analysis as HTML, PDF, Latex, etc.
│   ├── figures         <- Generated graphics and figures used in reporting
│   └── logs            <- Generated log files  
└── equakeboard
    ├── conf
    ├── data            <- data utilized in this project
    │   ├── ext
    │   ├── int
    │   └── raw
    ├── src             <- Source files used in this project
    ├── static          <- CSS/SCSS/JS/Vedoer source files
    └── templates       <- Flask templates 
```
## Installation
Install python dependencies from  `requirements.txt` using conda.
```bash
conda install --yes --file conda-requirements.txt
```

Or create a new conda environment `<new-env-name>` by importing a copy of the working conda environment `conda-equakeboard.yml` at the project root directory:
```bash
conda env create --name <new-env-name> -f conda-earthquakeboard.yml
```
## Usage
```bash
python run.py
```
## References

## To Do
- [ ] TBA

## License
MIT License

