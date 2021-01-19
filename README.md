# myrepo

#  Best Practice Connection

Best_Practice <- odbcConnect("ODBC_BP", uid = "BPSRAWDATA", pwd = "Loma77")

## Tables - Best Practice

Patients = sqlFetch(Best_Practice,"BPS_Patients")

Actions = sqlFetch(Best_Practice,"BPS_Actions")

Alcohol = sqlFetch(Best_Practice,"BPS_Alcohol")

All_Actions = sqlFetch(Best_Practice,"BPS_All_Actions")

All_History = sqlFetch(Best_Practice,"BPS_History")

All_Immunisation = sqlFetch(Best_Practice,"BPS_All_Immunisations")

Observations = sqlFetch(Best_Practice,"BPS_Observations")

PapSmears = sqlFetch(Best_Practice,"BPS_PapSmears")

Parameters = sqlFetch(Best_Practice,"BPS_Parameters")

All_Parameters = sqlFetch(Best_Practice,"BPS_All_Parameters")

Pregnancies = sqlFetch(Best_Practice,"BPS_Pregnancies")

Prescriptions = sqlFetch(Best_Practice,"BPS_Prescriptions")

Reminders = sqlFetch(Best_Practice,"BPS_Reminders")

All_Reminders = sqlFetch(Best_Practice,"BPS_All_Reminders")

Requests = sqlFetch(Best_Practice,"BPS_All_Requests")

Antenatal_Visits = sqlFetch(Best_Practice,"BPS_AntenatalVisits")

Appointments = sqlFetch(Best_Practice,"BPS_Appointments")

Births = sqlFetch(Best_Practice,"BPS_Births")

Clinical = sqlFetch(Best_Practice,"BPS_Clinical")

Clinical_images = sqlFetch(Best_Practice,"BPS_ClinicalImages")

Contact_Address = sqlFetch(Best_Practice,"BPS_ContactAddresses")

COntacts = sqlFetch(Best_Practice,"BPS_Contacts") 

CorrespondenceIn = sqlFetch(Best_Practice,"BPS_CorrespondenceIn")

CorrespondenceOut = sqlFetch(Best_Practice,"BPS_CorrespondenceOut")

CurrentRx = sqlFetch(Best_Practice,"BPS_CurrentRx")

DaysAway = sqlFetch(Best_Practice,"BPS_DaysAway")

DbVersion = sqlFetch(Best_Practice,"BPS_DbVersion")

Diabetes = sqlFetch(Best_Practice,"BPS_Diabetes")

EPCReports = sqlFetch(Best_Practice,"BPS_EPCReports")

Extra_Sessions = sqlFetch(Best_Practice,"BPS_ExtraSessions")

Family_History = sqlFetch(Best_Practice,"BPS_FamilyHistory") 

Family_History_Detail = sqlFetch(Best_Practice,"BPS_FamilyHistoryDetail")

History = sqlFetch(Best_Practice,"BPS_History") 

Obser_Gyno = sqlFetch(Best_Practice,"BPS_ObsGyn") 

Occupation_history = sqlFetch(Best_Practice,"BPS_OccupationHistory") 

Patients_Login = sqlFetch(Best_Practice,"BPS_PatientLogin")

Reactions = sqlFetch(Best_Practice,"BPS_Reactions")

Report_Values = sqlFetch(Best_Practice,"BPS_ReportValues")

Services = sqlFetch(Best_Practice,"BPS_Services")

Sessions = sqlFetch(Best_Practice,"BPS_Sessions")

Tobacco = sqlFetch(Best_Practice,"BPS_Tobacco")

Users = sqlFetch(Best_Practice,"BPS_Users")

Visit_Reason =sqlFetch(Best_Practice,"BPS_VisitReason")

Visits = sqlFetch(Best_Practice,"BPS_Visits")

# Queries

Patients <- sqlQuery(Best_Practice,"Select * from Best_Practice")
Patients

A <- sqlQuer