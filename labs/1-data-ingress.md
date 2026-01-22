# Week 1 - Web Scraping

This lab builds on the lectures on Data Ingress and involves collecting data from the web via web scraping and using web APIs.

## Before you begin

- Install Anaconda: https://www.anaconda.com/products/individual  
  (You can skip Anaconda if you already have Jupyter Notebook or JupyterLab installed, but Anaconda is recommended because it includes most common data-science libraries.)
- Register for The Guardian REST API key:
  - Follow the steps here: https://bonobo.capi.gutools.co.uk/register/developer
  - On registration you will receive an API key that looks like: `303qwe2k-xxxx-xxxx-xxxx-eff86a248059`
  - You will need this API key to complete the lab tasks

## Lab tasks

We will work with two approaches:

1. Web scraping using Beautiful Soup to extract data from a webpage (Beautiful Soup: https://www.crummy.com/software/BeautifulSoup/)  
2. Using The Guardian REST API (http://open-platform.theguardian.com/) to obtain structured JSON data.

You will complete two corresponding sets of tasks (one using Beautiful Soup, another using the REST API). To get you started, you are given two starter notebooks:

- Web scraping with Beautiful Soup: `1A-web_scraping_beautiful_soup-initial.ipynb`  
- Web scraping using The Guardian REST API: `1B_web_scraping_api-initial.ipynb`

Familiarise yourself with the code blocks in these notebooks, the lab tasks build on them.

Note for the API notebook:
- A sample config file is provided: `sampleconfig.cfg`  
- To use it, rename `sampleconfig.cfg` to `myconfig.cfg` and replace the API key in the file with your key from The Guardian.


### Files 
- [Lab 1 Task Specification]()
- [1A-web_scraping_beautiful_soup-initial.ipynb]()
- [1B_web_scraping_api-initial.ipynb]()
- [sampleconfig.cfg]()