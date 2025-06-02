# Retrieval Augmented Generation (RAG) for Cybersecurity, Pentesting, and Hacking

This project demonstrates a modular RAG pipeline that integrates with a Language Model (LLM) and supports previous conversations. The goal is to improve LLM responses for cybersecurity topics by augmenting them with relevant retrieved information.

## Features
- **Preprocessing**: Clean and prepare data/documents for retrieval.
- **Retrieval**: Find relevant documents or passages based on a query using FAISS and Sentence Transformers.
- **Previous Conversation Handling**: Integrate chat history into the retrieval and generation process.
- **Inference**: Use an LLM to generate responses augmented with retrieved information.

## Supported Dependencies and Versions
The following dependencies are required to run the project:

| Dependency              | Version         |
|-------------------------|-----------------|
| `pandas`               | `>=1.3.0`       |
| `scikit-learn`         | `>=0.24.0`      |
| `sentence-transformers`| `>=2.2.2`       |
| `transformers`         | `>=4.30.0`      |
| `faiss-cpu`            | `>=1.7.0`       |

## Installation Steps
Follow these steps to set up the environment and run the project:

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. **Install Dependencies**
   Install the required Python packages using `pip`:
   ```bash
   pip install pandas scikit-learn sentence-transformers transformers faiss-cpu
   ````

3. **Run the Notebook**
   Open the Jupyter Notebook `rag_cybersecurity.ipynb` and execute the cells step-by-step.
   ```bash
   jupyter notebook rag_cybersecurity.ipynb
   ```

## Usage
- Modify the datasets or preprocessing steps as needed.
- Extend the pipeline with additional retrieval or inference techniques.
- Deploy the pipeline as an API or integrate it into a chat interface.

## References
- [Sentence Transformers Documentation](https://www.sbert.net/)
- [FAISS Documentation](https://faiss.ai/)
- [HuggingFace Transformers](https://huggingface.co/docs/transformers/index)
- [RAG Paper (Facebook AI)](https://arxiv.org/abs/2005.11401)

## License
This project is licensed under the MIT License. See the LICENSE file for details.
