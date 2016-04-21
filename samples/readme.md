This script writes the name of 50 states with one state per line in the file with filename passed in input argument
Usage: $0 --create-file=<filename> [--no-prompt] [--verbose]
filename - required argument. Please provide the name of the file to be written
--no-prompt - optional argument. By default, it will prompt the user if user attempts to overwrite the file
--verbose - optional argument. By default, it won't print any additional commands during the execution

It will print help message showing usage with exit 1 - in case of bad arguments
It will print help message showing usage with exit 2 - in case of invalid syntax or invalid arguments
