installer <- function(vector) {
  for(i in vector) {
    if(!require(i, character.only = T)) install.packages(i)
    library(i, character.only = T)
  }
}

# Demo
installer(c("tidyverse", "readxl", "writexl"))
