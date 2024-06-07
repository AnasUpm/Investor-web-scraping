
Investor Finder is a Python script that scrapes and processes investor data from a webpage, allowing users to search for the most relevant investors based on a specified market. This script fetches investor details from a specific webpage, processes the information, and returns the top 3 investors matching the user's input market.

## Features

- Scrapes investor data from a given webpage.
- Extracts and stores relevant investor details.
- Allows users to input a market of interest.
- Returns the top 3 investors matching the specified market.

## Requirements

- Python 3.x
- `requests` library
- `beautifulsoup4` library

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/investor-finder.git
    cd investor-finder
    ```

2. Install the required Python libraries:
    ```sh
    pip install requests beautifulsoup4
    ```

## Usage

1. Run the script:
    ```sh
    python investor_finder.py
    ```

2. When prompted, enter the market you are interested in:
    ```sh
    Enter the market you are interested in: technology
    ```

3. The script will output the top 3 investors matching the specified market, including their details and profile URLs.

## Example Output

```
Enter the market you are interested in: technology

Top 1 Investor:
Name: John Doe
Type: Angel Investor
Locations: Kuala Lumpur, Malaysia
Markets: technology, healthcare
Past Investments: Startup A, Startup B
Profile URL: https://angelmatch.io/investors/john-doe

Top 2 Investor:
Name: Jane Smith
Type: Venture Capitalist
Locations: Penang, Malaysia
Markets: technology, finance
Past Investments: Startup C, Startup D
Profile URL: https://angelmatch.io/investors/jane-smith

Top 3 Investor:
Name: Alice Johnson
Type: Angel Investor
Locations: Selangor, Malaysia
Markets: technology, education
Past Investments: Startup E, Startup F
Profile URL: https://angelmatch.io/investors/alice-johnson
```

## Notes

- Ensure you have a stable internet connection as the script fetches data from an online source.
- The webpage structure may change over time, which could require updates to the scraping logic.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
```

Save the above content in a file named `README.md` in your repository. This will format the README properly on GitHub, making it easier to read and navigate.
