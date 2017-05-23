This code was written and tested in windows 7 and windows 10, with python 3.5.

This directory contains the following files and subdirs:
	irisData.txt
		a csv format file with a selected data about iris flowers, necessary for the first option test
	k_means.py
		the k_means source code module
	main.py
		the main function executed by the scripts
	parameters.txt
		parameter values useds by the main
		these parameter can be changed by the user
		only int values are accepted
	rapport.docx
		a repport about the k-means TP
	README.txt
		this file
	results/
		subdir who receives the test results
	run.bat
		run script for windows
	run.sh
		run script for unix

Dependencies:
	The third test option uses the plot library matplotlib

Input parameters:
	the input parameters can be set in the parameters.txt file
	only integers parameters are accepted

To execute the tests:
	in windows:
		Double click in the DOS script run.bat
	in unix:
		Double click in the bash script run.sh
	Another option:
		Open a terminal in this directory and run the following command:
		> python main.py

How the program works:
	Inside the program, you have 2 choices:
	Press 1 if you want to test the k-means algorythm with random data.
	Press 2 if you want to test the k-means algorythm with the predefined iris data.
	Press 3 if you want to test the k-means algorythm with a grafical plot about the clusters efficiency.

Results:
	The results will be written in the format CSV in the subdir ./results/

Possible errors:
	Datas appears wrongly in results files(csv):
		you should change your area settings and put the lists divider to ";" instead of "," 