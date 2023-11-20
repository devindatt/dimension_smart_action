# dimension_smart_action
Dimension Collaboration Log Application

## Overview

The Dimension Collaboration Log Application is a Streamlit-based web application designed to enhance team collaboration by logging user inputs, categorizing them, and recommending relevant tools or actions. This application leverages the power of GPT-3.5 for natural language processing and decision-making, providing smart recommendations based on user logs.

## Features

Log Submission: Users can submit logs about their development issues or observations.
Automatic Categorization: The app categorizes each log into a specific development issue category using a custom-built AI model.
Tool Recommendation: Based on the category, it recommends the most suitable tools or actions.


## Files Description

- dim_smart_feature.py: Main application file with Streamlit UI components and application logic.
- genai_recommendations.py: Contains functions to get recommendations for categories and tools using the LangChain and OpenAI's GPT-3.5 model.
- external_items.py: Includes predefined lists of log items, possible outputs, categories, and tools.


## Prerequisites

- Python 3.x
- Streamlit
- OpenAI API Key


## Installation

Clone the repository:
bash
git clone [repository URL]

Install required packages:
pip install -r requirements.txt


## Usage

Set your OpenAI API key as an environment variable:

export OPENAI_API_KEY='your_api_key_here'

Run the Streamlit app:
streamlit run dim_smart_feature.py

## Contributing

Contributions to improve the application are welcome. Please follow the standard fork-and-pull request workflow.

## License

Apache License - free to use


Contact

For any queries or suggestions, please contact [Your Name or Contact Information].
