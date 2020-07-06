# COVID19-Jupyter

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/WanderWashington/COVID19-Jupyter/master)
[![Updates](https://pyup.io/repos/github/WanderWashington/COVID19-Jupyter/shield.svg)](https://pyup.io/repos/github/WanderWashington/COVID19-Jupyter/)
[![Python 3](https://pyup.io/repos/github/WanderWashington/COVID19-Jupyter/python-3-shield.svg)](https://pyup.io/repos/github/WanderWashington/COVID19-Jupyter/)


The databases about the COVID19 can be downloaded at this site: https://ourworldindata.org/coronavirus-source-data

Brazil databases can be downloaded at this site: https://coronavirus.saude.gov.br


## Installation:
1.  Install the requirements file, with the command:

    ```pip install -r requirements.txt```

2.  In the prompt, run the command:

    ```jupyter-notebook```


### Notebooks
1.   In ```COVID19.ipynb``` is possible see data about the cases around the world. At this ipynb, could be used a function to plot by country through some functions present at this file.

2.  In ```Covid19 - Brazil.ipynb``` is possible see data just about the Brazil. Here, we have a function to create charts foreach state in Brazil. The function creates a folder with the state abbreviation and save inside there, the correspondent Chart. At this momment have six functions that can be used:
    * plotNewCasesByUF  - Create charts with the  new cases
    * plotNewDeathsByUF - Create charts with the  new deaths
    * plotAccumulatedCasesByUF - Create charts with the accumulated cases
    * plotAccumulatedDeathsByUF - Create charts with the  accumulated aeaths
    * plotNewRecoveredByUF -Create charts with the new recovered cases. Obs: the official data about covid 19 in Brazil, dont have informations about newRecovered, but have the column in the datasheet, probably, if use this function, the charts will appear blan.
    * plotUnderSupervisionCasesByUF - Create charts with the cases under supervision.Obs: the official data about covid 19  in Brazil, dont have informations about newRecovered, but have the column in the datasheet, probably, if use this function, the charts will appear blank.
 
 
  
