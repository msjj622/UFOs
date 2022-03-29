# UFOs
## Overview of analysis:
The purpose of this analysis is to allow users to filter multiple criteria by providing searching tables in different sectors such as city, state, country and shape. Dana's webpage already povided information as her intention, however she wanted to provide more searching table filters for users to find their seeking information fast.

![webpage_image](https://github.com/msjj622/UFOs/blob/main/description%20image/webpage_image.png)

The result of page will look this this image below.
![filter_webpage_image](https://github.com/msjj622/UFOs/blob/main/description%20image/filter_webpage_image.png)

## Analysis Results:
First of all, you can type data on data search table. For example, 1/13/2010 like the data should typed same way like the pre-data (gray colour text) as shown above image otherwise it can't find data. the date exackly has to match. The result would look like this image below.

![search_webpage](https://github.com/msjj622/UFOs/blob/main/description%20image/1.png)

After that, you can narrow information if you want to find specific data. For example, white oak like the pre-data (gray colour text) as shown above image. The same of city, state, country & shape must be matched with the data otherwise it can't read the data.

![search_webpage](https://github.com/msjj622/UFOs/blob/main/description%20image/2.png)


## Anaysis Coding:
First of all, create more filters and searching tables by using '<li>' and put tilte for each table as shown image below.

![filter_html_image](https://github.com/msjj622/UFOs/blob/main/description%20image/filter_html_image.png)

Second, link data with app.js file. Created empty filter variable to keep tracks of all filters as an object. After that, using 'd3.select(#datetime)' and 'filteredData = filteredData.filter(row => row.datetime === date)', this can bring data with exact date user typed.
  
![filter_datetime_image](https://github.com/msjj622/UFOs/blob/main/description%20image/filter_datetime_image.png)

Third, create a variable for the filtered data to hold the updated table data based on the user input. Let's say user typed date and entered, and typed city and entered again after she got the data. In this code, it will save the data user input and hold it.
![hold_data_image](https://github.com/msjj622/UFOs/blob/main/description%20image/hold_data_image.png)
  
## Analysis Summary:
- Describe one drawback of this new design
One thing I would wanted to fix on the webpage is to fix the search tables at the same location weather the window is small or large. As the below image, it keeps moving with a little of move that I make a large. I would like to make it fixed or give a limit at the certain pixel on the webpage window, the search table would stay the same location.

![one_drawback_image](https://github.com/msjj622/UFOs/blob/main/description%20image/one_drawback_image.png)

- Two recommendations for further development.
One recommendation would be to be fixed the list of data type (date, city, state, country, shape, duration and comments). when user scroll down the data, it would be nicer to fix the table head so that user can easily see what this information about.

Second recommendation would be to add clear filter button. when user typed data on searching table, they might want to clear and re-search the whole new data. If it is provided, it would be easier to access data more accurate and understanable.
  
![recomm_image](https://github.com/msjj622/UFOs/blob/main/description%20image/recomm_image.png)

