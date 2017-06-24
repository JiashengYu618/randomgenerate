# Shiny App randomgenerate supporting documentation

This documentation provides a general guide to use the shiny app [randomgenerate](https://cheyu.shinyapps.io/randomgenerate/).

## Where and How to Run the App
To run and use this app, one can consider the following different ways.

### Go to the website hosted by **shinyapps.io** of Rstudio
The website is [https://cheyu.shinyapps.io/randomgenerate/](https://www.tug.org/begin.html).

### Run the app locally using command `runApp()` 
If one has the code `ui.R` and `server.R` of the app locally with `shiny` package loaded, simply run the command `runApp(appDir)`, where `appDir` is a directory containing `server.R`, plus, either `ui.R` or a www directory that contains the file index.html.

### Run the app locally using command `runGithub()`
The app has been uploaded on Github at [https://github.com/chenghanyu/randomgenerate](https://github.com/chenghanyu/randomgenerate). One can run the shiny app by typing the command `runGithub("randomgenerate", "chenghanyu")` or `runGitHub("chenghanyu/randomgenerate")` in R.







































