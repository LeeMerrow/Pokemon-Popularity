# Pokemon Popularity
<img src="https://upload.wikimedia.org/wikipedia/commons/9/98/International_Pok%C3%A9mon_logo.svg" alt="pokemon banner" width="500" height="300">

## About
What makes a Pokemon popular? Let's dig in and see what we can find out. We will be looking at the video game series developed by Game Freak and published by Nintendo. This is my Capstone Project for Code:Louisville

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

Bulbapedia was also a huge help as a resource to make sure data was complete and in writing some of the explanations for terminology.
https://bulbapedia.bulbagarden.net/wiki/Main_Page

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

### Generation
Pokemon games are usually refered to their generation or gen. This is just a simpler way to break down the games. The first set ofgames, Pokemon Red and Pokemon Blue, are gen 1. The second set of games, Pokemon Gold and Pokemon Silver, are gen 2 and so on. We will only be looking at the first 7 gens.

### Shapes
Each pokemon is assigned a 'shape'. This gives you a rought idea about how the pokemon looks in terms of features such as wings or silhouette. There are currently 14 shapes that a pokemon can be split into. They are as follows:

<img src="https://archives.bulbagarden.net/media/upload/1/17/Body01.png" alt="head shape" width="32" height="32">  Pokémon consisting of only a head

<img src="https://archives.bulbagarden.net/media/upload/2/25/0132Ditto.png" alt="ditto" width="120" height="120"> 

<img src="https://archives.bulbagarden.net/media/upload/b/bc/Body07.png" alt="legs shape" width="32" height="32">  Pokémon consisting of a head and legs

<img src="https://archives.bulbagarden.net/media/upload/thumb/1/16/0043Oddish.png/240px-0043Oddish.png" alt="oddish" width="120" height="120"> 

<img src="https://archives.bulbagarden.net/media/upload/d/d3/Body03.png" alt="fins shape" width="32" height="32">  Pokémon with fins

<img src="https://archives.bulbagarden.net/media/upload/9/99/0131Lapras.png" alt="lapras" width="120" height="120"> 

<img src="https://archives.bulbagarden.net/media/upload/4/4b/Body14.png" alt="insectoid shape" width="32" height="32">  Pokémon with an insectoid body

<img src="https://archives.bulbagarden.net/media/upload/5/59/0213Shuckle.png" alt="shuckle" width="120" height="120"> 

<img src="https://archives.bulbagarden.net/media/upload/c/cc/Body08.png" alt="quadruped shape" width="32" height="32">  Pokémon with a quadruped body

<img src="https://archives.bulbagarden.net/media/upload/thumb/4/42/0059Arcanine.png/240px-0059Arcanine.png" alt="arcanine" width="120" height="120"> 

<img src="https://archives.bulbagarden.net/media/upload/0/09/Body13.png" alt="multi_wing shape" width="32" height="32">  Pokémon with two or more pairs of wings

<img src="https://archives.bulbagarden.net/media/upload/3/39/0212Scizor.png" alt="scizor" width="120" height="120"> 

<img src="https://archives.bulbagarden.net/media/upload/3/36/Body11.png" alt="multi_bodies shape" width="32" height="32">  Pokémon consisting of multiple bodies

<img src="https://archives.bulbagarden.net/media/upload/f/fe/0376Metagross.png" alt="metagross" width="120" height="120"> 

<img src="https://archives.bulbagarden.net/media/upload/9/97/Body10.png" alt="tentacles shape" width="32" height="32">  Pokémon with tentacles or a multiped body

<img src="https://archives.bulbagarden.net/media/upload/thumb/8/81/0487Giratina.png/240px-0487Giratina.png" alt="giratina" width="120" height="120"> 

<img src="https://archives.bulbagarden.net/media/upload/d/da/Body05.png" alt="head_base shape" width="32" height="32">  Pokémon consisting of a head and a base

<img src="https://archives.bulbagarden.net/media/upload/5/5a/0681Aegislash-Shield.png" alt="Aegislash" width="120" height="120"> 

<img src="https://archives.bulbagarden.net/media/upload/8/88/Body06.png" alt="bipedal_tail shape" width="32" height="32">  Pokémon with a bipedal, tailed form

<img src="https://archives.bulbagarden.net/media/upload/thumb/3/38/0006Charizard.png/240px-0006Charizard.png" alt="charizard" width="120" height="120"> 

<img src="https://archives.bulbagarden.net/media/upload/4/45/Body12.png" alt="bipedal_tailless shape" width="32" height="32">  Pokémon with a bipedal, tailless form

<img src="https://archives.bulbagarden.net/media/upload/f/f8/0282Gardevoir.png" alt="gardevoir" width="120" height="120"> 

<img src="https://archives.bulbagarden.net/media/upload/9/98/Body09.png" alt="wings shape" width="32" height="32">  Pokémon with a single pair of wings

<img src="https://archives.bulbagarden.net/media/upload/4/4a/0330Flygon.png" alt="flygon" width="120" height="120"> 

<img src="https://archives.bulbagarden.net/media/upload/9/98/Body09.png" alt="serpentine shape" width="32" height="32">  Pokémon with serpentine bodies

<img src="https://archives.bulbagarden.net/media/upload/8/80/0384Rayquaza.png" alt="rayquaza" width="120" height="120"> 

<img src="https://archives.bulbagarden.net/media/upload/2/2c/Body04.png" alt="arms shape" width="32" height="32">Pokémon consisting of a head and arms

<img src="https://archives.bulbagarden.net/media/upload/thumb/d/d1/0093Haunter.png/240px-0093Haunter.png" alt="haunter" width="120" height="120">

### Legendary/Mythical
Legendary pokemon are pokemon that you can normally only catch once per game/save file. These are usually rare pokemon. There can be multiple different legendary pokemon in a generation, with there normally being between 3-9 different legendaries per gen, but sometimes more.
Mythical pokemon are even rarer. They are typically only handed out during events. Most you cannot catch thru normal gameplay and either need a code to unlock or some other means depending on when the game came out. There are normally fewer Mythical than legendary pokemon per gen, between 1-5.

### Stats
- Pokemon have many stats that determine how good they are at combat. Here is a simple breakdown of what each stat does:

##### HP
- HP determines how much damage a pokemon can receive before fainting

##### Attack
- Attack helps determine how much damage physical moves do

##### Defense
- Defense helps determine how much damage from physical moves is mitigated

##### Special Attack
- Attack helps determine how much damage special moves do

##### Special Defense
- Defense helps determine how much damage from special moves is mitigated

##### Speed
- Speed determines the order of pokemon that can act in battle. Since pokemon is turn-based game, usally the pokemon with the highest speed gets to attack first.