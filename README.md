# LLM Based Tools and Gemini API Integration for Data Scientists

This repository provides a collection of LLM-based tools integrated with the Google Gemini API, tailored for data scientists. It serves as a starting point for exploring, building, and deploying intelligent data science workflows powered by large language models.

<hr><br>

## Purpose of This Repository

The purpose of this repository is to provide data scientists with a practical starting point for leveraging Large Language Models (LLMs) through the Google Gemini API. By offering ready-to-use tools and examples, this project aims to simplify experimentation, customization, and deployment of intelligent workflows that enhance data analysis and decision-making.

<hr><br>

## Demonstration

Here is a quick demo of what you can achieve with this repository:

```python
# gemini_demo.py

from google import genai

# Initialize Gemini client
client = genai.Client(api_key="YOUR_API_KEY")

# Example prompt for data scientists
prompt = """
You are a helpful assistant for data scientists.
Explain the difference between supervised and unsupervised learning in simple terms.
"""

# Send request to Gemini
response = client.models.generate_content(
    model="gemini-pro",
    contents=prompt
)

# Print the output
print("Gemini Response:\n")
print(response.text)
```

When you run:

```
python gemini_demo.py
```

<hr><br>

## Features

- Integration with Google Gemini API for natural language processing
- Ready-to-use LLM-based tools tailored for data scientists
- Examples for applying LLMs in data analysis, explanation, and workflow automation
- Modular code structure for easy customization and extension
- Support for experimenting with prompts and generating intelligent insights
- Demonstrations of practical use cases in data science projects

<hr><br>

## Technologies Used

- Python 3.x – core programming language
- Google Colab – as the primary development and execution environment
- Google Gemini API – for large language model integration
- Google Generative AI Python SDK (google-genai) – to interact with Gemini models
- Pandas / NumPy – for data manipulation and analysis
- Matplotlib / Seaborn – for data visualization

<hr><br>

## Project Setup

To prepare this project for use in Google Colab, follow these steps:

1. **Clone the repository**
   ```bash
   git clone https://github.com/sha-env/LLM-Based-Tools-and-Gemini-API-Integration-for-Data-Scientists.git
   ```
2. **Upload the cloned directory to Google Drive**
   
   This allows easy access and management from Colab.

3. **Locate to the folder**
   
   Locate the notebook file (.ipynb) inside the uploaded folder.
   
<hr><br>

## Steps to Run

Once the project is set up, follow these steps in Google Colab:

1. **Open the .ipynb notebook**

   Right click the file in Google Drive → Open with → Google Colaboratory

2. **Execute the notebook cells sequentially**

   This will install dependencies, configure the environment, and launch the tools.

3. **Start experimenting**

   - Interact with LLM-based tools directly inside the notebook
   - Test Gemini API integration for data science workflows
   - Extend or customize the code as needed

<hr><br>

## License

This project is licensed under the Apache-2.0 License. See the [LICENSE](LICENSE) file for details.

<hr><br>

<div align="center">
  <a href="https://www.instagram.com/sha.env/">
    <img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=100:00000,20:FFFFFF&section=footer&reversal=false&textBg=false&fontAlignY=50&descAlign=48&descAlignY=59"/>
  </a>
</div>
