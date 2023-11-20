# Trends-in-Global-Video-Games-Market

- Data source --> https://www.kaggle.com/datasets/thedevastator/discovering-hidden-trends-in-global-video-games
- Aim : discove trends in the video games market

### Content ->
- The Final Project
- Process

## The Final Project
![image](https://github.com/hj18/Trends-in-Global-Video-Games-Market/assets/71445208/4b852873-3828-4cdc-a253-a0d5ba5c515e)
- A Summary page which shows the top 50 rated games and as can be seen that is Metroid Prime. It also shows the average critics score that we are dealing with, it shows the amount of game sold from 1983 until 2012 and how the making of games peaked in 2008. This could be because many games back in 2008 had sequals and many new IPs were made in 2008 which are still popular to this day such as Dead Space, Mirror's Edge and many sports games such as NBA 2K9.
- The visilisation showcases that even though many games were made in 2008 not many of them were well reviewed by critics as only four of them are on the top 50 best reviewed games from 1983 until 2012. These games includes the likes of Bioshock at 94. 


## Process
#### 1. Transform data
- First I change some columns types to `Fixed Decimal Number` especial if it is a sale number such as `North America` and `Europ` sales
- Then I created another query, named it `Game Genre` it is where I focus on the genre. I `split column by Delimiter` because some games might have more than one genre then used `Unpivoted Columns`.

![image](https://github.com/hj18/Trends-in-Global-Video-Games-Market/assets/71445208/2bebcd12-0394-4903-8693-036791649d89)

#### 2. Planning step
- It is a good idea to know how many game titles people are dealing with so first thing I did on the planning page was make a measure `Game Count = COUNT('Video Games Sales Main'[Game Title])` to count the titles and from the count, it showed us that there is 1,907 game titles in our data.

![image](https://github.com/hj18/Trends-in-Global-Video-Games-Market/assets/71445208/019a8ac0-f35e-4f7f-ab58-9d59e04165c3)
- Started putting ideas toegther and see what works and what doesn't

![image](https://github.com/hj18/Trends-in-Global-Video-Games-Market/assets/71445208/d2b669ea-3017-42ba-8ac0-d176ab916443)

- Then I started to plan out the genre page, I wanted to see the average score of each genre and the sale numbers to see if rating or how popular a genre is effects sales

![image](https://github.com/hj18/Trends-in-Global-Video-Games-Market/assets/71445208/9faa1518-6ebb-4545-af1d-5c954cd06bd2)

