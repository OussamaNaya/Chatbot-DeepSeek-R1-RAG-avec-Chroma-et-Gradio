# Chatbot DeepSeek R1 avec RAG, Chroma et Gradio

Ce projet implémente un chatbot interactif appelé **DeepSeek R1** utilisant une architecture **Retrieval-Augmented Generation (RAG)** pour fournir des réponses pertinentes et contextuelles. Il combine **ChromaDB** pour la gestion de la base de données vectorielle et **Gradio** pour l'interface utilisateur interactive. Le modèle est conçu pour effectuer des tâches de question-réponse et est capable de générer des réponses basées sur des données récupérées depuis une base de connaissances.

## Fonctionnalités

- **RAG (Retrieval-Augmented Generation)** : Le chatbot utilise une approche hybride de génération et de récupération d'informations pour fournir des réponses de haute qualité et contextuelles.
- **ChromaDB** : Base de données vectorielle utilisée pour stocker et effectuer des recherches d'informations pertinentes par rapport aux questions posées.
- **Interface Gradio** : Une interface utilisateur interactive qui permet aux utilisateurs de poser des questions et d'interagir avec le chatbot via une interface web simple.
- **Réponses basées sur la recherche et la génération** : Le chatbot récupère des données pertinentes à partir de ChromaDB, puis génère des réponses adaptées à chaque question posée.

## Prérequis

- Python 3.x
- [Gradio](https://gradio.app/)
- [ChromaDB](https://www.trychroma.com/)
- Hugging Face Transformers
- PyTorch

## Installation

1. Clonez ce repository :
   ```bash
   git clone https://github.com/OussamaNaya/chatbot-deepseek-r1.git

  <img width="530" alt="Capture" src="https://github.com/user-attachments/assets/005da1c6-b1a3-4731-a85e-3013729d6a0a" />

