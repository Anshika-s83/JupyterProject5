Firstly I created a Jupyter Notebook Project .
then imported a dataset from koggle named Medical Appoinment No Shows(that is not present in my repository dew to sizing issues).
After that i started performing operations on it.
first operation i performed to check wheather there is null or not.
after that checked for duplicates.
there were some duplicates so i removed them by droping them and creating a new file named Cleaned_file.csv.
Next I converted columns into list format to operate on them.
Standarize Column Labels.
Checked DataType of all Columns.
converted them into Standard form as well.
Final dataset has,
PatentId as Object,
AppointmentID s int64
Gender as object
ScheduledDay as datetime64[ns, UTC]
AppointmentDay as object
Age as Int64
Neighbourhood as object
Scholarship as int64
Hipertension as Int64
Dibetes as int64
