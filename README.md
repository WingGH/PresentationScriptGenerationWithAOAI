# PDF to Speech Script Generator

This project converts PDF presentation slides into speech scripts using Azure OpenAI. It includes generating slide descriptions and summarizing them into a cohesive presentation script.

## Installation

To install the necessary libraries, run the following commands:

```bash
pip install openai
pip install PyMuPDF
```

## Features

Convert PDF pages to images: Extracts each page of a PDF and saves it as an image.  
Generate slide descriptions: Uses Azure OpenAI to describe each slide image.  
Summarize and smooth script: Creates a smooth and cohesive presentation script with transitions.  

## Usage

Set up Azure OpenAI: Replace YOUR_API_KEY and YOUR_ENDPOINT_URL in the code with your Azure OpenAI API key and endpoint.  
Run the script: The main() functions handle the conversion and summarization process.  
Output: The final summarized presentation script is saved in summarized_presentation.txt.  

## Code Structure
pdf_to_images: Converts PDF pages to PNG images.  
get_image_description: Calls Azure OpenAI to get descriptions for images.  
read_speech_script: Reads the speech script from a file.  
summarize_script: Summarizes and smooths the script using Azure OpenAI.  
write_summarized_script: Writes the summarized script to a file.  

## Notes
Ensure your PDF file is named aoaidemo.pdf or adjust the pdf_path in the code.  
Customize the presentation script format and content as needed.  
