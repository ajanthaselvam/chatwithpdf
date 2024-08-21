# chatwithpdf

#create env

python3 -m venv .venv

#Activate

source .venv/bin/activate

#install streamlit
pip install streamlit

#test streamlit
streamlit hello

pip install pypdf2 langchain python-dotenv faiss-cpu openai huggingface_hub

pip install InstructorEmbedding sentence_transformers

#run the application
streamlit run app.py

.env

OPENAI_API_KEY=

HUGGINGFACEHUB_API_TOKEN=
