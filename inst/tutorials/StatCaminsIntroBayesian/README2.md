# StatCaminsIntroBayesian

StatCaminsIntroBayesian Package. Download and install it

# First steps to activate the tutorial

## Let's install the packages that we need. Installation is only done once. Package will be installed for next tutorials

install.packages("learnr")

install.packages("devtools")

## We activate the package (once per session if needed)
library("learnr")

library("devtools")

## Download the tutorial from the repository
## since 4..6.2, pak for Mac needs Xcode; for Windows it needs Rtools

pak::pak("MaribelOrtego/StatCaminsIntroBayesian")

## Execute the tutorial:
learnr::run_tutorial("StatCaminsIntroBayesian", "StatCaminsIntroBayesian")

### And now follow the tutorial. ( Always follow the Next Page buttons) 
