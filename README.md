# Shell-Tools
This repository contains shell scripts for a variety of tools that can be strung together in a pipeline. 

concat_all

This is a shell script that concatenates all files in a given data directory whose file name contains a string of interest. The program allows users to specify the data directory, string of interest and name of out file. All files whose name contain this string are concatenated, minus the header in the file. Commented out is the ability for users to hardcode a header row in, if needed. Ideally, this script could be added to a pipeline where the names of the files are uniformly named based on the function of this pipeline.
