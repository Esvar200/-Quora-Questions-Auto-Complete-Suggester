# Quora Questions Auto-Complete Suggester

**Quora Questions Auto-Complete Suggester** is a tool designed to help users find the most similar questions from the Quora dataset based on a user-inputted question. By leveraging semantic search techniques, the tool provides relevant suggestions with a similarity score, making it easier to find related questions or content.

## Key Features

- **Semantic Search**: Retrieves the most similar questions from the Quora dataset using the `util.semantic_search` method.
- **SBERT Embeddings**: Utilizes the `quora-distilbert-multilingual` SBERT model to generate question embeddings and perform searches.
- **Symmetric Search Task**: The tool is designed to handle symmetric search, where the queries and corpus questions have similar lengths and content.

## Technologies Used

- **SBERT Transformer**: For generating semantic embeddings of questions.
- **Python**: The core programming language for the project.
- **Torch**: A machine learning library used for model inference.

## Dataset

The project uses the [Quora Questions Dataset](https://www.quora.com/q/quoradata/First-Quora-Dataset-Release-Question-Pairs) as the primary data source. The dataset consists of pairs of questions that have been manually labeled as either duplicates or not.

## How to Run the Project

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/Quora_Questions_Auto_Complete_Suggester.git
    cd Quora_Questions_Auto_Complete_Suggester
    ```

2. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Open the Jupyter Notebook**:
    - Launch Jupyter Notebook and open `Quora_Questions_Suggester.ipynb`.

4. **Run the Notebook**:
    - Execute the cells in the notebook to load the model, perform the search, and interact with the suggester.

5. **Input Your Question**:
    - When prompted within the notebook, type in your question, and the system will return the closest matching questions from the dataset along with their similarity scores.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any feature enhancements or bug fixes.

## License

This project is licensed under the MIT License.

---
