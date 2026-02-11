# Project Conventions

- **Encoding**: UTF-8 without BOM.
- **Line Endings**: CRLF (`
`).
- **Final Newline**: Files must end with one empty line.
- **Verification**: Run `pwsh -ExecutionPolicy Bypass -File .\bin	est.ps1` after any changes.

# Scoop Manifest Details

- **Checkver**: Prefer `github` if using GitHub releases.
- **Autoupdate**: Must include `architecture` and `hash`.
- **Bin**: Specify the executable name found in the archive.
