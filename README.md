# Advance Web Scraping Tool (Public)

The Web Scraping Tool is a GUI-based application built with Python + CustomTkinter that allows users to easily scrape websites without coding knowledge.
It supports multiple data types (text, links, images, tables, forms) and saves results in different formats for professional use.

:- Key Features
>URL Manager – Add, save, and manage multiple URLs.
>Scraping Options – Extract text, links, images, tables, and form data.
>File Storage – Save extracted data into:

CSV
Excel
TXT
Word

>User-Friendly GUI – Built with CustomTkinter for a clean, modern interface.
>Modular Codebase – Separate modules (url_manager.py, scraper.py, storage.py, gui.py) for easy maintenance.
>Tested on Real Websites – Handles Wikipedia pages, blogs, and data-rich sites.

:- Tech Stack

Python (Core language)

CustomTkinter (GUI)

Requests (HTTP requests)

BeautifulSoup4 (HTML parsing)

Pandas (Table handling & DataFrames)

OpenPyXL (Excel writing)

python-docx (Word file export)

:- Architecture / Flow

User enters or selects URL from URL Manager.

Scraper module fetches and parses data.

User selects data type to extract (links, images, tables, etc.).

Storage module saves data in chosen format.

User opens results via FileDialog for review.

 Future Roadmap

 User login system

 Scraping dynamic pages (Selenium / Playwright)

 API scraping support

 Automation & scheduling

 Login scraping (authenticated sessions)

 Database integration (SQLite/PostgreSQL)

 Analytics dashboard

:- Version History

v1 – Basic GUI + URL input

v2 – Scraping text, links, images

v3 – Table & form scraping + CSV/Excel export

v4 (Stable Release) – Added TXT & Word storage + polished structure

:- Author

Tahir Khan – Python & Backend Developer