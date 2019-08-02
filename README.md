# grubber
Grubber is a theme for Rstudio, in .rstheme format. It looks like this:  


![grubber_sample](https://raw.githubusercontent.com/robertmyles/grubber/master/grubber.png)


Download the .rstheme file and install it following the instructions [here](https://support.rstudio.com/hc/en-us/articles/115011846747-Using-RStudio-Themes), or alternatively, do this:

```r
# temp download folder
grubber <- fs::path_temp("grubber", ext = "rstheme")

# get theme
download.file("https://raw.githubusercontent.com/RobertMyles/grubber/master/Grubber.rstheme", 
              grubber)

# apply theme
rstudioapi::addTheme(grubber, apply = TRUE)
```
