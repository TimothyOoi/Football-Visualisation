# Visualising the European Football Leagues across the 2021/2022 Season

This repository contains a data visualisation displaying insights on five European football leagues across the 2021/2022 season.
The final visualisation can be viewed [here](https://timothyooi.github.io/Football-Visualisation/vis_assignment/).

## About

The aim of the visualisation is to display interesting player statistics and allow viewers to understand several insights on the football leagues.
This visualisation appeals to football enthusiasts that are interested about the underlying statistics behind football results better. 
The visualisation contains descriptions for football metrics to guide viewers without knowledge on football through my visualisation. 
My visualisation uses datasets prepared by [Sports Reference](https://fbref.com/en/comps/Big5/2021-2022/2021-2022-Big-5-European-Leagues-Stats), a third party sports data providers.

## Built With
* [Vega-Lite](https://vega.github.io/vega-lite/)
* ![html][html-img]
* ![CSS][css-img]
* ![JavaScript][JavaScript-img]
* [![Python][Python-img]][Python-url]
* [![Jupyter][jupyter-img]][jupyter-url]

## Repository Structure

The repository is organized as follows:
- `vis_assignment/`: This directory contains final visualisation which can be viewed [here](https://timothyooi.github.io/Football-Visualisation/vis_assignment/).
  - `css/`: This directory contains the CSS files used for styling the visualisation webpage.
  - `data/`: This subdirectory contains the datasets used for the visualisations.
  - `js/`: This directory contains the JavaScript files used for the web page functionality.
  - `index.html`: The HTML file that hosts the web page and displays the visualizations.
- `week9_hw`: This directory contains a draft map visualisation, subsequently improved in the final visualisation. It can be viewed [here](https://timothyooi.github.io/Football-Visualisation/week9_hw/)
- `week10_hw`: This directory contains an interactive visualisation, subsequently improved in the final visualisation. It can be viewed [here](https://timothyooi.github.io/Football-Visualisation/week10_hw/)
- `notebooks/`: This directory contains Jupyter Notebooks used for web scraping, data cleaning and compiling the final visualisation datasets.
- `datasets/`: This directory stores the raw datasets collected via web scraping.
- `vis_data/`: This directory stores the clean datasets output from the data cleaning.
- `logs/`: This directory stores the log messages from the web scraper.

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[JavaScript-img]: https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E
[Python-img]: https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue
[Python-url]: https://www.python.org/
[html-img]: https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white
[css-img]: https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white
[jupyter-img]: https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white
[jupyter-url]: https://jupyter.org/
