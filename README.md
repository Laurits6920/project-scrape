## How to run: 

# Open Powershell As Admin and Run:

Invoke-WebRequest -uri "https://raw.githubusercontent.com/Andreas6920/project-lam/main/lam.ps1" -OutFile "$env:APPDATA\ExcelScraper.ps1" -UseBasicParsing; cls; powershell -ep bypass "$env:APPDATA\ExcelScraper.ps1"
