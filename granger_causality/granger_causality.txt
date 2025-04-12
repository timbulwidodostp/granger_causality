# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Granger causality test (multivariate) Use granger_causality (bruceR) With (In) R Software
install.packages("bruceR")
install.packages("vars")
library("bruceR")
library("vars")
granger_causality = read.csv("https://raw.githubusercontent.com/timbulwidodostp/granger_causality/main/granger_causality/granger_causality.csv",sep = ";")
# Estimation Granger causality test (multivariate) Use granger_causality (bruceR) With (In) R Software
VARselect(granger_causality)
granger_causality = VAR(granger_causality, p=3)
model_summary(granger_causality)
granger_causality(granger_causality)
# Granger causality test (multivariate) Use granger_causality (bruceR) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished