# DoScript Installer for PortablePython

This folder provides an optional one-click Windows installer for PortablePython using DoScript.

## What it does
- Downloads the PortablePython zip from GitHub  
- Extracts it to the folder you choose (default shown in prompt)  
- Optionally adds the extracted folder to the user PATH  
- Cleans up the downloaded zip

This is an **optional helper script** — it does not modify the repository code.

## How to run
1. Install DoScript (or ensure the `doscript` runner is available).
2. Open a terminal in this folder.
3. Run: do install.do

(or `doscript install.do` depending on your runner)

## Notes
- The script targets Windows paths (e.g. `C:\PortablePython`). Adjust paths if you prefer another location.
- Adding to system PATH requires administrator rights; the script adds to the user PATH by default.
- If the archive layout changes upstream, the script still extracts the zip but may not find `python.exe` at the expected path. In that case, check the extracted folder manually.

## License & attribution
This helper is provided as-is to simplify setup for beginners. Remove or modify as desired.
