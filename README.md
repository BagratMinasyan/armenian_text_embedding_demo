# Armenian Text Embedding Model Demonstration

## Overview

This project demonstrates the capabilities of our developed **Armenian text embedding model** (`Metric-AI/armenian-text-embeddings-1`). The model is designed to generate meaningful embeddings for Armenian text, and this repository provides several examples showcasing how it can be used for various tasks such as text classification, keyword extraction, topic modeling, and product search.

### Project Use Cases

1. **Text Classification**: 
   - A sample notebook demonstrates how to use our model for text classification using a 7-class dataset. It shows how to fit a classifier and test the model.
   
2. **Keyword Extraction**:
   - The repository includes examples of using the **KeyBERT** and **Bertopic** packages with our model as the backbone. You can use these packages for keyword extraction and topic modeling, where our model provides the embeddings for text.
   
3. **Product Search & Recommendation**:
   - A product search example demonstrates how to embed a large dataset of product descriptions and compare them with user queries. The task is to find the most similar product, enabling recommendation systems or search functionality.

4. **Interactive Gradio Interface**:
   - The project also integrates with **Gradio** to provide an easy-to-use interface for testing and interacting with the model. This allows users to quickly test text classification, keyword extraction, and product search functionalities.
