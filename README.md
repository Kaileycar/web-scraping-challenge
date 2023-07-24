# Web Scraping Challenge

In this project, you will be doing two parts. **Part 1** is scraping the titles and  
preview text from [Mars News Site](https://static.bc-edx.com/data/web/mars_news/index.html).    
**Part 2** is to scrap and analyze the table in [Mars Weather Data](https://static.bc-edx.com/data/web/mars_facts/temperature.html).  

---

## About

In this Challenge, you will be using your web-scraping skills to identify HTML elements, such as  
`id` and `class` attributes. Using **Splinter**(to extract information with automated browsing)  
and **Beautiful Soup**(to parse the HTML), you will be scraping titles and previews and extracting  
tables from websites.  

### Part 1: Scrape Titles and Preview Text from Mars News

Create a `Beautiful Soup` object to extract text elements from the *Mars News Site*. Inspect the  
page to identify which elements to scrape. Extract the `title` and `preview text` from the website  
and store each dictionary in a python list. Each dictionary should have two keys. The first, `title`,  
and the second, `preview`. 

Here's an example of what it should look like...  

<img width="908" alt="Screenshot 2023-07-24 at 12 07 26 PM" src="https://github.com/Kaileycar/web-scraping-challenge/assets/130424499/5be05db8-35a2-49e6-acea-f1e3da17dce1">  

### Part 2: Scrape and Analyze Mars Weather Data

Create a `Beautiful Soup` object to extract data from the table in the *Mars Weather Data* site. Inspect  
the page to identify which elements to scrape. Create a Pandas Dataframe from the scraped data. Make  
the columns the same as the table's columns (`id`, `terrestrial_date`, `sol`, `ls`, `month`,  
`min_temp`, and `pressure`). Analyze the data from the dataframe and answer the following questions...  

  * Which month, on average, has the lowest temperature? The highest?  
  * Which month, on average, has the lowest atmospheric pressure? The highest?
  * How many terrestrial days exist in a Martian year? A visual estimate within 25% was made.

---

## Getting Started

1. Download [Starter_Code_v1.2.2.zip](https://github.com/Kaileycar/web-scraping-challenge/files/12148432/Starter_Code_v1.2.2.zip)
2. Create a repo in your git respository
3. Clone the repo to your computer
4. In your Jupyter Notebook, use [Mars News Site](https://static.bc-edx.com/data/web/mars_news/index.html) for Part 1 and
   [Mars Weather Data](https://static.bc-edx.com/data/web/mars_facts/temperature.html) for Part 2.
5. Push all changes to your local repository.

---

## Usage
### Part 2

After creating your Pandas Dataframe, convert the datatypes to the necessary columns, they should be  
`datetime`, `int`, or `float`. Once you examine the data, answer the following questions...  

1. How many months exist on Mars?  
   
2.  How many Martian (and not Earth) days worth of data exist in the scraped dataset?  

3.  What are the coldest and the warmest months on Mars (at the location of Curiosity)?  
     * Find the average minimum daily temperature for all of the months.
     * Plot the results as a bar chart.
       
<img width="589" alt="Screenshot 2023-07-24 at 12 36 02 PM" src="https://github.com/Kaileycar/web-scraping-challenge/assets/130424499/073f6a52-47ab-4e47-a001-a8f591e43129">  

4. Which months have the lowest and the highest atmospheric pressure on Mars?
     * Find the average daily atmospheric pressure of all the months.
     * Plot the results as a bar chart.
       
<img width="580" alt="Screenshot 2023-07-24 at 12 37 53 PM" src="https://github.com/Kaileycar/web-scraping-challenge/assets/130424499/fe133afe-99bb-4986-9d64-0ebd5ae4885a">  

5. About how many terrestrial (Earth) days exist in a Martian year?
     * Consider how many days elapse on Earth in the time that Mars circles the Sun once.
     * Visually estimate the result by plotting the daily minimum temperature.
       
<img width="594" alt="Screenshot 2023-07-24 at 12 39 19 PM" src="https://github.com/Kaileycar/web-scraping-challenge/assets/130424499/51e4dd3b-ea69-46b1-ab90-4e2638283fa7">  

**Make sure to export you Dataframe as a CSV file**  

---

## Links

[Sort_Index](https://stackoverflow.com/questions/43855474/changing-sort-in-value-counts)  
[Sort Values](https://www.geeksforgeeks.org/seaborn-sort-bars-in-barplot/#)  
[Datetime](https://docs.python.org/3/library/datetime.html)  
