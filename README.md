# sample-datasets

## Shape file of 67 provinces of Turkey

- File name and extension: turkey_admin1_merge3_all.zip

### Variables:

- growth: growth rate of per capita real income 1987-2001
- base: lograrithm of the per apita income in the base year 1987
- T: average terrorism index
- E: average years of schooling
- G: real per capita government expenditures in 1987
- Coastal: dummy variable  which takes the value of one if the province is a coastal province.

### Source:

- Öcal, N., & Yildirim, J. (2010). Regional effects of terrorism on economic growth in Turkey: A geographically weighted regression approach. Journal of Peace Research, 47(4), 477-489.

- [Matthew C. Ingram](http://mattingram.net/teaching/spatialanalysis/)

### Download Link:

## weighted-unconditional-beta-convergence

- Cole, M. A., & Neumayer, E. (2003). The pitfalls of convergence analysis: is the income gap really widening?. Applied Economics Letters, 10(6), 355-357.

df <- read_csv("https://raw.githubusercontent.com/ds777/sample-datasets/master/weighted-unconditional-beta-convergence.csv")

## simData

  From Magrini, S. (2007). [Analysing convergence through the distribution dynamics approach: why and how?](https://sites.google.com/a/unive.it/smagrini/home/matlab-code)

- The first series was obtained by drawing a random sample of 1000 observations from a univariate normal distribution
- The second series was instead produced by merging and appropriately sorting two random samples of 500 observations
  - These two samples, again drawn from a univariate normal distribution, differed in their means

## World Productivity Database 2017: Fernandez-Arias-2017-Database.csv

- Fernández-Arias, Eduardo, ed. 2017. Productivity Database 2017. Washington, DC: Inter-American Development Bank. Department of Research and Chief Economist. Distributed by Washington, DC: Inter-American Development Bank. Numbers for Development. <https://mydata.iadb.org/Economics/Productivity-Database-2017/n576-t3wa/about>

- This database provides measures of labor productivity (LP), capital and labor productivity (KLP) and Total Factor Productivity computed by Daude and Fernández-Arias (2010) for the 1960-2014 period, along with the inputs used to calculate them. This data spans 79 countries of them. <https://publications.iadb.org/handle/11319/8656?locale-attribute=en>

- Database description:  <https://github.com/ds777/sample-datasets/blob/master/Fernandez-Arias%202017%20-%20Database%20description.pdf>

- Download code for R:

Fernandez_Arias_2017_Database <- read_csv("https://raw.githubusercontent.com/ds777/sample-datasets/master/Fernandez-Arias-2017-Database.csv")

## World Income Database: ps2009.csv


### Download code for R

ps2009 <- read_csv("https://raw.githubusercontent.com/ds777/sample-datasets/master/ps2009.csv")

### Related files

- ps2009.csv
- ps2009.dta
- c3data.dta
- <https://www.stata-journal.com/article.html?article=st0503>

## Economic Growth Data (From David Weil Book, 2011)

- Source: <http://www.routledgetextbooks.com/textbooks/9780321795731/resources.php>

- For data definitions and sources see: WeilLabData2011FinalRevised-definitions-sources.txt

### Download code for R

weil <- read_csv("https://raw.githubusercontent.com/ds777/sample-datasets/master/WeilLabData2011FinalRevised.csv")

### Jamovi datafile available

## 10 Sector Database

### Dani Rodrik Version

Dataset from his famous paper

- McMillan, M. S., & Rodrik, D. (2011). Globalization, structural change and productivity growth (No. w17143). National Bureau of Economic Research.

Stata file names
- Rodrik-dataset-decomposition-1990-2005.dta
- Rodrik-industres-Employment-VA.dta
