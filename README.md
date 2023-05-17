# Chat with your PDF 

## Architecture

Link: 

Tutorial going over the design used for the app in order to enable chatting with your PDF using LangChain, ChromaDB and OpenAI's API.

## Getting Started

### Prerequisites

You will need Python and Pipenv

### Installation

1. Clone the repository:

```bash
git clone https://github.com//chat-pdf.git
```

2. Navigate to the project directory:

```bash
cd chat-pdf
```

3. Install the required dependencies using Pipenv:

```bash
pipenv install
```

4. Activate the Pipenv shell:

```bash
pipenv shell
```

5. Run the ingestion:

```bash
python src/ingest.py
```

6. Run the conversation:

```bash
python src/single-pdf.py
```




