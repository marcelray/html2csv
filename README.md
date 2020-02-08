# html2csv
A Python-based tool to convert HTML tables to CSV without the use of BeautifulSoup.

The original author of this tool is Sebastien Sauvage. His original version can be found at [https://sebsauvage.net/python/html2csv.py]()

### Changes to the original:

- Updated to support Python 3
- Handles edge UTF-8 cases
- Output `<th>` as column headers in the first CSV row
