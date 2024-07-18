# Scraping Bot

## Overview

This project is a web scraping bot that extracts data from various websites and compiles it into structured formats.

## Project Structure

- **app.py**: Main script for the web scraping bot.
- **requirements.txt**: Python dependencies for the project.
- **envname**: Virtual environment (excluded from Git).
- **output**: Directory where the scraped data is saved (excluded from Git).
- **.env**: Environment variables file (excluded from Git).

## Setup

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd scraping-bot
   ```

2. Create and activate the virtual environment:

   ```bash
   python -m venv envname
   source envname/bin/activate   # On Windows use `envname\Scripts\activate`
   ```

3. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the bot:
   ```bash
   python app.py
   ```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
