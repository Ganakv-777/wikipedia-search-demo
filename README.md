# Wiki Summary Search

## Overview
A minimal client-side web app to search Wikipedia and display a topic’s title, short summary (extract), and thumbnail (when available) using the Wikipedia REST API.

## Setup
- No build or server required.
- Open index.html in any modern browser.

## Usage
- Enter a topic (e.g., “Ada Lovelace”) and press Search or hit Enter.
- The page fetches https://en.wikipedia.org/api/rest_v1/page/summary/<topic> and displays:
  - Title
  - Summary (extract)
  - Thumbnail image (if available)
- Click “Read full article on Wikipedia” to open the full page.

## License
MIT License

Copyright (c) 2025

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.