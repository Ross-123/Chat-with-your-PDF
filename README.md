# Chat-with-your-PDF
This app lets you upload any pdf document and chat with it. You can ask questions in natural language and dets answers bsed on the uploaded pdf document.

  App is build using :
      shutil
tempfile
istreamlit as st  
dotenv import load_dotenv  
langchain.schema import HumanMessage, AIMessage, SystemMessage  
langchain_ollama import ChatOllama, OllamaEmbeddings  
langchain_openai import ChatOpenAI  
langchain.text_splitter import RecursiveCharacterTextSplitter  
langchain_community.document_loaders import PyPDFLoader  
langchain_community.vectorstores import Chroma  
langchain.memory import ConversationBufferMemory  
langchain.chains  
