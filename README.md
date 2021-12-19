# Hollywood Theatrical Market Analysis

This project focuses on **data visualization** on Hollywood Theatrical Market Synopsis (from 1995 to 2021).[^1]
The analysis involved study on Hollywood movie distributors, genres, ratings, gross, ticket sales, and inflation (dramatic change discovered during the peak of Covid19 Outbreak). 
The process involved in this project includes: 

1. Data cleanup with **Python**, **Pandas** on [this Jupyter notebook.][dataviz]
2. Data visualization using **Tableau**. ( For more interactive viewing, visit my dashboard for this visualization [here](https://public.tableau.com/app/profile/fateha.rozy/viz/WIP_movieGross/bar-distr-movie-gross) )

[^1]: Datasets retrieved from: https://www.kaggle.com/johnharshith/hollywood-theatrical-market-synopsis-1995-to-2021

---

## Data visualization findings:

### 💡 Top Hollywood Distributors ranked based on Total Grossings earned and number of movies released.
> ![](/images/bar-distr-movie-gross.png)
- Warner Bros. releases the most movies over the years but ranked 2<sup>nd</sup> in terms of total grossings.
- Disney accumulates the highest grossing and releases 588 movies in total (236 less compared to Warner Bros.)
- Among the top 10 distributors, only Dreamworks releases under 100 movies in total, but still manage to surpass Miramax (385 movies) in Total Grossings. 
- Insight: Number of movies released doesn't exactly affect the total grossings, this could be due to audience preference of quality over quantity.

### 💡 Disney is leading in market share in Hollywood theatricals.
> ![](/images/tree-distr-share.png)

### 💡 Covid19 effect on movie sales and inflation.
> ![](/images/dual-inflation.png)
- A dramatic drop starting from 2019 (deflation), and a slight rise in 2021.
- Disney movies had continuously achieved the highest sales for 8 consecutive years (2012 to 2019).
- After 12 years, a movie by Sony Pictures finally received the highest sales in year 2020 (Only to have Disney continue its lead in the following year).
- Insight: Disney leading movies are mostly from the Marvel Cinematic Universe and Star Wars franchise. These movies are known to have developed devoted fans throughout its movie series.

### 💡 Almost half of the total gross earnings is contributed by movies with PG-13 ratings.
> ![](/images/pie-mpaa-gross.png)

### 💡 Top 10 frequent genres in Hollywood Theatricals and its gross earnings.
> ![](/images/dual-genre-gross.png)
- Interestingly, Documentary comes in 3<sup>rd</sup> most released genres despite its low earnings compared to other genres.
- Adventure movies accumulates the highest grossing eventhough there is almost 5 times more Drama movies released in the market over the years.
- Insight: The high number of releases in genres such as Drama, Comedy, and Documentary, could be influenced by its lower budget needs (less dependency on CGI effects and stunts).

### 💡 Visit [my dashboard][dataviz] to interact with this data viz filter.
> ![](/images/heat-gross.png)


📌 Note from Author: Data findings can be visualized more coherently with Tableau. Given the right tools, even limited sets of data can produce valuable insights.

[dataviz]:https://github.com/FatehaRozy/hollywood-market-analysis/blob/main/datasets-cleaned/hollywood_data_cleaning.ipynb
