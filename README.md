# W266_Final_Project

## Instructions for GRUEN Replication
1. Clone Repo
2. Note that Main.py is GRUEN primary script full of all functions, etc. To get it to run refer to GRUEN repo: https://github.com/WanzhengZhu/GRUEN/blob/master/requirements.txt
3. Need to download the file contents of https://drive.google.com/file/d/1Hw5na_Iy4-kGEoX60bD8vXYeJDQrzyj6/view?usp=sharing into path relative to notebook ./cola_model/bert-base-cased

## Data
OpenAI GPT-2 Output Dataset: https://github.com/openai/gpt-2-output-dataset 
For my purposes, yields 5k records each of real web documents from test set.
Yields 5k records each from the outputs of 8 baseline GPT-2 models (small, medium, large, xl)X(temp1 & no trucncation,top-k 40 truncation).

Baseline evaluated data in Data folder.
