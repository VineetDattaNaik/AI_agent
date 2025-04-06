# Web Task Assistant

A powerful Python-based web task assistant that uses Google's Gemini AI to interpret tasks, extract information from websites, and generate detailed PDF reports with visual elements.

## Features

- 🤖 Uses Gemini AI for intelligent task interpretation
- 🌐 Automated web scraping with retry logic
- 📊 Dynamic chart generation (Bar, Pie, Line charts)
- 🖼️ Automatic image extraction and processing
- 📑 PDF report generation with visual elements
- ↪️ Fallback mechanisms for failed requests
- 🎯 Structured information extraction

## Prerequisites

- Python 3.7+
- Google API key for Gemini AI

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd web-task-assistant
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Set up your Google API key:
   - Get your API key from [Google AI Studio](https://makersuite.google.com/app/apikey)
   - Replace the `GOOGLE_API_KEY` in `web_task_assistant.py` with your key

## Usage

1. Run the script:
```bash
python web_task_assistant.py
```

2. Enter your task when prompted. For example:
   - "Find the top 5 AI related headlines"
   - "Get the latest cryptocurrency prices"
   - "Summarize recent space exploration news"

3. The script will:
   - Interpret your task
   - Visit relevant websites
   - Extract information
   - Generate a PDF report with:
     - Text information
     - Related images
     - Data visualizations
     - Charts (where applicable)

## Project Structure

```
web-task-assistant/
├── web_task_assistant.py   # Main script
├── requirements.txt        # Package dependencies
└── README.md              # Documentation
```

## Key Functions

- `interpret_task()`: Uses Gemini AI to understand the task and determine target websites
- `fetch_webpage()`: Retrieves webpage content with retry logic
- `extract_information()`: Extracts relevant information using Gemini AI
- `create_chart()`: Generates various types of charts
- `download_image()`: Processes and downloads images
- `save_results_to_file()`: Generates PDF reports with visual elements

## Requirements

```
google-generativeai
requests
beautifulsoup4
reportlab
Pillow
matplotlib
```

## Error Handling

- Retry mechanism for failed web requests
- Alternative URL fallback system
- JSON parsing error recovery
- Image download error handling
- Chart generation safeguards

## PDF Report Features

- Task description and timestamp
- Extracted information in structured format
- Automatically generated charts for numerical data
- Relevant images from source websites
- Professional formatting and layout
- Dynamic content organization

## Limitations

- Maximum webpage text processing limit: 10,000 characters
- Maximum 3 images per report to maintain reasonable file size
- Requires active internet connection
- API key rate limits apply

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Google Gemini AI for natural language processing
- ReportLab for PDF generation
- Beautiful Soup for web scraping
- All other open-source contributors

## Support

For support, please open an issue in the repository or contact the maintainers.

## Future Improvements

- [ ] Add support for more chart types
- [ ] Implement caching mechanism
- [ ] Add support for authentication-required websites
- [ ] Improve error reporting
- [ ] Add support for custom PDF templates
- [ ] Implement concurrent web scraping#   A I _ a g e n t  
 