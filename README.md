# R_code-
for R studio 
we are facing problem in cummit.
After so many attempt finally integrated github with R studio 
my powerbi community myself23063375
Imprtant Commandss
(1)-Read perticular format file from Directory(but set correct directory first)

# files<- list.files(pattern ="*.csv")
# myfiles<- do.call(rbind, lapply(files, function(x) read.csv(x, stringsAsFactors =                                                                 FALSE)))
(2)-TRUE/FALSE outcome in R

# TRUE & FALSE =  1 & 0 = Value will be multiply [ 1*0 =0] - False 
# TRUE | FALSE =  1 or 0 = Value will be add     [1+0  =1] - True 