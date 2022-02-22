# CarBombingTerror

1. Importe required pakages such as selenium, beautifulsoup, numpy and pandas
2. Load the selenium webbrowser using webdriver.Edge()
3. commit to the required url
4. After, load the url using browser.get(url)
5. get the html code of the required url using browser.page_source
6. Load this html code into the BeautifulSoup using : soup = BeautifulSoup(html, 'html.parser')
7. Now, go the url webpage --> right click --> inspect mode
8. In the inspect mode try to locate the required html code(Table, class) of the required table : table.wikitable.sortable.jquery-tablesorter
9. Now we are going to extract the top row (Year, Date, Country etc...) using 'th'
10. 
