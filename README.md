# Pokemon Popularity
<img src="https://upload.wikimedia.org/wikipedia/commons/9/98/International_Pok%C3%A9mon_logo.svg" alt="pokemon banner" width="500" height="300">

## About
What makes a Pokemon Popular? Let's dig in and see what we can find out. We will be looking at the video game series developed by Game Freak and published by Nintendo. This is my Capstone Project for Code:Louisville

Here are the Pokemon attributes we will be looking at to see how they correlate with their popularity:

- Stats
- Primary color
- Shape
- Generation introduced
- Legendary/Mythical

## Data Sources
CSVs:
- [Kaggle Complete Pokemon Data Set | complete-pokemon-set.csv](https://www.kaggle.com/datasets/kylekohnen/complete-pokemon-data-set)
- [Results from a survey on Reddit | Favourite_Pokemon_responses-Results.csv](https://docs.google.com/spreadsheets/d/1c16Wh4AawHGbTi3Eq1DGZQdM4FMUlJO1YwXJZ_ylRvg/edit#gid=557303698)

## Installation
- First you need to have Python installed. This project was developed using Python 3.11.4. If you do not have Python you can download it from the [official Python website](https://www.python.org/downloads/).
- You will also need Git to clone this repository. If you don't have Git, you can download it from the [official Git website](https://git-scm.com/downloads).

You will then need to clone this repo. To do so, open Git Bash/Terminal and navigate to where you want the directory where you want the repo cloned to.

To clone, run the following command:

```
git clone https://github.com/LeeMerrow/Pokemon-Popularity
```
It is recommended to make a virtual enviroment to have all dependencies isolated from your system's Python enviroment.

##  Virutal Environment Instructions
1. After you have cloned the repo to your machine, navigate to the project 
folder in GitBash/Terminal.
1. Create a virtual environment in the project folder. 
1. Activate the virtual environment.
1. Install the required packages. 
1. When you are done working on the repo, deactivate the virtual environment.

Virtual Environment Commands
| Command | Linux/Mac | GitBash |
| ------- | --------- | ------- |
| Create | `python3 -m venv venv` | `python -m venv venv` |
| Activate | `source venv/bin/activate` | `source venv/Scripts/activate` |
| Install | `pip install -r requirements.txt` | `pip install -r requirements.txt` |
| Deactivate | `deactivate` | `deactivate` |

## Data Analysis Capstone Features List
Here are the features that I have used for this project

### 1. Loading data
Read two data files (CSV)
### 2. Clean and operate on the data while combining them
Clean data and perform a pandas merge on two values and calculate a mean value
### 3. Visualize / Present data
Make 3+ seaborn visualizations
### 4. Best practices: Enhance project to a higher tier
Utilize a virtual environment and inclued instructions in README file
### 5. Interpretation of data
Annotate in code and markdown cells in Jupyter Notebook, and README file

## Understanding Pokemon Terminology
First lets dive into what I mean by shape for Pokemon. There are currently 14 shapes that a pokemon can be slit into. They are as follows

### <img src="<img src="https://archives.bulbagarden.net/media/upload/d/da/Body01.png" alt="head shape" width="32" height="32">  Pokémon consisting of only a head

### <img src="<img src="https://archives.bulbagarden.net/media/upload/d/da/Body07.png" alt="legs shape" width="32" height="32">  Pokémon consisting of only a head

### <img src="<img src="https://archives.bulbagarden.net/media/upload/d/da/Body03.png" alt="fins shape" width="32" height="32">  Pokémon with fins

### <img src="<img src="https://archives.bulbagarden.net/media/upload/d/da/Body14.png" alt="insectoid shape" width="32" height="32">  Pokémon with an insectoid body

### <img src="<img src="https://archives.bulbagarden.net/media/upload/d/da/Body08.png" alt="quadruped shape" width="32" height="32">  Pokémon with a quadruped body

### <img src="<img src="https://archives.bulbagarden.net/media/upload/d/da/Body13.png" alt="multi_wing shape" width="32" height="32">  Pokémon with two or more pairs of wings

### <img src="<img src="https://archives.bulbagarden.net/media/upload/d/da/Body11.png" alt="multi_bodies shape" width="32" height="32">  Pokémon consisting of multiple bodies

### <img src="<img src="https://archives.bulbagarden.net/media/upload/d/da/Body10.png" alt="tentacles shape" width="32" height="32">  Pokémon with tentacles or a multiped body

### <img src="<img src="https://archives.bulbagarden.net/media/upload/d/da/Body05.png" alt="head_base shape" width="32" height="32">  Pokémon consisting of a head and a base

### <img src="<img src="https://archives.bulbagarden.net/media/upload/d/da/Body06.png" alt="bipedal_tail shape" width="32" height="32">  Pokémon with a bipedal, tailed form

### <img src="<img src="https://archives.bulbagarden.net/media/upload/d/da/Body12.png" alt="bipedal_tailless shape" width="32" height="32">  Pokémon with a bipedal, tailless form

### <img src="<img src="https://archives.bulbagarden.net/media/upload/d/da/Body09.png" alt="wings shape" width="32" height="32">  Pokémon with a single pair of wings

### <img src="<img src="https://archives.bulbagarden.net/media/upload/d/da/Body02.png" alt="serpentine shape" width="32" height="32">  Pokémon with serpentine bodies

### <img src="<img src="https://archives.bulbagarden.net/media/upload/d/da/Body04.png" alt="arms shape" width="32" height="32">  Pokémon consisting of a head and arms

