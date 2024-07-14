# DocumentationSummarization

## Introduction

This project consists of a frontend and backend. The backend uses an LLM model (Lamini Flan T5) which can be downloaded from Hugging Face 
https://huggingface.co/MBZUAI/LaMini-Flan-T5-248M.

## Prerequisites
- Node.js
- Python
- Conda

## Setup Instructions

### Backend
1. Navigate to the backend directory:
   ```sh
   cd backend
2.Create and activate a conda environment:

conda create --name your_env_name python=3.x
conda activate your_env_name

3.Install the dependencies:

pip install -r requirements.txt

4.Create a empty directory 'data' for storing the input documents:
mkdir data

4.Run the backend:

python app.py


### Frontend
1.Navigate to the frontend directory:
cd frontend

2.Install the dependencies:
npm install

3.Run the frontend:
npm run