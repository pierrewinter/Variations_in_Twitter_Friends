# Variations in Twitter Friends :baby_chick: :baby_chick:

The average number of friends that a person can maintain strong relationships with has been determined to be 150 or less (Dunbar's number). The size of friend groups may also vary among different countries and cultures. Can geographical differences in the number of friends be quantified using social media data?

### Project Overview

This is a personal project based on my interest in social data science and understanding how sociology impacts human relationships. I made use of open-source software such as R and rtweet to obtain public Twitter data and I performed data aggregation and visualization in RStudio. Twitter API access is required!

### Solution :thumbsup:

My solution was to obtain geogrpahical Twitter timeline data using the rtweet package and to quantify differences in the number of friends between Western and Central Europe. Once the data was cleaned and aggregated, I defined a method for counting the number of friends a Twitter user has and applied variable transformation to deal with the highly skewed data.

Because the data is heavily skewed, I performed a permutation test to compare the two European populations and it was found that they exhibit a statistically significant difference in their average number of friends.

### TO-DO List

This is an ongoing project and I expect to add more functionality soon. :hatching_chick:

- [ ] Update friends function to include sentiment analysis
- [ ] Include more countries/cities to draw data from
- [ ] Automate function parametrization based on data
