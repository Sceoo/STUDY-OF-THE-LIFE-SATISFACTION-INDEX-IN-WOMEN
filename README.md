### Project Name
Study of the Life Satisfaction Index in Women

#### -- Project Status: [in revision]

### Genesis
This is a final project of the course **[Code First Girls Degree](https://codefirstgirls.com/courses/cfgdegree/)** created by the following people, whose participation in the course was sponsored by **[Credit Suisse](https://www.credit-suisse.com/)**, listed in alphabetical order:
|Name     |  GitHub Account   | 
|---------|-----------------|
|Ana Tavares | (https://github.com/anatava)
|Anna Dąbrowska | (https://github.com/AnnaDabrowska)
|Elena Garcia Gomez | (https://github.com/elepg261)
|Jasmine Ross | (https://github.com/jasmineemross)
|Milena Haładaj | (https://github.com/Sceoo)
|Michalina Bienkiewicz | (https://github.com/MichalinaBienkiewicz)
|Paulina Nanikowska | (https://github.com/PaulinaNan)
|Sayo Agunbiade - group supervisor | (https://github.com/sayoiscool)

### Project Intro
The purpose of this project is to analyze women's life satisfaction to raise awareness of the problem of gender inequality by performing descriptive analysis of the below-listed sources using Python:
- the Better Life Index data set provided by OECD (Organization for Economic Cooperation and Development), analyzed factors: employment rate, long-term unemployment rate, life expectancy, self-reported health, employees working very long hours, time devoted to leisure and personal care, educational attainment, students' skills, expected years in education, water quality, homicide rates, feeling safe walking alone at night, social network support, life satisfaction. The data provided in the source and analyzed comes from 2019 and 2020, with a few exceptions differing by country/factor that date back to 2006-2018. 
- the GDP data set provided by OECD. The data analyzed comes from the years 2020-2022.

### Methods Used
* Data loading, exploration, cleaning, summary - libraries: pandas, pandassdmx, requests.
* Mathematical operations - library: numpy
* Predictive modeling and evaluation of the performance of predictive models - library: sci-kit-learn
* Data visualization, correlation analysis - libraries: matplotlib, seaborn, plotly.

### Technologies
* Python and its libraries
* Jupyter
* GitHub

### Getting Started
1. For the project analysis we used Jupyter Notebook. To open the project file please click [here](https://github.com/Sceoo/STUDY-OF-THE-LIFE-SATISFACTION-INDEX-IN-WOMEN/blob/cfg-final-project-submission/study_life_satisfaction_women_notebook.ipynb) or open the file "study_life_satisfaction_women_notebook.ipynb" in this repository. 
2. It may be required to pip install 'pandasdmx' library the first time running this notebook, the command is included within the notebook. In case you want to install it from your terminal, please use the code 'pip install pandasdmx'.
3. Optionally, you can clone this repo, for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/).
4. Raw Data is being kept [here](https://github.com/Sceoo/STUDY-OF-THE-LIFE-SATISFACTION-INDEX-IN-WOMEN/tree/cfg-final-project-submission/data) within this repo. After 06.06.2023, if the repository is still private, in order to access the raw data one needs to generate one's own token in GitHub, use the new token in the code above by replacing value for 'autorization' in the headers dictionary with the new token. The notification about it is located within the file on the specific line of code.
5. GDP data set is accessed using API, the code to access the API is included within the notebook. If there is an error or the website does not respond, the particular line of code reads the data from the CSV file hosted on GitHub using the exception handling.
