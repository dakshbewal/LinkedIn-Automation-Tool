
# LinkedIn Automation Tool

## Overview

This tool automates profile visits and follows on LinkedIn using Selenium and Python.

## How It Works

### Setup

1. **Setup Python Environment**
   - Ensure you have Python installed.
   - Install necessary packages: `selenium`, `webdriver_manager`, `pandas`, `beautifulsoup4`.

2. **Setup Cookies**
   - Run `cookies.py` to log in to LinkedIn manually and save cookies to `cookies.pkl`.

### Main Script Execution

- Run `main.py` to execute the automation:
  - Loads LinkedIn homepage with saved cookies.
  - Searches for profiles based on specified queries like "Talent Acquisition", "IT recruiter".
  - Scrolls down to load more profiles and filters non-connections.
  - Visits each profile, follows if possible, and saves profile URLs to `visited_profiles.csv`.

## Benefits

- **Time Efficiency**: Automates repetitive tasks of profile visits and follows.
- **Networking**: Increases profile visibility and engagement.
- **Customization**: Easily modify search queries and automation parameters.
- **Data Tracking**: Saves visited profiles to CSV for tracking and analysis.

## Setup Instructions

1. **Clone Repository**
   ```bash
   git clone https://github.com/your-username/linkedin-automation.git
   cd linkedin-automation
Install Dependencies

```bash
pip install -r requirements.txt
```
Setup Cookies

Run cookies.py and log in to LinkedIn manually.
Press Enter to save cookies as cookies.pkl.
Run Automation

```bash
python main.py
```
Requirements
Ensure you have the following dependencies installed:

beautifulsoup4==4.10.0
pandas==1.3.5
selenium==4.1.0
webdriver-manager==3.5.2
Note
Ensure you have a stable internet connection and LinkedIn account for proper functionality.
Adjust search_queries in main.py to target specific profiles relevant to your networking goals.
Contributions
Contributions are welcome! Feel free to fork the repository, make improvements, and submit pull requests.
