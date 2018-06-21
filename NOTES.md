Several non-programming stuffs. Taken from Learn R in Y Minutes.

```R
data() # browse preloaded datasets

data(rivers) # get rivers dataset

ls()  # list variables in workspace

head(rivers) # similar to `head` command in Linux
tail(rivers) # similar to `tail` command in Linux

length(rivers)

summary(rivers)

# make a stem-and-leaf plot (terminal version of histogram)
stem(rivers)

# the usual histogram
hist(rivers)
hist(rivers, col="#333333", border="white", breaks=25)
hist(log(rivers), col="#333333", border="white", breaks=25)

data(discoveries)
sort(discoveries)
```


