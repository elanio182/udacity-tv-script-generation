# Udacity Deep Laerning Foundations Nanodegree

## Project 3: TV Script Generation

In this project, you'll generate your own Simpsons TV scripts using RNNs. You'll be using part of the Simpsons dataset of scripts from 27 seasons. The Neural Network you'll build will generate a new TV script for a scene at Moe's Tavern.

## Running using conda!

Run this in command line

**Step 1:** Create a new environment

```terminal
conda create --name tv-script-generation python=3
```

**Step 2:** Use the new env

```terminal
source activate tv-script-generation
```

**Step 3:** Install dependencies

```terminal
conda install -c conda-forge tensorflow=1.0.0
conda install numpy jupyter notebook
```

**Step 4:** Open the notebook to run it

```terminal
jupyter notebook dlnd_tv_script_generation.ipynb
```

## Project structure

This folder contains files for Udacity Deep Laerning Foundations Nanodegree Project 3: TV Script Generation.

**dlnd_image_classification.ipynb** - Main project file.

**dlnd_image_classification.html** - Neural network script results file.

**problem_unittests.py** - Unit tests provided by Udacity.

**helper.py** - Help functions provided by Udacity.

**data/simpsons/moes_tavern_lines.txt** - Some lines from a chapter of "The Simpsons" that will be used as input for the generation of a new scipt..
