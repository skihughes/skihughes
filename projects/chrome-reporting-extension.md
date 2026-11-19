# Automated Data Extraction & Reporting Tool

I built this Chrome extension at Zehnder’s of Frankenmuth to automate collecting records spread across multiple pages and prepare them for reporting. The extension processed more than 30,000 booking and customer records.

## How it worked

1. The extension collected records across multiple pages.
2. Background scripts used `chrome.storage.local` to store the collected data and combine it for processing.
3. The pipeline cleaned and checked the records before passing them to XLSX.
4. XLSX generated a formatted Excel workbook for reporting.

**Tools** · Chrome extension APIs, `chrome.storage.local`, background scripts, XLSX.
