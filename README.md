# Medical Query Generator

A Flask web application that uses Google's GenerativeAI (Gemini) to generate medical responses based on user input. The application simulates a medical expert providing accurate advice to a patient's query.

## About The Project

The Medical Query Generator is a web application that leverages Google's GenerativeAI to generate detailed and accurate medical responses. Users input medical queries, and the application provides responses adhering to specific guidelines for clarity, accuracy, and informativeness.

## Getting Started

To get started with the project, follow the steps below.

### Prerequisites

- Google API Key
- Google Generativeai
- Flask
- Python Dotenv

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/tarunvinodhkumar/Medical-Assistant-using-GenAI-Gemini-.git
   cd medical-query-generator
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Set up your Google API Key:

   - Create a project on the [Google Cloud Console](https://console.cloud.google.com/).
   - Enable the GenerativeAI API.
   - Create an API key and add it to your environment variables or a `.env` file.

4. Run the application:

   ```bash
   python app.py
   ```

   The application will be accessible at : [http://localhost:5000/](http://localhost:5000/).

## Usage

1. Open your web browser and navigate to [http://localhost:5000/](http://localhost:5000/).
2. Input a medical query following the provided guidelines.
3. Click the "Generate Response" button to obtain a detailed medical response.

