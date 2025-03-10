# Automatic Blog Generation
For live site visit [Automatic Blogging]([https://github.com/Rikriti/Automatic-Blogging](https://automatic-blogging.onrender.com/))

This project leverages **Hugging Face Transformers** and **Streamlit** to automatically generate detailed blog posts based on a given topic using a pre-trained GPT-2 model. The user can input a topic, and the app generates a well-structured blog entry about it.

## Features

- **Text Generation**: Automatically generates blog content using a pre-trained GPT-2 model.
- **Streamlit Interface**: Simple and interactive UI to enter topics and generate blogs.
- **Customizable Output**: Allows customization of the maximum length of generated content.

## Technologies Used

- **Streamlit**: Used to create the interactive web interface for the application.
- **Hugging Face Transformers**: Used for text generation with GPT-2.
- **Python**: The core language for implementing the app.

## Installation

To run this project on your local machine, follow these steps:

### Prerequisites

- Python 3.6 or higher
- Virtual environment (recommended)

### Steps to Run

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/automatic-blog-generation.git
    cd automatic-blog-generation
    ```

2. Create a virtual environment:

    ```bash
    python -m venv venv
    ```

3. Activate the virtual environment:

    - On Windows:

      ```bash
      venv\Scripts\activate
      ```

    - On macOS/Linux:

      ```bash
      source venv/bin/activate
      ```

4. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

    `requirements.txt` should include the necessary dependencies like `streamlit` and `transformers`. You can generate it using:

    ```bash
    pip freeze > requirements.txt
    ```

    Alternatively, you can install the required libraries directly:

    ```bash
    pip install streamlit transformers
    ```

5. Run the Streamlit app:

    ```bash
    streamlit run app.py
    ```

    This will start a local server and you can access the app via `http://localhost:8501` in your browser.

## How to Use

1. Open the app in your browser.
2. Enter a topic for your blog post in the input box (e.g., "How to Learn Machine Learning").
3. Click on the "Generate Blog" button.
4. The app will generate and display a detailed blog post on the given topic.
