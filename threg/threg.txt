# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fit a threshold regression model (Models) Use threg With (In) R Software
install.packages("threg")
library("threg")
threg = read.csv("https://raw.githubusercontent.com/timbulwidodostp/threg/main/threg/threg.csv",sep = ";")
# Estimation Fit a threshold regression model (Models) Use threg With (In) R Software
threg <-threg (Surv(weeks, relapse) ~ f.treatment2|f.treatment2, data = threg)
threg
# Fit a threshold regression model (Models) Use threg With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished