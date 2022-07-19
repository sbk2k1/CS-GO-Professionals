
# CS-GO-Professionals

[![Contributors](https://img.shields.io/github/contributors/dsckgec/project-template.svg)](https://github.com/dsckgec/project-template/graphs/contributors) [![Forks](https://img.shields.io/github/forks/dsckgec/project-template.svg)](https://github.com/dsckgec/project-template/network/members) [![Issues](https://img.shields.io/github/issues/dsckgec/project-template.svg)](https://github.com/dsckgec/project-template/issues) [![Pull Request](https://img.shields.io/github/issues-pr-closed-raw/dsckgec/project-template)](https://github.com/dsckgec/project-template/pulls)


![CSGO](https://cdn.akamai.steamstatic.com/steam/apps/730/ss_60b4f959497899515f46012df805b0006ef21af6.1920x1080.jpg?t=1641233427)


## Contents

1. [Description](#description)
1. [Project structure](#project-structure)
1. [Getting started](#getting-started)
1. [Contributing](#contributing)
1. [Authors](#authors)
1. [License](#license)


## Description

Counter-Strike: Global Offensive is a 2012 multiplayer first-person shooter developed by Valve and Hidden Path Entertainment. It is the fourth game in the Counter-Strike series.
It is one of the biggest eSports title out there. In this project we scrape and work on a dataset of all CSGO Athletes.

The entire flow of the project includes:
- Scrape the Dataset from this [Website](https://www.hltv.org/stats/players)
- Perform Feature Engineering to create insightful columns
- Perform Exploratory Data Analysis to create insights and meaningful dashboards

## Project structure

```
  ├── Transaction/        
  ├── scraping notebook.ipynb             Notebook for Scraping the website
  ├── CSGO Player Dataset.csv             Original Dataset about CSGO Player Dataset
```
## Getting started


### Prerequisites

#### Software Needed
 
  1. A web browser. 

         OR
         
  3. Anaconda software.

#### Knowledge Needed
- Very basic understanding of git and github:

    1.  What are repositories (local - remote - upstream), issues, pull requests
    2.   How to clone a repository, how to fork a repository, how to set upstreams
    3.   Adding, committing, pulling, pushing changes to remote repositories

- For EDA and Visualisation
 
    1. Basic syntax and working of ```python```.(This is a must)
    2. Basic knowledge of ```pandas``` library. [Reading this blog might help.](https://www.dataquest.io/blog/pandas-python-tutorial/)
    3. Basic knowledge of ```matplotlib``` library. [Reading this blog might help.](https://blog.quantinsti.com/python-matplotlib-tutorial/)
    4. Basic knowledge of ```seaborn``` library. [Reading this blog might help.](https://www.mygreatlearning.com/blog/seaborn-tutorial/)
    5. Basic knowledge of ```scikit learn``` library. [Reading this blog might help.](https://www.dataquest.io/blog/sci-kit-learn-tutorial/)

  However the code is well explained, so anyone knowing the basics of Python can get a idea of what's happenning and contribute to this.

### Installing

There are two ways of running the code.
  1. Running the code on web browser.(Google Colab) [Recommended]
      - Head on to [Google colab](https://colab.research.google.com/)
      - Then click on ```Upload Notebook``` Tab.
      - Upload the notebook that you got from this repo.
        ![Colab-1](https://res.cloudinary.com/codehackerone/image/upload/v1618463907/ML/colab-2_c14swf.png)
      - Connect with the runtime.
        ![Colab-2](https://res.cloudinary.com/codehackerone/image/upload/v1618464955/ML/Colab-3_da822c.png)
      - Upload your dataset.
        ![Colab-3](https://res.cloudinary.com/codehackerone/image/upload/v1618464958/ML/Colab-04_sxfyjx.png)
      - Then Click on ```Run All```.
        ![Colab-4](https://res.cloudinary.com/codehackerone/image/upload/v1618465413/ML/colab-5_i92bzp.png)
      - Start Editing.

  2. You can also run the code locally in your computer by installing Anaconda.
      - Install Anaconda. [Follow these steps to install Anaconda on your computer](https://www.edureka.co/blog/python-anaconda-tutorial/#:~:text=on%20our%20systems.-,Installation%20And%20Setup,the%20instructions%20in%20the%20setup.)
      - Install jupyter notebook using ```conda```. [Follow these steps to install jupyter notebook.](https://test-jupyter.readthedocs.io/en/latest/install.html)
      - Make sure to install ```pandas```,```matplotlib```,```seaborn``` and ```scikit-learn``` to run the notebook.
      - Start Editing.


## Contributing

Please read [contributing.md](contributing.md) for details on our code of conduct, and the process for submitting pull requests to us.


## Authors

- [@sbk2k1](https://github.com/sbk2k1)
- [@AryaChakraborty](https://github.com/AryaChakraborty)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.