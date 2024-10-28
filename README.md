# Creativity in Music Generation with Large Language Models (LLMs)

# (A work in progress, subject to changes 🛠️)

## Project Overview

This project explores creativity in music generation models, focusing on evaluating generated outputs based on novelty, surprise, and value. By utilizing a dataset of MIDI files and applying Music Information Retrieval (MIR) techniques, the aim is to analyze structural characteristics of generated music and assess their creative attributes through a deep learning model.

## Goals

- Develop a creativity assessment model to evaluate LLM-generated music according to established frameworks.
- Utilize MIR for data-driven analysis of MIDI files to establish a structural basis for identifying creativity-related characteristics.
- Apply the creativity assessment model to measure and compare the creativity of human-composed and AI-generated music.

## Dataset

The dataset comprises MIDI files sourced from [Kaggle](https://www.kaggle.com/datasets/soumikrakshit/classical-music-midi). Here is a copy of this on [google drive](https://drive.google.com/file/d/1NR-RbH1NupYU6TkXJOnPbHFsMsbmqj3w/view?usp=sharing)

## Project Structure

- `src/`: Code for data analysis, preprocessing, and model training.
- `notebooks/`: Jupyter notebooks for exploratory data analysis (EDA) and MIR-based dataset insights.
- `datasets/`: Directory (not included in the repo) for storing MIDI datasets.

## Getting Started

### Prerequisites

- Python 3.12+
- All dependencies are listed in `requirements.txt`.

### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/briantwene/creativity-in-music-generation.git
