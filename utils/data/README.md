| SN | Dataset                                                                                                       | #User      | #Item     | #Inteaction   | Sparsity | Interaction Type           |
| -- | ------------------------------------------------------------------------------------------------------------- | ---------- | --------- | ------------- | -------- | -------------------------- |
| 1  | [MovieLens](https://github.com/RUCAIBox/RecDatasets/tree/master/dataset_info/MovieLens)                       | \-         | \-        | \-            | \-       | Rating                     |
| 2  | Anime                                                                                                         | 73,515     | 11,200    | 7,813,737     | 99.05%   | Rating \[-1, 1-10\]        |
| 3  | Epinions                                                                                                      | 116,260    | 41,269    | 188,478       | 99.99%   | Rating \[1-5\]             |
| 4  | Yelp                                                                                                          | 1,968,703  | 209,393   | 8,021,122     | 99.99%   | Rating \[1-5\]             |
| 5  | Netflix                                                                                                       | 480,189    | 17,770    | 100,480,507   | 98.82%   | Rating \[1-5\]             |
| 6  | Book-crossing                                                                                                 | 105,284    | 340,557   | 1,149,780     | 99.99%   | Rating \[0-10\]            |
| 7  | Jester                                                                                                        | 73,421     | 101       | 4,136,360     | 44.22%   | Rating \[-10, 10\]         |
| 8  | Douban                                                                                                        | 738,701    | 28        | 2,125,056     | 89.73%   | Rating \[0,5\]             |
| 9  | Yahoo Music                                                                                                   | 1,948,882  | 98,211    | 11,557,943    | 99.99%   | Rating \[0, 100\]          |
| 10 | [KDD2010](https://github.com/RUCAIBox/RecommenderSystems-Datasets/tree/master/dataset_info/KDD2010)           | \-         | \-        | \-            | \-       | Rating                     |
| 11 | [Amazon](https://github.com/RUCAIBox/RecommenderSystems-Datasets/tree/master/dataset_info/Amazon)             | \-         | \-        | \-            | \-       | Rating                     |
| 12 | Pinterest                                                                                                     | 55,187     | 9,911     | 1,445,622     | 99.74%   | \-                         |
| 13 | [Gowalla](https://github.com/RUCAIBox/RecommenderSystems-Datasets/tree/master/dataset_info/Gowalla)           | 107,092    | 1,280,969 | 6,442,892     | 99.99%   | Check-in                   |
| 14 | LastFM                                                                                                        | 1,892      | 17,632    | 92,834        | 99.72%   | Click                      |
| 15 | [DIGINETICA](https://github.com/RUCAIBox/RecommenderSystems-Datasets/tree/master/dataset_info/DIGINETICA)     | 600,684    | 184,047   | 993,483       | 99.99%   | Click                      |
| 16 | [Steam](https://github.com/RUCAIBox/RecommenderSystems-Datasets/tree/master/dataset_info/Steam)               | 2,567,538  | 32,135    | 7,793,069     | 99.99%   | Buy                        |
| 17 | [Ta Feng](https://github.com/RUCAIBox/RecommenderSystems-Datasets/tree/master/dataset_info/TaFeng)            | 32,266     | 23,812    | 817,741       | 99.89%   | Click                      |
| 18 | [Foursquare](https://github.com/RUCAIBox/RecDatasets/tree/master/dataset_info/Foursquare)                     | \-         | \-        | \-            | \-       | Check-in                   |
| 19 | [Tmall](https://github.com/RUCAIBox/RecommenderSystems-Datasets/tree/master/dataset_info/Tmall)               | 963,923    | 2,353,207 | 44,528,127    | 99.99%   | Click/Buy                  |
| 20 | [YOOCHOOSE](https://github.com/RUCAIBox/RecommenderSystems-Datasets/tree/master/dataset_info/YOOCHOOSE)       | 9,249,729  | 52,739    | 34,154,697    | 99.99%   | Click/Buy                  |
| 21 | [iPinYou](https://github.com/RUCAIBox/RecDatasets/tree/master/dataset_info/iPinYou)                           | 12,931,430 | 131       | 15,367,312    | 99.09%   | View/Click                 |
| 22 | [Retailrocket](https://github.com/RUCAIBox/RecommenderSystems-Datasets/tree/master/dataset_info/Retailrocket) | 1,407,580  | 247,085   | 2,756,101     | 99.99%   | View/Addtocart/Transaction |
| 23 | [LFM-1b](https://github.com/RUCAIBox/RecommenderSystems-Datasets/tree/master/dataset_info/LFM-1b)             | 120,322    | 3,123,496 | 1,088,161,692 | 99.71%   | Click                      |
| 24 | Criteo                                                                                                        | \-         | \-        | 45,850,617    | \-       | Click                      |
| 25 | Avazu                                                                                                         | \-         | \-        | 40,428,967    | \-       | Click \[0, 1\]             |
| 26 | Phishing Websites                                                                                             | \-         | \-        | 11,055        | \-       |                            |
| 27 | Adult                                                                                                         | \-         | \-        | 32,561        | \-       | income>=50k \[0, 1\]       |
| 28 | MIND                                                                                                          | \-         | \-        | \-            | \-       | Click                      |


A brief introduction of these datasets is as follows:
### Shopping
- Amazon: This dataset contains product reviews and metadata from Amazon, including 142.8 million reviews spanning May 1996 - July 2014. This dataset includes rating data (ratings), product metadata (descriptions, category information, price, brand, and image features), and links (also viewed/also bought graphs).
- Epinions: This dataset was collected from Epinions.com, a popular online consumer review website.
- Yelp :This dataset was collected from Yelp.com. The Yelp dataset is a subset of the businesses, reviews, and user data for use in personal, educational, and academic purposes.
- Tmall : This dataset is provided by Ant Financial Services, used in the IJCAI16 contest.
- DIGINETICA : The dataset includes user sessions extracted from an e-commerce search engine logs, with anonymized user IDs, hashed queries, hashed query terms, hashed product descriptions and meta-data, log-scaled prices, clicks, and purchases.
- YOOCHOOSE : This dataset has been constructed by YOOCHOOSE GmbH to support participants in the RecSys Challenge 2015.
- Retailrocket: The data has been collected from a real-world ecommerce website. It is raw data, i.e. without any content preprocessing, however, all values are hashed due to confidential issues.
- Ta Feng: The dataset contains a Chinese grocery store transaction data from November 2000 to February 2001.

### Advertisng
- Criteo: This dataset was collected from Criteo, which consists of a portion of Criteo's traffic over a period of several days.
- Avazu: This dataset is used in Avazu CTR prediction contest.
- iPinYou: This dataset was provided by iPinYou, which contains all training datasets and leaderboard testing datasets of the three seasons iPinYou Global RTB (Real-Time Bidding) Bidding Algorithm Competition.

### Check-in
- Foursquare: This dataset contains check-ins in NYC and Tokyo collected for about 10 months. Each check-in is associated with its time stamp, its GPS coordinates and its semantic meaning.
- Gowalla: This dataset is from a location-based social networking website where users share their locations by checking-in, and contains a total of 6,442,890 check-ins of these users over the period of Feb. 2009 - Oct. 2010.

### Movies
- MovieLens: GroupLens Research has collected and made available rating datasets from their movie web site.
- Netflix: This is the official data set used in the Netflix Prize competition.
- Douban: Douban Movie is a Chinese website that allows Internet users to share their comments and viewpoints about movies. This dataset contains more than 2 million short comments of 28 movies in Douban Movie website.

### Music
- Last.FM: This dataset contains social networking, tagging, and music artist listening information from a set of 2K users from Last.fm online music system.
- LFM-1b: This dataset contains more than one billion music listening events created by more than 120,000 users of Last.fm. Each listening event is characterized by artist, album, and track name, and includes a timestamp.
- Yahoo Music: This dataset represents a snapshot of the Yahoo! Music community's preferences for various musical artists.

### Books
- Book-Crossing: This dataset was collected by Cai-Nicolas Ziegler in a 4-week crawl (August / September 2004) from the Book-Crossing community with kind permission from Ron Hornbaker, CTO of Humankind Systems. Contains 278,858 users (anonymized but with demographic information) providing 1,149,780 ratings (explicit / implicit) about 271,379 books.

### Games
- Steam: This dataset is reviews and game information from Steam, which contains 7,793,069 reviews, 2,567,538 users, and 32,135 games. In addition to the review text, the data also includes the users' play hours in each review.

### Anime
- Anime: This dataset contains information on user preference data from myanimelist.net. Each user is able to add anime to their completed list and give it a rating and this data set is a compilation of those ratings.

### Pictures
- Pinterest: This dataset is originally constructed by paper Learning image and user features for recommendations in social networks for evaluating content-based image recommendation, and processed by paper Neural Collaborative Filtering.

### Jokes
- Jester: This dataset contains anonymous ratings of jokes by users of the Jester Joke Recommender System.

### Exercises
- KDD2010: This dataset was released in KDD Cup 2010 Educational Data Mining Challenge, which contains the situations of students submitting exercises on the systems.

### Websites
- Phishing Websites: This dataset contains 30 features of 11,055 websites and labels of whether they are phishing websites or not. The websites' features include 12 address-bar based features, 6 abnormal based features, 5 HTML-and-JavaScript based features and 7 domain based features.

### Adult
- Adult: This dataset is extracted by Barry Becker from the 1994 Census database, which consists of a list of people's attributes and whether they make over 50k a year.

### News
- MIND: This dataset is a large-scale dataset for news recommendation research. It was collected from anonymized behavior logs of Microsoft News website. MIND contains about 160k English news articles and more than 15 million impression logs generated by 1 million users.

## Data Sources
- [Google Drive](https://drive.google.com/drive/folders/1so0lckI6N6_niVEYaBu-LIcpOdZf99kj?usp=sharing)
- [Baidu Wangpan](https://pan.baidu.com/s/1p51sWMgVFbAaHQmL4aD_-g) (Password: e272)

## Credits
- [RecBole](https://recbole.io/index.html)

## Appendix
- [Table format - Google Sheet](https://docs.google.com/spreadsheets/d/1iufwr6Zkayu0SUoG78tVQ412oeluil958KakWAjI4gs/edit?usp=sharing)
