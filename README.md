# WordPress XMLRPC Brute Force Tool

This tool is designed to perform brute force attacks on WordPress sites using the XMLRPC interface. It supports three different methods for attempting to log in via XMLRPC.

## Features

- **Multiple XMLRPC Methods**: Supports three different XMLRPC methods for login attempts.
- **Auto-Get Usernames**: Automatically fetches usernames from WordPress API endpoints.
- **Auto-Login to wp-admin**: Verifies successful logins by attempting to access the `wp-admin` dashboard.
## Password Feature

The script supports the following  in the password file 
- `[WPLOGIN]`: Replaced with the WordPress username.
- `[UPPERLOGIN]`: Replaced with the WordPress username in uppercase (e.g., `ADMIN`).
- `[DOMAIN]`: Replaced with the domain name (e.g., `domain.com`).
- `[UPPERDOMAIN]`: Replaced with the domain name in uppercase (e.g., `DOMAIN.COM`).
- `[FULLDOMAIN]`: Replaced with the full domain URL (e.g., `https://domain.com`).



## Technologies and Tools

- ![Python](https://img.shields.io/badge/Python%203.x-3776AB?style=for-the-badge&logo=python&logoColor=white) **Python 3.x**: The main programming language used.
- ![Requests](https://img.shields.io/badge/Requests-3776AB?style=for-the-badge&logo=python&logoColor=white) **Requests**: For making HTTP requests.
- ![Rich](https://img.shields.io/badge/Rich-3776AB?style=for-the-badge&logo=python&logoColor=white) **Rich**: For colorful console output.
- ![urllib3](https://img.shields.io/badge/urllib3-3776AB?style=for-the-badge&logo=python&logoColor=white) **urllib3**: For handling HTTP requests.
- ![alive_progress](https://img.shields.io/badge/alive__progress-3776AB?style=for-the-badge&logo=python&logoColor=white) **alive_progress**: For displaying progress bars.
- ![concurrent.futures](https://img.shields.io/badge/concurrent.futures-3776AB?style=for-the-badge&logo=python&logoColor=white) **concurrent.futures**: For multithreading.



## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/OrdinaryHumans404/XMLRPC_WP.git
    cd XMLRPC_WP
    ```

2. Install the required libraries:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Prepare a file named `list.txt` containing the target URLs, one per line.

3. Run the script:
    ```sh
    python main.py
    ```

4. Choose the XMLRPC method to use:
    - `1`: Brute Force XMLRPC V1
    - `2`: Brute Force XMLRPC V2
    - `3`: Brute Force XMLRPC V3
---
## Example

![image](https://github.com/user-attachments/assets/39793495-6591-4bc9-97c1-4b5d33c6cad7)

---
## Notes

- Ensure you have permission to test the target sites.
- Use responsibly and ethically.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


## Author

- ![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white) **D-V** 

## Greets To

- k4l0nk - eLV1n4 - h0rCuX - X-Line

## Acknowledgements

- Thanks to the contributors and supporters mentioned in the script.

## Disclaimer

- This script is intended for educational purposes only. Unauthorized use of this script to access or attempt to access systems without permission is illegal and unethical. The authors and contributors do not condone or support any illegal activities. Use this tool responsibly and only on systems you have explicit permission to test.
