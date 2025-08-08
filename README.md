<p align="center">
  <img src="StringsExtractor.jpg" alt="StringsExtractor Banner" width="700">
</p>

# StringsExtractor

**StringsExtractor** is a tool for parsing `strings` output files and extracting and categorizing strings to quickly reveal suspicious patterns and indicators.  
It is designed for malware analysis, reverse engineering, and large-scale string inspection, allowing analysts to navigate massive output files without losing any lines — including blanks — while quickly identifying relevant data.  

## Features
- Parses very large `strings` output files without losing blank or whitespace-only lines.
- Categorizes extracted strings into:
  - IP addresses
  - URLs
  - File paths
  - Registry keys
  - API calls
  - Command lines
- Real-time search and filtering with regex and case sensitivity options.
- Exports results to **CSV** or **JSON** for documentation and further analysis.
- Dark-themed modern GUI built with **customtkinter**.

## Download

| Platform | Interface | Download |
|----------|-----------|----------|
| Windows  | GUI       | [StringsExtractor.zip](./StringsExtractor.zip) |

## Usage
- Use the file picker or drag-and-drop a `.txt` file generated from the `strings` command into the application.  
- Switch between tabs to view categorized results.  
- Use the search bar to filter results by keyword.

## Important Notice

Some antivirus software may flag the executable version of this tool as a false positive.  
This is due to the way the application is packaged with **Python** and **PyInstaller**, which can sometimes trigger heuristic detections.

If you encounter warnings, consider:
- Running the tool in a sandbox environment.
- Adding an exclusion rule for the executable in your antivirus software.
- Temporarily disabling your antivirus software while using it.

## Contact

For questions or feedback, please contact me via https://www.linkedin.com/in/guy-eldad/

---

**Copyright**  
© 2025 Guy Eldad. All rights reserved.
