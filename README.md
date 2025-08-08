<p align="center">
  <img src="StringsExtractor.jpg" alt="StringsExtractor Banner" width="700">
</p>

# StringsExtractor

**StringsExtractor** is a tool for parsing `Strings` output files and extracting and categorizing data to quickly reveal suspicious patterns and indicators.  
It is designed to help analysts investigate strings output efficiently, without having to run regex searches manually, and to navigate massive files while quickly identifying relevant information..  

## Features
- Parses `Strings` output files and categorizes extracted data into:
  - IP addresses
  - URLs
  - File paths
  - API calls
  - Emails
  - Registry keys
  - Command lines
- Displays all results in an **All** tab, preserving every line from the original file.
- Ignores blank and whitespace-only lines to keep results clean and relevant.
- Real-time search and filtering with regex and case sensitivity options.
- Exports results to **CSV** or **JSON** for documentation and further analysis.
- Statistics panel showing the total number of lines and counts for each category.
- User-friendly interface designed for quick and easy navigation.

## Download

| Platform | Interface | Download |
|----------|-----------|----------|
| Windows  | GUI       | [StringsExtractor.zip](./StringsExtractor.zip) |

## Usage
- Use the open file option or drag and drop a `.txt` file generated from the `Strings` command into the application.
- Switch between tabs to view categorized results.  
- Use the search bar to filter results by keyword.

## Important Notice

Some antivirus software may flag the executable version of this tool as a false positive.  
This is due to the way the application is packaged with **Python** and **PyInstaller**, which can sometimes trigger heuristic detections.

If you encounter warnings, please consider the following:

- Running the tool in a sandbox environment.
- Adding an exclusion rule for the executable in your antivirus software.
- Temporarily disabling your antivirus software.

## Contact

For questions or feedback, please contact me via https://www.linkedin.com/in/guy-eldad/


Copyright
© 2025 Guy Eldad. All rights reserved.
