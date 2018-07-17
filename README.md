# sample-datasets

## simData

  From Magrini, S. (2007). [Analysing convergence through the distribution dynamics approach: why and how?](https://sites.google.com/a/unive.it/smagrini/home/matlab-code)

- The first series was obtained by drawing a random sample of 1000 observations from a univariate normal distribution
- The second series was instead produced by merging and appropriately sorting two random samples of 500 observations
  - These two samples, again drawn from a univariate normal distribution, differed in their means

## World Productivity Database 2017: Productivity_Database_2017.csv

- Fernández-Arias, Eduardo, ed. 2017. Productivity Database 2017. Washington, DC: Inter-American Development Bank. Department of Research and Chief Economist. Distributed by Washington, DC: Inter-American Development Bank. Numbers for Development. <https://mydata.iadb.org/Economics/Productivity-Database-2017/n576-t3wa/about>

- This database provides measures of labor productivity (LP), capital and labor productivity (KLP) and Total Factor Productivity computed by Daude and Fernández-Arias (2010) for the 1960-2014 period, along with the inputs used to calculate them. This data spans 79 countries of them. <https://publications.iadb.org/handle/11319/8656?locale-attribute=en>

- Database description:  <https://github.com/ds777/sample-datasets/blob/master/Fernandez-Arias%202017%20-%20Database%20description.pdf>

- Download code:

  Productivity_Database_2017 <- read_csv("https://raw.githubusercontent.com/ds777/sample-datasets/master/Productivity_Database_2017.csv")

## World Income Database: ps2009.csv


### Download code

ps2009 <- read_csv("https://raw.githubusercontent.com/ds777/sample-datasets/master/ps2009.csv")

### Related files

- ps2009.csv
- ps2009.dta
- c3data.dta
- <https://www.stata-journal.com/article.html?article=st0503>
