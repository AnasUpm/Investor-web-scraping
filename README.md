# Investor Finder
Investor Finder is a Python script that scrapes and processes investor data from a webpage, allowing users to search for the most relevant investors based on a specified market. This script fetches investor details from a specific webpage, processes the information, and returns the top 3 investors matching the user's input market.

Features
Scrapes investor data from a given webpage.
Extracts and stores relevant investor details.
Allows users to input a market of interest.
Returns the top 3 investors matching the specified market.
Requirements
Python 3.x
requests library
beautifulsoup4 library
Installation
Clone the repository:

sh
Copy code
git clone https://github.com/your-username/investor-finder.git
cd investor-finder
Install the required Python libraries:

sh
Copy code
pip install requests beautifulsoup4
Usage
Run the script:

sh
Copy code
python investor_finder.py
When prompted, enter the market you are interested in:

sh
Copy code
Enter the market you are interested in: technology
The script will output the top 3 investors matching the specified market, including their details and profile URLs.

Example Output
yaml
Copy code
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
