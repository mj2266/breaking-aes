CS698U ASSIGNMENT 2
Group Members:
1) Ayush Sahni (21111019)
2) Manjyot Singh Nanra (21111038)
3) Sharanya Saha (21111056)

The folder contains the following files :
	1) HD_power_trace.csv: It contains the hamming distance power traces.
	2) estimate_trace.py: This file is updated to extract the round 10 key
	3) Output file: final_key.txt (will be created by the code)


-The file is coded in python 3.8.8 (In case the code doesn't work, please use the same version)

-Required Libraries:
	-Numpy
	-Matplotlib
	
Inverse shift row is implemented to extract all the bytes of the round 10 key correctly.
The bytes are inserted in column wise fashion i.e.
	The first byte is at position row 1 and column 1
	The second byte is at row 2 and column 1
Inverse shift row takes care of the above column wise insertions and provides the output accordingly.
The inverse shift row mappings are stored in a dictionary named Invshiftrow.
The output is in hexadecimal format. It is stored in final_key.txt and also displayed on console.

The code takes 10-12 minutes to produce the output, please let the script run for the same amount of time.
