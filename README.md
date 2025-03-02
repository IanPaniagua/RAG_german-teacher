# German Language Assistant with ChromaDB and OpenAI

This is a simple assistant that helps answer questions about the German language, leveraging ChromaDB for data storage and OpenAI's GPT-4o-mini model for answering questions. It uses ChromaDB for document storage and retrieval, while OpenAI's model is utilized to provide relevant responses based on the provided data.

## Project Overview

The project is designed to:
- Store relevant information about the German language.
- Retrieve stored documents and metadata to respond to user queries.
- Answer questions based on the information stored in the database, while also correcting any grammatical errors in the user query.

### Features

- **ChromaDB**: A document storage and retrieval system that is used to store German language-related content.
- **OpenAI GPT-4o-mini**: Used to generate responses to user queries based on the stored documents.
- **Grammatical Correction**: The assistant corrects grammatical errors in the user query and teaches the right way to phrase things in German.

## Requirements

- Python 3.x
- OpenAI API access
- ChromaDB
- dotenv (for environment variable management)

## Installation

### 1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
