### Site Connectivity Checker

#### Overview:
This Python project enables users to check the connectivity status of websites. It provides a straightforward command-line interface (CLI) for users to input one or more website URLs. The script then attempts to establish a connection to each URL and reports back the status, indicating whether the site is reachable or not.

#### Installation:
No additional installations are required beyond Python itself, as the project utilizes built-in Python libraries for network communication.

#### Usage:
1. Run the Python script.
2. The script will prompt you to enter one or more website URLs, separated by commas or spaces.
3. After entering the URLs, press Enter.
4. The script will attempt to connect to each provided website and display the connectivity status for each.
5. The status message will indicate whether the website is reachable or if there was an error connecting to it.

#### Notes:
- The script utilizes Python's built-in `urllib.request` module to establish connections to the provided URLs.
- Users should ensure a stable internet connection for accurate results.
- Connection errors may occur due to various reasons, such as network issues, server downtime, or incorrect URL formatting.

#### Example:
- If you input "https://www.example.com" and "https://www.google.com", the script will attempt to connect to both websites and report back their connectivity status.
- For example, if both sites are reachable, the script will display messages like "https://www.example.com: Reachable" and "https://www.google.com: Reachable".
- If a site is unreachable, the script will display an error message indicating the failure to connect to that particular URL.
are welcome. If you encounter any issues or have suggestions for improvement, please feel free to [submit an issue/create a pull request] on the [GitHub repository/Project page].

Enjoy using the Site Connectivity Checker script for your Python projects!
