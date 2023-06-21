# Data Science Jobscape: "What do we call 'data scientists'?"

The question, "What is a data scientist?", is impossible to answer before asking and answering inquiry, "What are data scientists called?".  

To begin to answer that latter question, here, I collected and manipulated country-wide data on 'data scientist' job listings from O*NET (https://www.onetonline.org/) using Pandas and NLTK to parse through and analyze job title trends.

## Part I: Most Frequently Used Titles for Data Scientists
The table below features the Top 15 most frequently used Job Titles for O*NET's keyword 'data scientist' in the U.S. as of 6/21/2023:

<p align="center">
  <img src="https://github.com/ethanwright96/data-science-jobscape/raw/main/top_15_titles.png" alt="top_15_titles" style="border: 1px solid black;">
</p>

## Part II: Keyword Frequency at the State Level
![ds_job_title_category_area_plot](https://github.com/ethanwright96/data-science-jobscape/raw/main/Figures/ds_job_title_category_area_plot.png)

After dropping 'data' and 'scientist' from the data frame:
![ds_job_title_category_area_plot](https://github.com/ethanwright96/data-science-jobscape/raw/main/Figures/no_ds_job_title_category_area_plot.png)

## Part III: Keyword Frequency at the Regional Level
![ds_job_title_category_area_plot](https://github.com/ethanwright96/data-science-jobscape/raw/main/Figures/regional_ds_job_title_category_area_plot.png)

After dropping 'data' and 'scientist':

![ds_job_title_category_area_plot](https://github.com/ethanwright96/data-science-jobscape/raw/main/Figures/regional_filtered_ds_job_title_category_area_plot.png)

## Discussion:

Please feel free to clone or fork this repository to jump-start your own job search or exploratory data analysis on job market trends!
