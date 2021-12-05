Wide Receiver Fantasy Football Output

Motivation
I am very big into fantasy football and I enjoy looking into it. I knew this project was going to take a lot of time and be a lot of work so I figured I should make it as enjoyable as possible. But the even bigger reasoning for wanting to use fantasy football as my project topic was so that I could understand the topic on a deeper level, which would provide me an advantage in my own fantasy football leagues. One thing that I hope to one day do is have a side gig being a fantasy football analyst and uncovering analytical advantages and findings through projects like this could go a long ways.

Data Sources
I scraped data from ProFootballReference.com which has all major information and statistics for every player that has ever played a snap in the National Football League. I also used FFToday.com to scrape every wide receiver's fantasy finishes and points per seaaon which has all fantasy data on each player going back to 2001. 

Processing Steps
There were major complications with processing data for this project. The main reason was that scraping and extracting this data wasnt quite as simple because the sites do not have all of the wide receivers on one page, rather each receiver has their own page that needs to be extracted and when I am extracting from nearly 500 receivers it can be quite time consuming. Which I then had to put all of the different statsitics from the two sites into one, easy to see dataframe. When extarcting data it was important to remove as much bias as possible, and mainly selection bias. To do this and get the least bias results, I used every single wide receiver that has been drafted from 2006-2020 in order to create a large enough sample to trust the analysis results while also not eliminating any receiver/data point for any reason.

Visualization
As I processed the data the biggest question I started to wonder was how much a wide receiver's drafted round, the round that the wide receiver was selected in when entering the NFL, mattered when it came to their fantasy output. So what I wanted to do was create graphs that showed just how important a draft round could be. The first graph I created was the most general. It was to see what percentage of receivers from each round achieve a top twelve fantasy season. (I will get into the results more in the analysis section)

<img width="360" alt="Screen Shot 2021-12-04 at 7 28 25 PM" src="https://user-images.githubusercontent.com/91634689/144734268-1cc7810c-df92-4ddf-aa3d-179a1160f569.png">

The next three graphs I created were to caputure how each round preforms using their actual average fantasy points score by their first three seasons (sepreately) in the NFL.

<img width="359" alt="Screen Shot 2021-12-04 at 7 28 31 PM" src="https://user-images.githubusercontent.com/91634689/144734348-2cb381af-e377-4c4a-bda7-2704c900c5ec.png">
<img width="360" alt="Screen Shot 2021-12-04 at 7 28 34 PM" src="https://user-images.githubusercontent.com/91634689/144734357-d32c54f4-7553-4d09-bf7c-df4bb81f353d.png">
<img width="359" alt="Screen Shot 2021-12-04 at 7 28 36 PM" src="https://user-images.githubusercontent.com/91634689/144734359-4c09d351-9373-4602-b84c-f6550fab215e.png">

Analysis
My goal was trying to find if a wide receiver getting drafted in a certain round can tell us, or give us a better clue as to how successful that wide receiver is likely to be. The results were far less surprsing than even I was expecting. Wide receivers that are drafted in the first round are far more likely to achieve a top twelve fantasy season and own the highest average fantasy points in each of their first three seasons. It was also not very surprising to see that the second and third rounders followed suite. But when it came to the fourth, fifth, sixth, and seventh rounders they were far more scattered and there was no clear evidence that one of those last rounds is superior to the other. Which speaking logically makes a large amount of sense. As the draft gets deeper it is likely harder for NFL executives to judge talent, especially as the data has showed, that the better talent is already off the board in the first few rounds.

References
“Pro Football Statistics and History.” Pro, https://www.pro-football-reference.com/. 
Wide Receiver Stats: 2020 Regular Season - FF Today, https://fftoday.com/stats/playerstats.php?Season=2020&amp;GameWeek=&amp;PosID=30&amp;LeagueID=107644&amp;order_by=FFPtsPerG&amp;sort_order=DESC&amp;cur_page=0. 

