## Part 1
### 1. Write a regex to extract all the numbers with orange color background from the below text in italics.
== I have used regular expressions to filter out the numbers.

### 2. identify ratings where review text is good, but rating is negativeso that the support team can point this to users.
==  Here we need to find the sentiment of the reviews individually and find out those reviews where sentiment is positive but the rating is poor. 
    I used SentimentIntensityAnalyzer and Roberta based pretrained model on twitter sentiment analysis which gives most appropriate results on
    languages\slangs used in real life. After finding out the sentiment score and comparing the models. I found roberta model performing good.
    So i used the positive sentiment score of roberta model which is greater than 0.5 with the condition where the given star rating was 1 or 2.
    This gives the misclassified reviews. I used Flask to deploy this model. Where Authentication is required and when an input csv file is uploaded,
    file is processed and output.csv is returned.Check the link.
    github link-
    deployed link-
   
### 3. Ranking Data
==  Here i have checked correlation between keyword and App id and how both affect the ranking parameter.
    Accordingly,the keywords are given more priority. APP ID has some correlation with the keyword in determining the rank and also Short description 
    have more correlation to ranking than long description.
   
## Part 2

### 1.Check if sentence is grammatically correct
==   used scoring method for checking grammar ranging 0-100 github link-

### 2.
==  V={(a,2a):for all real a (option 3)
    the endpoints lie on the line y=2a in x-y plane, Let's choose any two vectors from V,say u=(1,2),v=(-2,-4).
    u+v=(-1,-2) is also a vector because its second component is twice the first(cond closed under addition).
    3u=3(1,2)=(3,6) is also a vector ,every scalar multiple of any vector in v is itself an element of v(closed under scalar multiplication).
    
