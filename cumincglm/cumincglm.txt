# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Generalized linear models for cumulative incidence Use cumincglm (eventglm) With (In) R Software
install.packages("eventglm")
library("eventglm")
cumincglm = read.csv("https://raw.githubusercontent.com/timbulwidodostp/cumincglm/main/cumincglm/cumincglm.csv",sep = ";")
# Estimation Generalized linear models for cumulative incidence Use cumincglm (eventglm) With (In) R Software
cumincglm <- cumincglm(Surv(time, status) ~ rx, time = 2500, data = cumincglm)
summary(cumincglm)
# Generalized linear models for cumulative incidence Use cumincglm (eventglm) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished