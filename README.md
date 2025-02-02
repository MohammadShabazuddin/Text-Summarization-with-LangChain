### Text Summarization with Split
This project is a web app built with Streamlit and LangChain for summarizing long text files. Users upload a text file, input their OpenAI API Key, and the app splits the content into smaller chunks to prevent token limits. The app then uses LangChain to summarize the text using OpenAI's language models. It employs a map-reduce chain approach, summarizing each chunk and combining the results into a concise summary. The app ensures that files exceeding 20,000 words are flagged, offering a simple interface for users to summarize lengthy documents efficiently.

### How to run? Use python = 3.11
conda create -n llmapp python=3.11 -y

conda activate llmapp

pip install -r requirements.txt

streamlit run main.py

Live Website: https://text-summarization-with-split.streamlit.app/


