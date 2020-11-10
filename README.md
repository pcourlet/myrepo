# myrepo
"This is a line from Rstudio"

library(ggplot2)
library(readr)


setwd("M:/PCL/COLLABORATEURS/PCOURLET/NONMEM/Amlodipine_validation_f")
inh25 <- read_delim("sim5.csv", ";", escape_double = FALSE, trim_ws = TRUE)
