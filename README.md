[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/TnJIQ-Y6)
# Data Mining and Machine Learning Group Coursework

> [!TIP]
> You should update and customize this README as the project progresses.

> [!IMPORTANT]
> You should complete this README as soon as possible and then delete all messages like this one. This is your first task as a group. Your project should not contain any of these ["alerts"](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#alerts) by Week 4.


## Group Members
1. Hamza Hassan Mooraj - @hamzamooraj99 - H00390746
2. Max Ferstenberg - @Max-Ferstenberg - H00390365
3. Cameron Cassidy - @CobaltEclipse117 - H00369879
4. Chi-ioi Chan - @CICiceINA - H00376665
5. Ines Piot - @InesPiot - H00480289

## Initial Project Proposal
Pokemon type predictor

## Project Objective
Creating a probability-based classifier for Pokemon typings based on textual descriptions and tabular/visual attributes

### Source of Datasets
> [!IMPORTANT]
> Create a bullet list of the dataset(s) you used, their source with a link, and their licence. Also, include 2 specific examples from your dataset(s); present these nicely.

1. National pokedex data for every pokemon: https://docs.google.com/spreadsheets/d/19Me94k6YLz1_3EO_PwTPsAI9KmdFTh07/edit?gid=353590428#gid=353590428. No license required; fan made database on a reddit forum.
2. Textual description database for pokemon: https://huggingface.co/datasets/wanghaofan/pokemon-wiki-captions?row=1. Open source database repository.

### Milestones

> [!IMPORTANT]
> Create a bullet list of the key milestones for your project. Discuss these with your group. You may need to update these as the project progresses.

1. 


## Installing the project

> [!IMPORTANT]
> Provide instructions on how to install the project. This should include any dependencies that need to be installed.

```bash
```

## Data Preparation Pipeline

> [!IMPORTANT]
> Describe the data preparation pipeline. This should include how you will load the data, clean it, and preprocess it.

> [!TIP]
> Try to keep this as simple as possible, ideally with a single magic command that will run the entire pipeline consistently for everyone.


> [!WARNING]
> Do not blindly trust that the pipeline works. Verify that each invocation is identical by checking the output. For further checks, you can use methods such as calculating the MD5 checksum for files.


## Coursework Requirements

> [!IMPORTANT]
> Include a short description (100 words max.) of each Coursework Requirement (R2-R5) and their location within your repository.

### R2. Data Analysis and Exploration

### R3. Clustering

### R4.	Baseline Training and Evaluation Experiments

### R5. Neural Networks


## Documentation

Initial notes on data usage:
- Pokemon name, pokedex description, image, each inidivudal stat (HP, ATK, DEF, SATK, SDEF, SPD, Total Stats), All abilities, Height and Weight, Size, MAYBE pokedex colour and MAYBE egg groups.
- Output will be classifying pokemon typing based on probabilities, to account for dual typing.
- For clustering, we will be using k-Nearest clustering (for now)
- For machine learning algorithms, we will use decision trees, k-Nearest neighbours and Random Forest/CatBoost?
- CNN for image data

- We can take the best performing ML algorithm and CNN, combining them.

Weekly updates are kept in the `documentation/` directory.
