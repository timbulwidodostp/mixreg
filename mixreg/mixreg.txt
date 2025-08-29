# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fit a mixture of linear regressions Use mixreg With (In) R Software
install.packages("remotes")
remotes::install_github("cran/mixreg")
library("mixreg")
mixreg = read.csv("https://raw.githubusercontent.com/timbulwidodostp/mixreg/main/mixreg/mixreg.csv",sep = ";")
# Estimation Fit a mixture of linear regressions Use mixreg With (In) R Software
mixreg <- mixreg(aphRel, plntsInf, ncomp = 2, seed = 42, data = mixreg)
mixreg$parmat
mixreg$theta
# Fit a mixture of linear regressions Use mixreg With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished