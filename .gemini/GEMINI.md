# Project Specific Instructions

- This project is a Scoop bucket for Windows environment.
- All text files (JSON, Markdown, PowerShell scripts, etc.) must adhere to the following conventions:
    - Line endings must be **CRLF** (`\r\n`).
    - Files must end with **one empty line (newline)**.
- After editing or creating files, ensure they conform to these rules and apply conversions if necessary.
- When executing PowerShell scripts (e.g., `bin/*.ps1`), use `pwsh -ExecutionPolicy Bypass -File <path>`.
- After making changes, run `pwsh -ExecutionPolicy Bypass -File .\bin\test.ps1` locally to verify there are no violations.
