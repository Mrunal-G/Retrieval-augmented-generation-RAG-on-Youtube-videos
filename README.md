# Retrieval-augmented-generation-RAG-on-Youtube-videos

This is a Streamlit application that helps you chat with your youtube audio file powered by Langchain, ChromaDB, and OpenAI.

normally -> streamlit run app.py

Build docker image and run the image in container
- docker build -t chatbotaudio . 
- docker run -p 8501:8501  chatbotaudio

check by testing:

curl http://localhost:8501/

Open the following link after running the above command:

http://localhost:8501/

![streamlit chatbotaudio][https://github.com/Mrunal-G/Retrieval-augmented-generation-RAG-on-Youtube-videos/blob/main/demo_img/img.png]
