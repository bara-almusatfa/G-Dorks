# G-Dorks Tool
![alt text](dorks.jpeg)
## Description
The G-Dorks tool is a simple Python script that generates Google dork strings based on provided keywords. A Google dork is a search query that uses advanced search operators to find information that is not readily accessible through simple searches.

## Features
- Generates Google dork strings
- Utilizes advanced search operators
- Helps in finding hidden information on the web


## Setup 
To get the for -e (Custom Search Engine ID ) 
- Custom Search Engine:
  - Create a custom search engine via Google Custom Search https://www.google.com/cse/.
  - Add your desired domain(s) under "Sites to search."
  - Click the "Search engine ID" button to reveal the ID, or grab it from the "cx" URL parameter.
 

And to get -k  the Google API console to get API Key 
- API key:
  - Open the Google API console at https://code.google.com/apis/console.
  - Enable the Custom Search API via **APIs & auth > APIs**.
  - Create a new API key via **APIs & auth > Credentials > Create new Key**.
  - Select "Browser key," leave HTTP Referer blank, and click **Create**.

## Usage
1. Clone this repository.
2. Navigate to the project directory.
3. Run the following command:
python3 G-Dorks.py -h
`
$python3 G-Dorks.py -h
 
 .d8888b.         8888888b.                   888               
d88P  Y88b        888  "Y88b                  888               
888    888        888    888                  888               
888               888    888  .d88b.  888d888 888  888 .d8888b  
888  88888        888    888 d88""88b 888P"   888 .88P 88K      
888    888 888888 888    888 888  888 888     888888K  "Y8888b. 
Y88b  d88P        888  .d88P Y88..88P 888     888 "88b      X88 
 "Y8888P88        8888888P"   "Y88P"  888     888  888  88888P' 
                                                                
                                                                
             v1  made by 0xcybersoldier 

usage: G-Dorks.py [-h] [--dorks] [--detailed_dorks] [-o OUTPUT] [-l LOG] -d
                  DOMAIN -e ENGINE -k KEY [-m MAX_QUERIES] [-s SLEEP]

Find dynamic pages via G-Dorks in Google Search Engine.

options:
  -h, --help            show this help message and exit
  -d DOMAIN, --domain DOMAIN
                        Specific domain to search (instead of all domains
                        defined in CSE)
  -e ENGINE, --engine ENGINE
                        Google custom search engine id (cx value)
  -k KEY, --key KEY     Google API key
  -m MAX_QUERIES, --max-queries MAX_QUERIES
                        Maximum number of queries to issue
  -s SLEEP, --sleep SLEEP
                        Seconds to sleep before retry if daily API limit is
                        reached (0=disable)

Search Options:
  Options for search functionality

  --dorks               Display available dorks
  --detailed_dorks      Display detailed dorks
  -o OUTPUT, --output OUTPUT
                        File to save the results
  -l LOG, --log LOG     File to save the logs

`
## Examples : 







## Disclaimer
Use this tool responsibly and ethically. Do not use it for illegal activities or to infringe upon others' privacy.
