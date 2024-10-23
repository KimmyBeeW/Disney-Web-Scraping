Anyone else get the feeling that Marvel, and Disney in general, have gone downhill?
The writing has been subpar, it feels like their focusing on quantity over quality, and I've lost interest. It made me wonder how Marvel has been doing over the last few years in their revenue, and that led to a question about how Disney has been doing as a company. Spoiler alert... not great.

The first thing I looked at was an [IMDB post](https://www.boxofficemojo.com/brand/bn3732077058/) about box office revenue for marvel movies. (You can also view the scraped data in the [marvel_movies.csv](https://github.com/KimmyBeeW/marvel-movies-web-scraping/blob/main/marvel_movies.csv)) I've heard that Marvel hasn't been as good since Avengers: Endgame which came out in Apr 26, 2019, but according to the Opening Revenue, they've had a couple of good ones since then like "Spider-Man: No Way Home" (Dec 2021) and "Black Panther: Wakanda Forever" (Nov 2022), but I think the beginning of the end began with the nightmare that was rank 9 on their list: "Doctor Strange in the Multiverse of Madness" (May 2022). Obviously the MCU is not the only contributor to Disney stock fluctuations, but it is an indicator to me of the quality pushed by the company.
Another important date to note is the Disney+ launch in the US: November 12, 2019.

Next I checked out Disney stock prices on [Google Finance](https://www.google.com/finance/quote/DIS:NYSE?sa=X&ved=2ahUKEwjM1_narpiJAxU3EjQIHZL5BIwQ3ecFegQIQhAh&window=5Y) and [Yahoo! Finance](https://finance.yahoo.com/quote/DIS/) which were both scrapable, but I decided to use the historical data from [Yahoo](https://finance.yahoo.com/quote/DIS/history/?period1=1571423893&period2=1729276688) for the last 5 years (Oct 18, 2019-2024) and that scraped data can be found in the [disney_stocks.csv](https://github.com/KimmyBeeW/marvel-movies-web-scraping/blob/main/disney_stocks.csv) and for all the [stocks](https://finance.yahoo.com/quote/DIS/history/?period1=-252322200&period2=1729276688) since 1962 with the scraped data in [all_disney_stocks.csv](https://github.com/KimmyBeeW/marvel-movies-web-scraping/blob/main/all_disney_stocks.csv). [This video](https://youtu.be/7sFCOunKL_Y?si=ntvA0dtiJSIHrWOS) can help you get started if you want to try scraping stock data.

I wanted to see if it wasn't just Marvel so I explored all the brands owned by Disney listed on the [Box Office Mojo Website](https://www.boxofficemojo.com/brand/?ref_=bo_nb_gs_secondarytab):
    * [Marvel Comics](https://www.boxofficemojo.com/brand/bn3732077058/) – Disney acquired Marvel Entertainment in 2009.
    * [Lucasfilm](https://www.boxofficemojo.com/brand/bn4168284674/) – Disney purchased Lucasfilm in 2012.
    * [Pixar](https://www.boxofficemojo.com/brand/bn3530750466/) – Acquired by Disney in 2006.
    * [Walt Disney Animation Studios](https://www.boxofficemojo.com/brand/bn3295869442/) – This is a division of The Walt Disney Company.
    * [Blue Sky Studios](https://www.boxofficemojo.com/brand/bn3430087170/) – Disney acquired Blue Sky as part of the 2019 purchase of 21st Century Fox, but it was shut down in 2021.
    * [Disney Channel](https://www.boxofficemojo.com/brand/bn3446864386/) – Owned by Disney.
    * [DisneyToon Studios](https://www.boxofficemojo.com/brand/bn4185061890/) – A division of Disney, although it was closed in 2018.
    * [Disneynature](https://www.boxofficemojo.com/brand/bn3245537794/) – This is a film label of Walt Disney Studios.
So I combined all that data into an aggregate dataset and reset all the ranks to reflect the Gross Income again: [disney_owned_movies.csv](https://github.com/KimmyBeeW/marvel-movies-web-scraping/blob/main/disney_owned_movies.csv)

I'll do some Data Visualization soon, but enjoy looking at the data in the meantime!
