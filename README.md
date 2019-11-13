# shiny-workshop
Workshop 3 of fall 2019 workshop series.  
Link to this page: http://bit.ly/R-workshop3

### For use with Lewis & Clark's RStudio Server

* Visit <a href='https://datasci.watzek.cloud' target='_blank'>https://datasci.watzek.cloud</a>
* Sign in with your Lewis & Clark username and password. If you haven't created an account yet, you'll be prompted to create a password.
* Once signed in, click "RStudio Server", after which you will need to sign in again (LC username / password you just created)

in console (lower left-hand corner):
* `library(usethis)`
* `use_course("https://github.com/jeremymcwilliams/shiny-workshop/archive/1.0.3.zip")`

After running the command above, you'll be prompted whether to download to your current directory. Go ahead and answer in the affirmative (you'll be presented with variations on "yes"). Once the course files download, you'll be prompted as to whether to delete the zip file. Again, answer in the affirmative. Once you do, click "Save", and your window will refresh to a new R session.


### For use with rstudio.cloud 

* Visit https://rstudio.cloud, and sign in with your google account  
* Click the arrow next to "New Project", and select "from Github Repository"
* Enter the url: https://github.com/jeremymcwilliams/ggplot-workshop
* Once the project loads, run `install.packages("tidyverse")` and `install.packages("shiny")` in the console.


#### To get started, click "shiny-worksheet.Rmd" in the files window, and then minimize the console window.
