# Trends-in-Global-Video-Games-Market
- Project by: Haia Jihan
- Data source --> https://www.kaggle.com/datasets/thedevastator/discovering-hidden-trends-in-global-video-games
- Aim : discove trends in the video games market
- Tool --> Power BI

### Content ->
- The Final Project
- Process

## The Final Project
![image](https://github.com/hj18/Trends-in-Global-Video-Games-Market/assets/71445208/3b55afba-75e4-4ccd-ae67-56ba4e6788c7)
- A Summary page which shows the top 50 rated games and as can be seen that is Metroid Prime. It also shows the average critics score that we are dealing with, it shows the amount of game sold from 1983 until 2012 and how the making of games peaked in 2008. This could be because many games back in 2008 had sequals and many new IPs were made in 2008 which are still popular to this day such as Dead Space, Mirror's Edge and many sports games such as NBA 2K9.
- The visilisation showcases that even though many games were made in 2008 not many of them were well reviewed by critics as only four of them are on the top 50 best reviewed games from 1983 until 2012. These games includes the likes of Bioshock at 94.

![image](https://github.com/hj18/Trends-in-Global-Video-Games-Market/assets/71445208/e2c8245c-e86f-4de9-b962-b0ae849a068c)
- In the genre section I wanted to showcase which genres are the most popular amoung sales wise, which results in them being made the most such as can been seen with Sports and Action games. In 2006 Nintendo made most of sales just from Wii Sports which sold numbers in all the regions Europe, North America...etc

![image](https://github.com/hj18/Trends-in-Global-Video-Games-Market/assets/71445208/fd5804df-47a1-4714-832d-ce14e9d45151)
- In this slide I wanted to showcase the most popular games in each region and if the average critics rating effects it in anyways. This is not the case because from what we saw earlier, one of the most well reviwed games was Metroid Prime but Pokemon Gold/Silver is the most sold in Japan whereas everywhere else Wii Sports holds first place.


## Process
#### 1. Transform data
- First I change some columns types to `Fixed Decimal Number` especial if it is a sale number such as `North America` and `Europ` sales
- Then I created another query, named it `Game Genre` it is where I focus on the genre. I `split column by Delimiter` because some games might have more than one genre then used `Unpivoted Columns`.

![image](https://github.com/hj18/Trends-in-Global-Video-Games-Market/assets/71445208/332fe033-e189-4e19-92a6-ed30b19fc42b)

#### 2. Planning step
- It is a good idea to know how many game titles people are dealing with so first thing I did on the planning page was make a measure `Game Count = COUNT('Video Games Sales Main'[Game Title])` to count the titles and from the count, it showed us that there is 1,907 game titles in our data.

![image](https://github.com/hj18/Trends-in-Global-Video-Games-Market/assets/71445208/6fa62b2d-00b0-4a48-9d5e-db0565a85628)

- Started putting ideas toegther and see what works and what doesn't

- Then I started to plan out the genre page, I wanted to see the average score of each genre and the sale numbers to see if rating or how popular a genre is effects sales

