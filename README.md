# MUSIC LISTENING STATISTICS ON ARTIST LY TRANG'S ALBUM
* Ly Trang is a young artist. She has been active on Sportify since 2018. She released an album on Sportify called "Snail Skeleton" and a live concert collab with two other artists.The genre music that Ly Trang is pursuing is experimental pop and art pop. The songs she creates always have a good effect on the listener, although she is a young artist, Ly Trang also has a certain community of listeners.
* So today I want to use the pandas library to analyze the statistics on Ly Trang's album (statistics are from the date 21/09/2021 to 18/10/2021 on Sportify)
# What is python pandas library?
*The pandas library in python is an open source library that effectively supports data manipulation. This is a powerful data processing and analysis toolkit of the python programming language. This library is widely used in both research and development of data science applications. This library uses a data structure called Dataframe.
# How to work with the gấu trúc library?
![Just a fun gif](https://media.giphy.com/media/PiQejEf31116URju4V/giphy.gif)

* Load the library:
```py

( import pandas as pd}
(import numpy as np}
```

* I load the database of Music listening statistics on artis LT'album:
```py
df = pd.read_csv("audience.tsv",sep = "\t")
```

* Then printed out the first record of the dataframe 
#And I used the "head".
```py
df.head()
```
*# Then I view the dataframe's size using the "shape":
```py
df.shape
```
*Then I view the dataframe's information using the "info":
```py
df.info()
```
*print all the columns' name:
```py
list(df.columns)
```
*print all indexing in the datafame:
```py
df.index
```
* print basic statistics on data:
```py
df.describe()
```


