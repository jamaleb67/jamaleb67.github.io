# Web Scraping and other Text Applications
As noted in previous discussions, the IC utilizes the five -INT sources in the forms of documents and reports.

However, given the importance and dynamic nature of data and information as it relates to the IC's Mission, thee is a much greater dependence on data and information to be available in real-time. 

As a result, websites have become much more of a platform or medium for consideration because much of the information is not available in real-time, is at least more current than that found in reports and documents. 

Hence, techniques such as web crawling and web scraping have garnered a lot of attention

**Web crawling**
    - Focus on the entire website and each page on the site
    - Indexing and searching for content are the main objectives<br>
**Web Scraping**
    - Focus on certain data and information
    - Extracting and organizaing content are the main objectives
    - Process to collect, structure, and store data from websites.

Unfortunately, there are numerous challenges with dealing web pages, i.e., 
1. Constructed using HTML, which is unstructured, not annotated, nor well-suited for analysis
2. Have text and HTML elements, but only want to extract text

As a result, web pages require libraries to put text in the "right" format. Some of the most well-known libraries are:<br>

**BeautifulSoup**: Powerful Python library for 
    - Scraping live websites
    - Extracting data embedded in HTML<br>
**Request**
    - De facto standard for making HTTP requests in Python via a simple Application Programming Interface (API).

**API**
    - Requests data in structured format
    - Not limited to public environments

**Selenium**
    - Open source framework for automating browsers
    - Webdriver
        - Collection of APIs used to automate web application testing
    - Chromedriver
        - Mechanism used to control browser. 
