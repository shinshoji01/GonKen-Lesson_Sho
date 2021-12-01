# Lessons for AI Laboratory
This repository contains the lessons that I gave for the laboratory I belonged to. The original repository is [this](https://github.com/shinshoji01/gonken-lesson) and this repository includes only the lessons I built. It can be divided into mostly 4 parts: M1_spring, M1_autumn, M2_spring, and M2_autumn, where the number and the latter word indicate an academic year of master's degree (when I created the lessons) and the semester, respectively.  

# Lessons

## M1_spring
- 02_Learning_Algorithm
  - It describes the basic algorithm used in machine learning.
- 04_Overfitting_Underfitting
- 05_Practice-Overfitting_Underfitting
  - It contains an exercise of the lesson regaring overfitting and underfitting.
- 10_Convolutional_Neural_Networks

## M1_autumn
- PyTorch_implementation

## M2_spring
- PyTorch_implementation

## M2_autumn
- Auto-Encoder

# Docker Environment
This repository contains docker environment to allow anyone to try my model. To make the execution simple, I created my environment with docker-compose. Please follow the procedure below to build my environment.

1. Go to `Docker/`
2. `docker-compose up -d`
3. `docker-compose exec gonken-lesson nohup jupyter lab --ip=0.0.0.0 --no-browser --allow-root --NotebookApp.token='' --port 8080`
4. Go to http://localhost:8080/lab
