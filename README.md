# Module 1 Final Project - State Of The Box Office
Yasir Karim and Amir Edris

Sources: Imdb, Box Offic Mojo, The Numbers & Kaggle.
## Introduction
Microsoft has set their intentions on venturing into the movie industry. They have decided to create their own movie studio. We are tasked with analyzing the state of the industry in order to guide Microsoft to take their first steps. We have relied heavily on our pre-existing knowledge of the industry and the box office in deciding which questions we would like explore. 
## Data Cleaning And Exploration
From the get go we wanted to explore data regarding a movies studio, genre, prodcution budget, revenue and date. We believe that these are vital information in analyzing the state of the box office. Out of the csv files that were provided to us, we used the files from Box Office Mojo and The Numbers, as they had the information that we needed. However, we needed more data to work with including but not limited to data regarding sales of Microsofts video games. From Kaggle, we found a csv file with video game sales information along with their genre, console, studio etc. For further box office information we used webscraping to get tables from IMDb and The numbers website.

For analysis and visualization on the csv files with Box Office Mojo and The Numbers website data:

`see: Data_Cleaning_Visualization_v1.ipynb`

For Webscraping from The Numbers website and the subsequent exploration and plots:

`see: Data_scraping_visualization_v2.ipynb`

For the Webscraping of Box office Movies and and joining it with extra data(also cleaning and visualization) :

`see: Adding Movie and Game data.ipynb`

### Queries
We wanted to answer the following questions through our exploration and analysis of the collected data.

```
1. Is the decision to produce and distribute films the right decision at this time?`
2. Has the global industry changed in any shape or form in this century?`
3. Is it benficial or harmful to use intellectual property owned by Microsoft as source material?
    a. What are Microsofts highest selling genre and title of video games?
4. What level of budget in a movie is more profitable and yields the highest return on investment?
5. Analyze the business of a popular movie studio based on our findings.
6. Is their a certain time of the year when it's more preferrable to release films?
```

### Visualizations
After completeing exploratory data analysis to answer our questions, we made graphs to help visualize our findings for the non-technical audience. We have related one or more plots to each question.

`Q1.`
![GitHub Logo](/Data_Visualizations_PNG/Yearly_Worldwide_Gross.png)

`Q2.`
![GitHub Logo](/Data_Visualizations_PNG/Global_Revenue_By_Decade.png) 

`Q3.`
![GitHub Logo](/Project_graphs/SumOfRevenueForTheGenres.png)
![GitHub Logo](/Project_graphs/BudgetCostBreakdownByGenre.png)
The Dataset Shown below is and example of some of the "safe" titles for each genre but because of the the way we got genre information there is a fair chance that some of these, when you look at context, are probably bad desicions.
![GitHub Logo](/Project_graphs/Top3MicrosoftOwnedIpsForEachMovieGenre.png)
![GitHub Logo](/Data_Visualizations_PNG/Ip_v_Original.png) 

`Q4.`
![GitHub Logo](/Data_Visualizations_PNG/ROI_Profit_By_Budget.png)
`Q5.`
![GitHub Logo](/Data_Visualizations_PNG/Blumhouse_Horror_Profits.png)
`Q6.`
![GitHub Logo](/Data_Visualizations_PNG/Monthly_revenues.png)

## Conclusion
### Recommendations

* Creating a new movie studio at this time is the right decision.
    * Global market has significantly changed in the past decade. Overseas revenue has increased by over 150%, which has garnered far greater profits for studios.
    * Microsoft also has enough assets to get their legs under them and be in a strong position from the start, especially in conjuction with the rest of our data         it seems like this would probably be a very safe desicion.
* Microsoft should rightfully use its existing gaming franchises to adapt them into feature films.
    * Movis based on comic books or video games yield far greater return than movies based on original screenplay.
    * Sequels dominate the top of box office charts yearly. Therefore, once we have succesfully launched our properties into movies, it is important to follow then up sequels. This is mirroring the same way microsoft makes sequels to their popular video games.
    * There is alot of safety in bringing popular games with stories that people already know and are willing to follow as this is just money saved in budgeting.
    * Use the highest selling games such as Halo and others that match genres that with films with the greatest profits.
* Invest in either big budget action or smaller horror films for optimal success.
    * higher budgets yield the greatest gross profit but smaller budgets have greater return on investment. Therefore, avoid making mid budget films.
* Release movies during the summer or holiday seasons.
    * Movies released in May, June, July, November and December result in far higher revenues than movies released during the rest of the year.
* A good business stratagey for them would probably be to go with the lower cost option based our avoidance of mid-range priced movies and look at the most successfull title they have that is a good fit (A halo horror game would be a good example) then used this low risk medium reward situation to collect data on expenses which can further be explored and used to figure out if investing at higher amounts is worth its weight or not cause if its not no harm done.
### Future Work
We can dive even deeper in terms of research to construct our perfect and profitable movie studio. We can look to answer the following questions:

* Strip our research on original films even further by removing seqeuls, remakes or reboots by considering them popular I.P.
* Analyze the many genres to reveal which of them have the highest return on investment.
* How much does the runtime of a movie affect its box office?
* Should microsoft create its own T.V division?
* Should we release our films on streaming services, if so, which genres are better suited for that platform?
* Is it profitable to buy rights for novel/play adaptations?
* How does budget allocation affect profit margins, can guide our spending with futher analysis.
