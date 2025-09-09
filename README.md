# OWL Web Spider 🕷️
[![Python Version](https://img.shields.io/badge/python-3.7%2B-blue)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/OWL-Shadow/stalkeye)

A web spider tool for extracting links from websites with a terminal interface.

## Features

-  Cool ASCII art and Matrix-style animations
-  Multi-level spidering (1-3 levels deep)
-  Automatic results saving with timestamps
-  Built-in error handling and encoding detection
-  Random delays to avoid being blocked
-  Supports all websites with proper HTML structure

## Installation

1. Clone this repository:
```bash
git clone https://github.com/OWL-shadow/spider.git
cd spider
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

## Usage

Run the spider:
```bash
python spider.py
```

Follow the on-screen prompts:
1. Enter the URL you want to spider
2. Choose spidering level (1, 2, or 3)
3. Watch the magic happen!

Results will be automatically saved to a timestamped text file.

## Spidering Levels

- **Level 1**: Extract links from the main page only
- **Level 2**: Extract links from main page + all linked pages
- **Level 3**: Go 3 levels deep (main page → linked pages → their linked pages)


## Requirements

- Python 3.6+
- Internet connection
- Terminal that supports ANSI colors

## Disclaimer

⚠️ **Use Responsibly**: This tool is for educational and legitimate research purposes only. Please:
- Respect website terms of service
- Don't overload servers with requests
- Use appropriate delays between requests
- Follow ethical web scraping practices

## Contributing

Feel free to fork this project and submit pull requests for improvements!

## License

This project is open source. Use it responsibly.

---

*"I often feel that night and shadow are more alive than day and light...."*

Happy (and ethical) hunting!!
