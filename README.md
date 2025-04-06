# Web Task Assistant 🤖

A powerful Python-based web task assistant powered by Google's Gemini AI that interprets tasks, extracts web information, and generates detailed PDF reports.

<div align="center">

![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)
![Gemini](https://img.shields.io/badge/AI-Gemini-orange.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

</div>

## ✨ Features

- **AI-Powered Task Interpretation**: Leverages Gemini AI for understanding complex tasks
- **Smart Web Scraping**: Automated data extraction with retry mechanisms
- **Visual Reports**: Generates PDF reports with charts and images
- **Error Handling**: Robust fallback systems for failed requests
- **Data Visualization**: Dynamic generation of charts (Bar, Pie, Line)

## 🚀 Quick Start

### Prerequisites

- Python 3.7 or higher
- Google API key for Gemini AI

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/web-task-assistant.git
   cd web-task-assistant
   ```

2. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```

3. Configure environment variables
   - Copy the example environment file:
     ```bash
     cp .env.example .env
     ```
   - Get your API key from [Google AI Studio](https://makersuite.google.com/app/apikey)
   - Update the `GOOGLE_API_KEY` in `.env` file

4. Run the application
   ```bash
   python web_task_assistant.py
   ```

## 💻 Usage

Run the assistant:
```bash
python web_task_assistant.py
```

Example tasks:
```
- "Find the top 5 AI related headlines"
- "Get the latest cryptocurrency prices"
- "Summarize recent space exploration news"
```

## 📁 Project Structure

```
web-task-assistant/
├── web_task_assistant.py   # Main script
├── requirements.txt        # Dependencies
└── README.md              # Documentation
```

## 🛠️ Core Functions

| Function | Description |
|----------|-------------|
| `interpret_task()` | Task analysis using Gemini AI |
| `fetch_webpage()` | Web content retrieval with retries |
| `extract_information()` | Smart data extraction |
| `create_chart()` | Data visualization |
| `save_results_to_file()` | PDF report generation |

## 📦 Dependencies

```python
google-generativeai>=0.3.0
requests>=2.31.0
beautifulsoup4>=4.12.0
reportlab>=4.0.0
Pillow>=10.0.0
matplotlib>=3.7.0
```

## 🔒 Limitations

- Text processing limit: 10,000 characters
- Maximum 3 images per report
- Requires internet connection
- API rate limits apply

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

## 🙏 Acknowledgments

- [Google Gemini AI](https://deepmind.google/technologies/gemini/)
- [ReportLab](https://www.reportlab.com/)
- [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/)

## 📫 Support

For support:
- Open an [issue](https://github.com/yourusername/web-task-assistant/issues)
- Contact: your.email@example.com

## 🔜 Roadmap

- [ ] Additional chart types
- [ ] Caching system
- [ ] Authentication support
- [ ] Enhanced error reporting
- [ ] Custom PDF templates
- [ ] Concurrent scraping
#   A I _ a g e n t  
 