# DocumentationSummarization

## Project Overview
This project involves developing a web-based application for automatic summarization of financial documents using two advanced Natural Language Processing (NLP) models: Lamini Flan T5 and BERT. The application is designed to assist users in quickly extracting key information from lengthy financial documents, improving efficiency and comprehension. 
The backend uses an LLM model (Lamini Flan T5) which can be downloaded from Hugging Face 
https://huggingface.co/MBZUAI/LaMini-Flan-T5-248M.

## Technologies Used
- Frontend: React.js
- Backend: Flask
- LLM Models: Lamini Flan T5, BERT
- Other Tools: Axios for API requests, Tailwind CSS for styling, PDF.js for PDF rendering, and Matplotlib for visualization.

## Key Features
1. Document Upload: Users can upload financial documents in PDF format.
2. Model Selection: Users can choose between Lamini Flan T5 and BERT for summarization.
3. Summarization: The selected model processes the document and provides a concise summary.
4. Comparison: The application offers a feature to compare summaries generated by both models side by side.
5. Visualization: Performance of the models is compared using ROUGE scores visualized through graphs.

## Output
FrontEnd:
![frontend](https://github.com/user-attachments/assets/372bd6d0-dee1-4d15-839b-569811a9a97a)
Summary using BERT:
![output ss1](https://github.com/user-attachments/assets/d981a298-a9d3-4a13-99ad-3780f689f429)
Summary using Lamini-Flan-T5:
![output ss3](https://github.com/user-attachments/assets/4f2e4fdf-ad0a-4d9f-ab84-45876170ba77)



## Setup Instructions

### Backend
1. Navigate to the backend directory:
   ```sh
   cd backend
2.Create and activate a conda environment:

   ```sh
   conda create --name your_env_name python=3.x
   conda activate your_env_name
```
3.Install the dependencies:
   ```sh
   pip install -r requirements.txt
```
4.Create a empty directory 'data' for storing the input documents:
   ```sh
   mkdir data
```
4.Run the backend:
   ```sh
   python app.py

```
### Frontend
1.Navigate to the frontend directory:
   ```sh
   cd frontend
```
2.Install the dependencies:
   ```sh
   npm install
```
3.Run the frontend:
   ```sh
   npm run
