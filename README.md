# Pages24 Scraper

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
  - [Input](#input)
  - [Executing the Code](#executing-the-code)
- [Output Format](#output-format)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Welcome to the **Pages24 Scraper**. This repository houses a powerful scraper designed to extract valuable data from the [Pages24](https://www.pages24.com/) website. As a platform providing diverse information, Pages24 offers a range of listings and details. This scraper streamlines the process of collecting data from Pages24, creating a valuable dataset for various applications.

## Features

- Efficiently extracts data from the Pages24 website.
- Provides a comprehensive dataset including listing details.
- Facilitates analysis, database creation, and other creative projects using the extracted data.

## Installation

Follow these steps to set up the Pages24 Scraper:

### Prerequisites

- Python 3.9
- Install required Python packages:
  - BeautifulSoup4: `pip install beautifulsoup4`
  - Requests: `pip install requests`

### Instructions

1. Clone this repository to your local machine using Git:

   ```bash
   git clone https://github.com/adil6572/pages24-scraper.git
   cd pages24-scraper
   ```

2. Install the required Python packages:

   ```bash
   pip install beautifulsoup4 requests
   ```

## Usage

To utilize the Pages24 Scraper, follow these steps:

### Input

1. Open the main file (`main.py`)

#### Customize the Parameters as per mention in (`main.py`)

```python

    # Input Parameters for the Scraper
    FILENAME = 'data.csv'
    scrape_url = 'https://www.pages24.com/somerset-tx/san-antonio'


```

1. Open the main file (`main.py`) and Replace `FILENAME = data.csv` with your preferred filename.

2. Rpelace `scrape_url = 'YOUR URL'` to the url that you want to scrape from pages24 website

### Executing the Code

1. Run the scraper:

   ```bash
   python main.py
   ```

2. The scraped data will be saved in a CSV file with items structured as follows:

### Output Format

```csv
name,url,street_address,locality,postal_code,phone_number,description,keywords
San Antonio River Authority,https://www.pages24.com/somerset-tx/1814639-san-antonio-river-authority,20334 S Payne Rd,Somerset,78069,(830) 429-2160,Providers of in Somerset,

```

You can now use this CSV file for various purposes, such as analysis, database creation, or any other creative project you have in mind.

## Contributing

We welcome contributions from the community to enhance the **Pages24 Scraper** project. If you have ideas for improvements, encounter issues, or want to add new features, feel free to open an issue or submit a pull request. Your contributions are valuable and play a crucial role in the ongoing development of this project. Thank you for considering being a part of our open-source community!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
