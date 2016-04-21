# aporeto
This repo contains solution to the 3 problems posted by aporeto.

Problem 1 :- Writes the name of 50 states with one state per line in the file with filename provided in arguments.
             It exits with code 1 if bad number of arguments are passed
	           It exits with code 2 if invalid syntax or invalid arguments are passed
	     
Note : If user says 'n' to overwrite, this script prompts "File removed", if verbose. It only means that the process on the file is stopped as it has alias problem with existing file, but it doesn't remove the existing file.

Problem 2 :- Removes duplicate lines from input file and writes unique lines to output file
	           It exits with code 1 if bad number of arguments are passed
	           It exits with code 2 if invalid syntax or invalid argumnets are passed
	           It exits with code 3 if input file can't be read

Problem 3 :- Concurrent url fetching and creation of word frequency tables with output being stored in multiple txt files
	           It exits with code 1 if bad number of arguments are passed

Note : The time taken for execution of this code is equal to the maximum time taken by a particular url amongst many urls.
For example - url0 takes 0.3s and url1 takes 0.45s, then the code will also take 0.45s as it uses go routine and channels which can do concurrent execution

 
