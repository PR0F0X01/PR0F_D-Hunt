


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


## Usage
1. Clone the repository to your local machine:
   ```
   git clone https://github.com/PR0F0X01/PR0F_D-Hunt.git
   ```

2. Navigate to the directory:
   ```
   cd PR0F_D-Hunt
   ```

3. Run the script with the necessary arguments:
   ```
   python3 domain_security_tool.py -f <file_path> -o <output_folder> -s <status_codes> -m <method> ...
   ```
   - Replace `<file_path>` with the path to the file containing URLs.
   - Replace `<output_folder>` with the desired output folder path.
   - Replace `<status_codes>` with the status codes to save, separated by commas.
   - Replace `<method>` with the desired HTTP method (optional).

## Requirements
- Python 3.x
- Requests library (install via pip: `pip install  -r requests`)

## License
This project is licensed under the MIT License .
```
