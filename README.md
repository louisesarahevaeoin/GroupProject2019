# GroupProject2019
SQL for creating a table = currently all column types are VARCHAR
once the table was created the BCP utility was used to import the dataset using the below command
bcp dbo.Weatherdata in "C:\Users\louis\OneDrive\Documents\finalgroupdataset.txt" -c -t -S lsee.database.windows.net -d LouiseSarahEvaEoin -U LouiseSarahEvaEoin -P Pembroke1 
