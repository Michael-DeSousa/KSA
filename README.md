# Kickstarter Analytics

![kickstarter analytics_home](https://user-images.githubusercontent.com/22509729/119893722-8fdd3700-bef0-11eb-9428-8ff286449e06.png)
![kickstarter_anayltics_example](https://user-images.githubusercontent.com/22509729/119899662-42fd5e80-bef8-11eb-9585-2906220d6fc9.png)


## Demo
[Link](https://www.youtube.com/watch?v=sDqwZvFt7VE)

## Project Overview
Kickstarter Analytics is an analytics website created by Jason Chang, Vivian Le, Michael De Sousa, and Neha Gupta in the winter of 2020. 

The purpose of the website is to parse a given CSV file of Kickstarter Projects and create interesting analytics based on that data. For this project, we used the dataset found [here](https://www.kaggle.com/kemical/kickstarter-projects) which contains data on nearly 400,000 Kickstarter Projects. 

Kickstarter Analytics supports the following features:
- You can use the search bar to search for projects by their Name, Category, Country of Origin, # of Backers, Currency Type, or ID. Partial searching is supported when searching for projects by name.
- You can add or delete projects from the dataset at any time. All future searches and analytics will reflect these changes to the dataset.
- You can update the properties of projects in the dataset at any time. All future searches and analytics will reflect these changes to the dataset.
- You can save your changes to the dataset using the "Backup Data" button in the top right of screen. This will export a new CSV file with your changes.
- You can browse 7 analytics based on the dataset:
   - By Country: A breakdown of all projects by which country they originated from
   - By Category: A breakdown of all Kickstarter categories and how many projects they hve
   - By Start/End Date: A comparison of how many projects are launched and ended in each month
   - Project Success Percentage: Displays the overall success rate of all projects in the dataset
   - Most Successful Category: A breakdown of all Kickstarter categories, organized by the most successful category to the least successful
   - Failed Takeoffs: A breakdown of all Kickstarter Projects that had 0 backers
   - Funding v.s. Success Rate: A comparison of project success rates based on their funding goals
   
   *Note: You can move your mouse over all pie slices, bars, data points, etc. for specific numbers and other information. This was not shown in the demo video.*

## Technologies Used

Front End:
- HTML
- CSS + [Bootstrap](https://getbootstrap.com/)
- Javascript + [ChartJS](https://www.chartjs.org/)

Back End:
- Python  + [Flask](https://flask.palletsprojects.com/en/2.0.x/)

Note: For this class project we were not allowed to use databases or parsing libraries. This means we had to write the parsing code from scratch and store data in simple data structures.  
