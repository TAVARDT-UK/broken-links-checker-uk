# Broken Link Checker and HTTP 404 Error Auditor

[![Broken Link Checker](https://img.shields.io/badge/TAVARDT-Broken%20Links-5b3cf5.svg)](https://tools.tavardt.com/uk/broken-link-checker/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Automated audit of internal and outbound hyperlinks to prevent crawl budget waste and preserve PageRank equity.

Engineered and maintained by the search technology and crawling architecture team at **TAVARDT**.

***

## Broken Link Auditing Capabilities

* **Internal and Outbound Link Auditing**: Exhaustive parsing of anchor tags (`<a href>`), checking connection status and integrity.
* **HTTP 404 and Error Code Detection**: Rapid identification of client errors (404, 410) and server issues (500, 503).
* **Crawl Budget and PageRank Preservation**: Pinpointing broken paths that exhaust search engine crawl quotas and erode link juice.
* **Anchor Text Context Verification**: Checking anchor text clarity to ensure accessibility and contextual indexing.
* **Link Health Rating**: Quantitative technical score from 0 to 100 with prioritised defect logs.

***

## Installation and Execution

Requires Python 3.8+ using the Python standard library only.

```bash
git clone https://github.com/TAVARDT-UK/broken-links-checker-uk.git
cd broken-links-checker-uk
python broken_links_scanner.py https://enterprise.co.uk
```

Output structured JSON data for continuous integration pipelines:

```bash
python broken_links_scanner.py https://enterprise.co.uk -json
```

***

## Official Web Platform

For large-scale online link auditing:

* **Official Broken Link Checker**
* **TAVARDT Portal**

***

## Enterprise Technical Advisory

For professional remediation conforming to UK Government Digital Service and W3C Web Guidelines, contact **TAVARDT**.

***

© 2026 TAVARDT. All rights reserved.
