## Document Upload and Data Analysis Tool

Welcome to the Document Upload and Data Analysis Tool repository. This application allows users to upload documents, manage datasets, and perform similarity analysis using machine learning. The intuitive interface lets you easily compare new documents with existing ones in your database and get clear similarity scores to identify related or duplicate files.

## Repository Overview

This GitHub repository contains the source code for the Document Upload and Data Analysis Tool, developed using Python and Streamlit. The application is designed to make document management and analysis easier by leveraging a simple, user-friendly interface and powerful machine learning capabilities.

## GitHub URL

You can access the repository here: Connected-Data-Solutions/python_streamlit_ml

## Getting Started

Follow these instructions to set up and run the application on your local machine.

## Prerequisites

The application requires Python to be installed on your local system. Additionally, the following libraries are required:

Streamlit: The web framework used to build the application interface.

Pandas: For handling dataframes and extracting data from uploaded files.

NumPy: For numerical computations.

Scikit-Learn: For machine learning operations like calculating document similarity.

## Installation

Clone the repository:

Navigate to the project directory:

Install the required libraries:
You can install the necessary Python libraries by running:

Alternatively, you can manually install the required packages:

## Running the Application

To run the application, use the following command:

`streamlit run app.py`

This command will launch the application in your default web browser, allowing you to begin uploading and analyzing documents.

## Features

The tool has two main sections:

- Upload Document:

Users can upload various document types, such as CSV, Excel, Word, PDF, and XML.

Uploaded documents are stored in a database for future analysis.

- Data Analysis Result:

Users can upload a new document for comparison against existing documents.

The system analyzes the documents and provides a similarity score ranging from 0.0 to 1.0, where 1.0 indicates an exact match.

Results are highlighted with larger fonts and color for better visibility.

A download button is provided to allow users to download the most similar existing document.

## How It Works

Upload Documents: Users can drag and drop files or browse to select them for upload. The files are extracted, and their content is saved to the database.

Document Analysis: Once a document is uploaded for analysis, it is compared with all existing documents using machine learning techniques. A similarity score is generated to help users understand the level of similarity.

## Best Practices

Organize Your Documents: Upload documents that add value to the database.

Use Clear File Names: To help identify documents during analysis.

Monitor Similarity Scores: Scores can help you understand the relevance of different documents.

## Contributing

Contributions are welcome! Please create a pull request if you have a feature to add or spot a bug that needs fixing.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Support

If you encounter any issues or have questions about using the application, please refer to the documentation or create an issue in the GitHub repository.

## Contact

For further inquiries, please reach out to us through the GitHub repository.
