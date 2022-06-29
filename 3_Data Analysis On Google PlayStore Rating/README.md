# <p align = 'center'> Data Analysis on Google PlayStore Dataset </p>

While many public datasets (on Kaggle and the like) provide Apple App Store data, there are not many counterpart datasets available for Google Play Store apps anywhere on the web. On digging deeper, I found out that iTunes App Store page deploys a nicely indexed appendix-like structure to allow for simple and easy web scraping. On the other hand, Google Play Store uses sophisticated modern-day techniques (like dynamic page load) using JQuery making scraping more challenging.

In this Notebook, we cleaned the dataset by implementing `Data Pre-processing` and `Analyzed` in order to gain insights from it.

The dataset is collected from kaggle: <a href = "https://www.kaggle.com/lava18/google-play-store-apps">Link</a>

## Dataset Description -

1. App - Application name
2. Category - Category the app belongs to
3. Rating Overall - user rating of the app (as when scraped)
4. Reviews - Number of user reviews for the app (as when scraped)
5. Size - Size of the app (as when scraped)
6. Installs - Number of user downloads/installs for the app (as when scraped)
7. Type - Paid or Free
8. Price - Price of the app (as when scraped)
9. Content Rating - Age group the app is targeted at Children / Mature 21+ / Adult
10. Genres - An app can belong to multiple genres (apart from its main category). For eg, a musical family game will belong to Music, Game, Family genres.
11. Last Updated - Date when the app was last updated on Play Store (as when scraped) Current version of the app available on Play Store (as when scraped)
12. Current Ver - Current Android Version
13. Android Ver - Min required Android version (as when scraped)

## The main tasks performed in this jupyter notebook are -

1. Data Analysis
2. Data Cleaning
3. Data Pre-processing
4. Data Visualisation

## Methodologies -

We will perform the following steps for Data Cleaning and Data Preparation -
1. Deal with missing values and ‘Varies with device’ data.
2. Removing characters from Installs and make it numeric.
3. Remove ‘M’(megabyte) from the size and make it numeric.
4. Remove ‘k’(kilobyte) from size, make it numeric then divide it by 1000.
5. Transform reviews to numeric.
6. Remove currency symbol from Price, change it to numeric
7. Convert ‘Last Updated’ date to date format
8. Round current version number to 1 decimal
