<h1 align="center">
  <a href="#"><img src="https://ibb.co/xGKbBkN" alt="Logo of Program" width="400"></a>
  <br>
    Web Scraping TMDb Movies Directory
  <br>
</h1>

<h3 align="center">Scraping unstructured data from TMDb and structuring it to Pandas DataFrame</h3>
  
<p align="center">
  <img src="https://forthebadge.com/images/badges/made-with-python.svg" alt="made with python">
  <img src="https://forthebadge.com/images/badges/built-with-love.svg" alt="built with love">
</p>

<p align="center">
  <a href="#introduction">Introduction</a> •
  <a href="#requirements">Requirements</a>  •
  <a href="#installation">Installation</a> •
  <a href="#working-of-bot">Working of Bot</a>               •
  <a href="#how-it-works">How it Works</a> •
  <a href="#thanks">Thanks ❤</a>
</p>

---

## Introduction
* Web Scraping is an automatic method to obtain large amounts of data from websites. Most of this data is unstructured data in an HTML format which is then converted into structured data in a spreadsheet or a database so that it can be used in various applications.

* In this project, I would be scraping TMDb website which is an online movie directory. I would be later structuring data in form of a DataFrame, which could be further used as a DataSet for various Applications.

* Tools/Technologies used in this Project are Python, requests, Beautiful Soup, Pandas.

## Requirements

- Python 3.3+
- macOs or Linux or Windows
- Pandas
- requests
- Beautiful Soup

## Installation

### Building the source code

#### 1. Clone the repository
```sh
git clone https://github.com/arhamshah/Movies-Web-Scraper.git
cd Movies-Web-Scraper
```
#### 2. Download & Install all the Dependencies
```sh
pip install -r requirements.txt
``` 

## Raw Data is structured into Pandas DataFrame
<a href="#"><img src="https://ibb.co/PwyYMbL" alt="Final Outcome DataSet" width="300"></a>

## How it Works
- Data from TMDb is extracted using Beautiful Soup.
- As TMDb uses pagination, data is extracted from different pages in a loop.
- Specific Data of movies is extracted from their inner page.
- Final Result is stored in form of a Pandas DataFrame.
 

## Thanks
- [TMDb](https://www.themoviedb.org/) for providing their data. 
- Shout-out to developers & contributors of [requests](https://docs.python-requests.org/en/master/), [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/),  [Pandas](https://pandas.pydata.org/docs/).
