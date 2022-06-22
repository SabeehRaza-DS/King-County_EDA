# EDA-project: King County Housing
## Problem Statement: 
Stakeholder wants to buy 2 houses (central and suburban area) in King County housing

Stakeholder Profile

- Family: 2 people
- City House: Fast and central
- Country House: Best timing and non-renovated

## Data

King County Housing Data: [Data link](https://geodacenter.github.io/data-and-lab/KingCounty-HouseSales2015/)

## Approach

- Understanding data set using EDA techniques
- Data visualization for better understanding
- Apply Stakeholder criterion
- Present proposal to Stakeholder

## Virtual Environment

This repo contains a requirements.txt file with a list of all the packages and dependencies you will need.

```Bash
pyenv local 3.9.8
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
````
### Workflow

- [King count data wrangling notebook](EDA_housing.ipynb)
- [Centrally located houses](city_map.html)
- [Suburban houses](urban_map.html)
- [Stakeholder presentation](House_Buying_Proposal.pdf)