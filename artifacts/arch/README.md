# Design Description: Email Classification and Reporting System

## Overview

This system is designed to classify emails and their attachments into predefined categories and subcategories using a Deep Seek AI model, with results presented in a user-friendly table via a Streamlit front-end interface. The system supports manual file uploads or directory-based email inventory processing, leveraging an object-oriented Python architecture for modularity and scalability.

## System Architecture

The system comprises the following key components:

1. **Streamlit Front-End**: User interface for input selection and result visualization.
2. **File Handler**: Manages file uploads and folder path processing.
3. **Email Processor**: Handles email extraction and preparation.
4. **Prompt Generator**: Constructs prompts for the AI model.
5. **Deep Seek Model**: Performs classification and metadata extraction.
6. **Report Generator**: Formats classification results into JSON.
7. **Result Renderer**: Displays results as a table in Streamlit.

<img width="1526" alt="image" src="https://github.com/user-attachments/assets/c3838af7-051a-4300-8233-eb4a66af3f22" />


## Actors

- **User**: An individual interacting with the Streamlit front-end to upload emails or specify an email inventory path and view the classification results.
