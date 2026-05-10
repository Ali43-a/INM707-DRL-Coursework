# INM707 DRL Coursework

This repository contains my coursework submission for INM707 Deep Reinforcement Learning.

The work was completed individually by Ali Abdulzahra. The repository includes the Jupyter notebooks, exported notebook versions, saved result files, the written report, and the coursework brief.

## Repository structure

```text
INM707-DRL-Coursework/
│
├── CourseWork Guide.pdf
│
├── Notebooks/
│   ├── 01_basic_q_learning_gridworld.ipynb
│   ├── 02_dqn_cartpole.ipynb
│   ├── 03_ppo_cartpole.ipynb
│   │
│   └── pdfnhtml/
│       ├── NB1/
│       │   ├── 01_basic_q_learning_gridworld.html
│       │   └── 01_basic_q_learning_gridworld.pdf
│       │
│       ├── NB2/
│       │   ├── 02_dqn_cartpole.html
│       │   └── 02_dqn_cartpole.pdf
│       │
│       └── NB3/
│           ├── 03_ppo_cartpole.html
│           └── 03_ppo_cartpole.pdf
│
├── Report/
│   ├── INM707 Deep Reinforcement Learning Coursework Report.docx
│   └── INM707 Deep Reinforcement Learning Coursework Report.pdf
│
└── Results/
    ├── basic/
    ├── dqn/
    └── ppo/

Contents
CourseWork Guide

The file CourseWork Guide.pdf contains the original coursework brief for the assignment.

Notebooks

The Notebooks folder contains the three main Jupyter notebooks used for the coursework.

Notebook 1

01_basic_q_learning_gridworld.ipynb

This notebook implements tabular Q learning in a custom Gridworld environment. It includes the environment definition, state representation, reward function, Q learning training loop, greedy evaluation, parameter sweeps, and reward design comparison.

Notebook 2

02_dqn_cartpole.ipynb

This notebook implements DQN on CartPole v1. It compares the baseline DQN against Double DQN, Dueling DQN, and Double Dueling DQN.

Notebook 3

03_ppo_cartpole.ipynb

This notebook implements Proximal Policy Optimisation on CartPole v1 using an actor critic approach. It includes training results, greedy evaluation, entropy tracking, and clip fraction tracking.

Exported notebooks

The folder Notebooks/pdfnhtml contains PDF and HTML exports of each notebook.

These exports are included for transparency, so the notebook outputs can be viewed without rerunning the code.

The folders are organised as follows:
NB1 = exports for 01_basic_q_learning_gridworld
NB2 = exports for 02_dqn_cartpole
NB3 = exports for 03_ppo_cartpole
Each folder contains one HTML file and one PDF file of the matching notebook.

Report

The Report folder contains the written coursework report in both Word and PDF format.

The PDF version is the final submitted report. The Word version is included as an editable version of the same report.

Results

The Results folder contains the result files generated from the notebooks.

The results are organised by notebook:
Results/basic = results from Notebook 1
Results/dqn   = results from Notebook 2
Results/ppo   = results from Notebook 3

The notebooks were written in Python and use common scientific computing and reinforcement learning libraries.

The main packages used are:
numpy
pandas
matplotlib
torch
gymnasium

Results structure

Each notebook saves its outputs into the matching results folder.

Basic Q learning results

The Results/basic folder contains the outputs from the Gridworld Q learning notebook. These include the baseline training history, greedy rollout, Q table, parameter sweep summaries, and plots used in the report.

DQN results

The Results/dqn folder contains the outputs from the DQN CartPole notebook. These include training histories, variant summaries, evaluation plots, and saved network weights for the DQN variants.

The DQN variants are:
baseline DQN
Double DQN
Dueling DQN
Double Dueling DQN

PPO results

The Results/ppo folder contains the outputs from the PPO CartPole notebook. These include training history, summary results, policy evaluation plots, entropy and clip fraction plots, and saved actor critic weights.

Reproducibility note

The repository keeps the outputs in the structure produced by the coursework code. This was done to keep the submission transparent and reproducible. The notebooks, exported notebook files, result files, figures, and report are all included so the work can be inspected either by rerunning the notebooks or by viewing the saved outputs directly.


Author

Ali Abdulzahra

