# MrOlympia DataAnalysis

[Versão em Português](README.md)

## Introduction
The MrOlympia-DataAnalysis project aims to perform web scraping from Wikipedia to gather data about the winners of Mr. Olympia in the Open Division category. From this data, we seek to extract interesting information and create visualizations that allow for a better understanding of patterns and trends over the years.

## Technologies Used
For the development of this project, we used the following technologies:

* **pandas**: for data manipulation and analysis.
* **requests**: to make HTTP requests and obtain the content of web pages.
* **BeautifulSoup4**: to parse HTML and extract relevant data.
* **matplotlib**: for creating graphs and visualizations.

## Project Structure
The project consists of four main parts:

1. **Scraping Data from Wikipedia**
In this part, we implemented all the web scraping logic to obtain data from the Wikipedia site about Mr. Olympia and its participants. The collected data is stored in lists.

2. **Create DataFrame**
After collecting the data, we stored this information in dataframes using the pandas library. This makes data manipulation and analysis easier.

3. **Get Data of Each Olympia**
In this section, we created specific dataframes for each edition of Mr. Olympia, including detailed information about the participants, such as weight and height.

4. **Display Data in Graphs**
We used matplotlib to create interactive graphs and visualizations that help understand the collected data. Some of the generated graphs include:

Some of the observed data:

![graph](images\data1.png "Participações Mr Olympia")
![graph](images\data2.png "Posições de Ronne Coleman")
![graph](images\data3.png "Distribuição de Vitórias")
![graph](images\data4.png "Dispersão de peso x altura")
![graph](images\data5.png "Tendência de crecimento de prêmio")
![graph](images\data6.png "Países sediaram evento")

## Conclusion
The MrOlympia-DataAnalysis project provided interesting insights into the winners and patterns of Mr. Olympia over the years. Some of the discoveries include the evolution of award values, the performance of notable competitors like Ronnie Coleman, and the distribution of events by country.

Possible extensions of the project may include the analysis of other Mr. Olympia categories, the inclusion of more recent data, and the creation of interactive visualizations using libraries like Plotly or Bokeh.