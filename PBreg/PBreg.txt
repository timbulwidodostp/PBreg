# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Passing-Bablok regression Use PBreg (MethComp) With (In) R Software
install.packages("MethComp")
library("MethComp")
# Estimate Passing-Bablok regression Use PBreg (MethComp) With (In) R Software
PBreg = read.csv("https://raw.githubusercontent.com/timbulwidodostp/PBreg/main/PBreg/PBreg.csv",sep = ";")
PBreg <- Meth(PBreg)
PBreg <- PBreg(PBreg)
par(mfrow = c(2, 2))
plot(PBreg, s = 1 : 4)
PBreg
# Passing-Bablok regression Use PBreg (MethComp) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished