


```markdown
# PR0F_D-Hunt
## Description
It is a tool used to extract domains that are of great importance in the context of security testing and to search for security vulnerabilities in login pages that require authentication.
## Features
- **Domain Filtering:** The script filters domains based on specified criteria, allowing users to focus on extracting domains with high importance.
 
- **Authentication Pages:** Targets domains hosting authentication pages, where sensitive information is often exchanged, enhancing the focus on security-critical areas.

- **Custom Configurations:** Supports custom configurations, empowering users to tailor the tool to their specific security testing requirements.

- **Ease of Use:** With a simple command-line interface, it offers ease of use for both beginners and experienced security professionals.

- **Concurrency:** Utilizes multithreading for concurrent processing, optimizing performance when dealing with a large number of URLs.

- **Proxy Support:** Includes proxy support, allowing users to route requests through proxy servers for enhanced anonymity and flexibility.

- **Flexible HTTP Methods:** Supports various HTTP methods (GET, POST, PUT, DELETE, PATCH), providing flexibility in request types for different testing scenarios.

## Installation

To get started with the  PR0F_D-Hunt , follow these steps:

1. Clone this repository:

```bash
git clone https://github.com/PR0F0X01/PR0F_D-Hunt.git
cd  PR0F_D-Hunt
```

2. Install the required dependencies:

```bash
pip3 install -r requirements.txt
```
## Usage
python3 PR0F_D-Hunt.py -h                       
usage: PR0F_D-Hunt.py [-h] -f FILE -o OUTPUT [-p PROXY] -s STATUS [-os OUTPUT_SEARCH] [-m {GET,POST,PUT,DELETE,PATCH}]
                      [-H HEADERS] [-t THREADS]

Download responses from given URLs.

options:
  -h, --help            show this help message and exit
  -f FILE, --file FILE  Path to file containing URLs.
  -o OUTPUT, --output OUTPUT
                        Output folder path.
  -p PROXY, --proxy PROXY
                        Proxy server address.
  -s STATUS, --status STATUS
                        Status codes to save, comma-separated.
  -os OUTPUT_SEARCH, --output-search OUTPUT_SEARCH
                        Output file path to save URLs containing search keywords.
  -m {GET,POST,PUT,DELETE,PATCH}, --method {GET,POST,PUT,DELETE,PATCH}
                        HTTP method to use for requests.
  -H HEADERS, --headers HEADERS
                        Custom headers to include in the request.
  -t THREADS, --threads THREADS
                        Number of concurrent threads.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

We welcome contributions from the community. If you'd like to contribute, please fork the repository and create a pull request.

```
