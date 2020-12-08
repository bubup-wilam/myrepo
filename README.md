# myrepo

# Access to Best Practice

Best_Practice <- odbcConnect("ODBC_BP", uid = "BPSRAWDATA", pwd = "Loma77")

resultset = sqlFetch(Best_Practice,"BPS_Patients")
resultset

BA <- sqlQuery(Best_Practice,"Select Firstname, Surname from BPS_Patients")
BA

