# Privacy Policy for URLMinerX

**Last updated:** November 21, 2026  
**Extension:** URLMinerX  
**Developer:** Nitesh Kumar

## Overview

URLMinerX is a Chrome extension for discovering and extracting historical article URLs from user-selected websites, including through sitemaps, pagination, Load More controls, and infinite scrolling.

This policy describes the behavior of the URLMinerX Chrome extension version 1.0.0.

## Information URLMinerX Processes

When you use URLMinerX, it processes URLs, links, and relevant webpage content from the websites you choose to inspect. It may read sitemap files, page structure, and article publication-date information to identify matching article URLs.

URLMinerX saves extracted URL results in your browser using Chrome's local extension storage (`chrome.storage.local`). You can also export extracted URLs to a CSV file on your device.

## Website Requests and Access

URLMinerX requests broad host access because users may extract URLs from websites on many different domains. The extension makes requests to websites as part of its URL discovery functionality. These requests go to the websites being inspected, not to a developer-operated collection server. The extension's request code may include browser credentials, such as cookies, when contacting a website; the destination website may therefore receive normal request information associated with your browsing session.

## Data Sharing and Collection

The reviewed extension package does not contain a developer-operated analytics, advertising, or telemetry endpoint and does not include code that uploads extracted results to a developer-controlled server.

URLMinerX does not sell extracted URLs or user data. Website operators may receive requests made while you use the extension, as described above. If you export results, the CSV file is saved on your device and its subsequent handling is under your control.

## Storage and Retention

Extracted URL results are stored locally in the Chrome browser profile using extension storage. They may remain available between sessions until you clear the extension's stored data, remove the extension, or otherwise delete the browser profile data. CSV exports remain wherever you save them until you delete them.

## Permissions

- **activeTab:** Access the active tab when you invoke the extension.
- **scripting:** Inspect webpages and interact with page elements needed for extraction.
- **sidePanel:** Display the URLMinerX interface alongside the webpage.
- **storage:** Save extracted URL results locally in the browser.
- **Host access (`<all_urls>`):** Inspect user-selected websites and discover URLs across different domains.

## Data Security

URLMinerX does not require an account to perform its core functions. Extracted results are stored in your browser's local extension storage. Website requests are subject to the security and privacy practices of the destination websites and your browser.

## Your Choices

You control which websites to inspect and when to run extraction. You can export extracted URLs, clear extension storage through your browser's extension/site-data controls, or uninstall URLMinerX. You can also delete exported CSV files from your device.

## Changes to This Policy

This policy may be updated if URLMinerX's functionality or data-handling practices change. The latest policy should be published alongside the extension's project documentation.

## Contact

For privacy questions or issues, please open an issue in the URLMinerX GitHub project repository or contact the developer through the support contact listed on the Chrome Web Store listing.
