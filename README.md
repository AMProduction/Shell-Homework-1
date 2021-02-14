# Shell Homework 1
### Download file «sample_cut.txt» here https://github.com/dhoncharuk/DWBI_DQE_lab/tree/main/examples_for_slides
1. Find all rows that include department name «Marketing» and get rid of department name (i.e. pick only name  and phone). Write results in a new file called «marketing_<YESTERDAY>.txt», where YESTERDAY is yesterday‘s date in format YYYY-MM-DD.
1. Using files «sample_cut.txt» and «marketing_<YESTERDAY>.txt» Find people (i.e. Names) from file «marketing_<YESTERDAY>.txt» that not work in Marketing department (i.e. not present in «sample_cut.txt»). Put results into the new file called «namesakes_preparation»
1. Append to the end of file «namesakes_preparation» a new row with count of the people from file «sample_cut.txt» who has the same name as a person in «namesakes_preparation».
1. Rename «namesakes_preparation» to «namesakes.txt»  
  
### **Use:**
1. 1 line-commands only ! 
1. pipes «|», redirections «>» and «>>», command substitution.
1. utilities: grep, cat, cut, sed, awk, date  

### **Do not use:** 
1. bash-scripting! i.e don't use cycles and if-constructions  

### **Result:**
1. 3 files: «marketing_<YESTERDAY>.txt», «namesakes_preparation»,  «namesakes.txt»
1. 4 files where you save your commands (each of task 1-4 in separate file). Call them "command_n", where n - task no
