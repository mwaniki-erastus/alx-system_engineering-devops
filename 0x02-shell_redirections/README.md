Working with shell input/output redirection
shell scripts that do different things:
0-hello_world - prints hello world 
1-confused_smiley - uses escape to print a special  character on the stdout
2-hellofile - uses cat to print the contents of one file
3-twofiles - uses cat to print the contents of 2 files
4-lastlines - is used to print the first 10 lines of a file
5-firstlines - is used to print the last 10 lines of a file
6-third_line - uses a combination of head and tail to print a specific line ina file
8-cwd_state - writes the output of ls -la to afile
9-duplicate_last_line uses tail to get thye last line and appends it to the same file 
10-no_more_js uses find to seach for all .js files and deletes them
11-directories - uses find to count the number of directories in the current folder including hidden ones but excluding the current and parent directories
12-newest_files - uses ls -1t to sort files within a directory with the newest file first per line and pipes the output to head to print only the first 10 files
