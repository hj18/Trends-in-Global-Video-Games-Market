# Trends-in-Global-Video-Games-Market

- Data source --> https://www.kaggle.com/datasets/thedevastator/discovering-hidden-trends-in-global-video-games
- Aim : discove trends in the video games market

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

![image](https://github.com/hj18/Trends-in-Global-Video-Games-Market/assets/71445208/1a853a44-dc42-4aab-8a23-1c0e3b5f2d9a)
