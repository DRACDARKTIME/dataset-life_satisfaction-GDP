# Dataset about life satisfaction and GDP

This repository contains a dataset that merges several sources into a single file. The data can be divided into two groups: life satisfaction data from Wellbeing Research Centre (2025) [OurWorldInData.org](https://ourworldindata.org/grapher/happiness-cantril-ladder?tab=line) and Gross Domestic Product (GDP) data from the World Bank [OurWorldInData.org](https://ourworldindata.org/grapher/gdp-per-capita-worldbank?tab=line&time=2021..latest&overlay=download-data#sources-and-processing). The data were compiled for the period 2021–2024 and combined into one dataset.

---
## Comands used for making the repository with git
``` bash
echo "# dataset-life_satisfaction-GDP" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin git@github.com:DRACDARKTIME/dataset-life_satisfaction-GDP.git

git push -u origin main
```
We also used `git add .`, `git commit -m <message>`, `git pull origin main`, `git push origin main` for each update.