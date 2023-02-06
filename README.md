# 🌐 Python Web Scraping Snippets

[![Downloads](https://img.shields.io/packagecontrol/dt/Python%20Web%20Scraping%20Snippets)](https://packagecontrol.io/packages/Python%20Web%20Scraping%20Snippets)
[![Tag](https://img.shields.io/github/v/tag/futureprogrammer360/Python-Web-Scraping-Snippets?sort=semver)](https://github.com/futureprogrammer360/Python-Web-Scraping-Snippets/tags)
[![Repo size](https://img.shields.io/github/repo-size/futureprogrammer360/Python-Web-Scraping-Snippets)](https://github.com/futureprogrammer360/Python-Web-Scraping-Snippets)
[![License](https://img.shields.io/github/license/futureprogrammer360/Python-Web-Scraping-Snippets?style=flat-square)](https://github.com/futureprogrammer360/Python-Web-Scraping-Snippets/blob/master/LICENSE)

[Python Web Scraping Snippets](https://github.com/futureprogrammer360/Python-Web-Scraping-Snippets) is a collection of [Sublime Text](https://www.sublimetext.com/) snippets for web scraping and HTML parsing in Python.

## 💻 Installation

The easiest way to install Python Web Scraping Snippets is through [Package Control](https://packagecontrol.io/packages/Python%20Web%20Scraping%20Snippets). After it is enabled inside Sublime Text, open the command palette and find **Package Control: Install Package** and press `ENTER`. Then, find **Python Web Scraping Snippets** in the list. Press `ENTER` again, and this package is installed!

## 📈 Snippets

* [Imports](#imports)
* [BeautifulSoup4](#beautifulsoup4)
* [Requests](#requests)
* [Requests-HTML](#requests-html)

### Imports

Import snippets start with `i` followed by the import alias.

| Trigger             | Description                                  |
|---------------------|----------------------------------------------|
| `ibs`               | `from bs4 import BeautifulSoup`              |
| `irequests`         | `import requests`                            |
| `iAsyncHTMLSession` | `from requests_html import AsyncHTMLSession` |
| `iHTMLSession`      | `from requests_html import HTMLSession`      |

### BeautifulSoup4

| Trigger      | Description                    |
|--------------|--------------------------------|
| `bs`         | `bs4.BeautifulSoup`            |
| `find`       | `bs4.BeautifulSoup.find`       |
| `find_all`   | `bs4.BeautifulSoup.find_all`   |
| `prettify`   | `bs4.BeautifulSoup.prettify`   |
| `select`     | `bs4.BeautifulSoup.select`     |
| `select_one` | `bs4.BeautifulSoup.select_one` |

### Requests

| Trigger   | Description        |
|-----------|--------------------|
| `delete`  | `requests.delete`  |
| `get`     | `requests.get`     |
| `head`    | `requests.head`    |
| `patch`   | `requests.patch`   |
| `post`    | `requests.post`    |
| `put`     | `requests.put`     |
| `request` | `requests.request` |

### Requests-HTML

| Trigger            | Description                      |
|--------------------|----------------------------------|
| `AsyncHTMLSession` | `requests_html.AsyncHTMLSession` |
| `HTMLSession`      | `requests_html.HTMLSession`      |

The snippet files are in the [`snippets`](https://github.com/futureprogrammer360/Python-Web-Scraping-Snippets/tree/master/snippets) folder of [this GitHub repository](https://github.com/futureprogrammer360/Python-Web-Scraping-Snippets).
