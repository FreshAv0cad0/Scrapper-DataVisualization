# Amazon Review Scraper

## Overview

This project aims to scrape product reviews from Amazon.in efficiently. It includes pre-built functionality to handle captchas encountered during scraping. To prevent IP bans, it's recommended to run the script with a VPN. Additionally, setting up POWER BI is necessary if you want live graphing of product reviews in real-time.

## Features

- Scrapes product reviews from Amazon.in
- Handles captchas using built-in functionality
- Supports real-time graphing of product reviews with POWER BI setup

## Prerequisites

Before running the script, ensure you have the following prerequisites installed:

- Python 3.x
- Selenium
- POWER BI (for live graphing)

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/amazon-review-scraper.git
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the script:

    ```bash
    python scrape.py
    ```

4. Make sure to run the script with a VPN to avoid IP bans.

## Configuration

You can configure the script by adjusting the following parameters:

- `time.sleep`: Increase the Selenium driver sleep time if facing captchas frequently.

## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvement, feel free to open an issue or submit a pull request.


## Disclaimer

This project is for educational purposes only. Use it responsibly and at your own risk.

