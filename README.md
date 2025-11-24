# Pinoy California Blogger Theme

## Overview
This repository contains the Blogger theme for Pinoy California. This theme has been updated to improve its Search Engine Optimization (SEO) and social media sharing capabilities.

## Author and License
- **Author:** Nash Ang (PinoySeoul Media Enterprise)
- **License:** MIT License (or appropriate open-source license, to be confirmed if different)

## Features
This updated theme includes the following improvements:

1.  **Enhanced SEO Implementation:**
    *   **Improved Title Tag Logic:** Title tags are now more dynamic and SEO-friendly, preventing redundant titles and ensuring relevant keywords are used for different page types (e.g., search results, individual posts).
    *   **Robust Meta Description Handling:** Meta descriptions now have proper fallbacks, utilizing `data:blog.metaDescription` or `data:post.snippet` to ensure every page has a concise summary for search engines.
    *   **Removed Deprecated Meta Keywords:** Outdated meta keywords have been removed to streamline the `<head>` section and adhere to modern SEO best practices.

2.  **Better Website Schema Implementation:**
    *   **Dynamic Site Title in Schema:** Hardcoded site titles in schema markup (e.g., `itemprop='name'`) have been replaced with `data:blog.title`, ensuring the correct blog title is displayed across subdomains and for structured data.
    *   **Added WebSite JSON-LD Schema:** A comprehensive `WebSite` schema has been added using JSON-LD, providing search engines with structured information about the entire website and its search functionality.

3.  **Improved Social Media Sharing:**
    *   **Comprehensive OpenGraph Tags:** Added `og:description` with fallbacks and implemented a default image for `og:image` when no post image is available, ensuring rich snippets when shared on platforms like Facebook and LinkedIn.
    *   **Enhanced Twitter Card Meta Tags:** Incorporated `twitter:title`, `twitter:description`, and `twitter:image` with appropriate fallbacks, optimizing content previews when shared on X (formerly Twitter).

## Installation and Usage
To use this theme on your Blogger blog:
1.  Navigate to your Blogger dashboard.
2.  Go to **Theme**.
3.  Click on the "..." (three dots) icon next to "Customize" and select **Edit HTML**.
4.  Copy the entire content of the `theme.xml` file from this repository.
5.  Paste the copied content into the Blogger HTML editor, replacing the existing theme code.
6.  Click **Save**.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Support
For any issues or questions, please refer to the issues section of this repository.
