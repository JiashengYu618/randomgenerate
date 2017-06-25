# Shiny App randomgenerate supporting documentation

This documentation provides a general guide to use the shiny app [randomgenerate](https://cheyu.shinyapps.io/randomgenerate/).

## Where and How to Run the App
To run and use this app, one can consider the following different ways.

### Go to the website hosted by **shinyapps.io** of Rstudio
The website is [https://cheyu.shinyapps.io/randomgenerate/](https://cheyu.shinyapps.io/randomgenerate/).

### Run the app locally using command `runApp()` 
If one has the code `ui.R` and `server.R` of the app locally with `shiny` package loaded, simply run the command `runApp(appDir)`, where `appDir` is a directory containing `server.R`, plus, either `ui.R` or a www directory that contains the file index.html.

### Run the app locally using command `runGitHub()`
The app has been uploaded on Github at [https://github.com/chenghanyu/randomgenerate](https://github.com/chenghanyu/randomgenerate). One can run the shiny app by typing the command `runGitHub("randomgenerate", "chenghanyu")` or `runGitHub("chenghanyu/randomgenerate")` in R.



## Description and Example of Using the App
### Description
This app generates random draws from normal, binomial, or gamma distribution. Users can specify parameters of each distribution and the number of simulation draws. After specifying all the input values, including the number of bins, one can press the submit button and a corresponding historgram of color navy is shown. There is a checkbox to include a estimated dencity curve or not. 

### Example
Take a normal distribution for example. The default value of parameters are mean 0 and variance 1, i.e., standard normal. One can use the slider bars on the left to select any mean value between -1000 and 1000 with increment 0.1, and the standard deviation between 0 and 1000 with increment 0.1. The default number of draws is 1000 and increment 50. The number of bins can be from 5 to 150 with default value 30. After all inputs are set, simply press the Submit button at the end of the left panel, we would have a histogram for normal distribution and its empirical mean and standard deviation in the right panel, which can be used to verify the theoretical mean and standard deviation we specify in the left panel. For instance, given the mean 134 and standard deviation 10 and 10000 draws, the empirical mean and standard deviation are 133.7896 and 9.9402, respectively.

*Note: After choosng the distribution, one has to press Sumbit first in order to specify the corresponding distribution parameters.*






































