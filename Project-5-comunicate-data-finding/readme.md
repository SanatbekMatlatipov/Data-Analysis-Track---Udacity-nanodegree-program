# PISA 2012 dataset
## by Sanatbek Matlatipov


## Dataset

> PISA is a survey of students' skills and knowledge as they approach the end of compulsory education. It seems that PISA 2012 survey is about how well student is prepared for life beyond school rather than just how well student have observed school lessons. Around 510,000 students in [65 economies](https://www.oecd.org/pisa/pisaproducts/PISA%202012%20framework%20e-book_final.pdf) took part in the PISA 2012 assessment of reading, mathematics and science representing about 28 million 15-year-olds globally. 

**PISA 2012 DATA**
1. (pisa2012-download)[https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisa2012.csv.zip&sa=D&ust=1554482573645000#:~:text=https%3A//s3.amazonaws.com/udacity-hosted-downloads/ud507/pisa2012.csv.zip] dataset has been explored. The Database has **636 columns** and **485490 rows**. 

2. To undestand the structure and investigation of topics in the dataset use (this dictionary)[https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisadict2012.csv&sa=D&ust=1554482573645000]

## Summary of Findings

> Student directly related info: When I count the most frequent countries, Mexico, Italy and Spain were top 3 countries who has most students. Whole dataset have equal gender distribution. When I compared I found that girls do reading slightly more than males. However, boys mathematics is better than girls. I also found that distribution of three scores are normally distributed. The peak for all academics between 420 and 460. Student's parent's realted info: More fathers' have full-time job than mothers. It seems mothers have more home duties than fathers. Unemployment rate is low for both of the genders which is very good. The highest proportion for both gender corresponds to International Standard Classification of Education of level 3A which is upper secondary education. most of students are from country where PISA test happened(93% vs 7%). However, I explored that for both father and mother who came as immigrant slightly higher than their children(85% and 15% approx.). I have filled mising values with corresponding values, if it was Yes/No and NaN, I decided to change NaN value to Yes. I also take average values of PVMAT(1-5), PVREAD(1-5), and PVSCIENCE(1-5) columns. I also made some merging columns by taking most_frequent_one s.

