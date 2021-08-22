I made a big mistake in the preprocessing phase.
I deleted the rows containing missing data before dropping the age_60 column which contained most of said missing data.
This resulted in losing more than half the data entries in the set.
But honestly, I was pressed for time and didn't have the time to restart when I realised my mistake.
Also, 136000 entries is still a pretty good number, and I thought it was enough to train our model pretty good.
I got pretty good performance at the end, at least with logistic regression, but the results were pretty satisfying so it wasn't that big a deal.
