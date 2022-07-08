#############################################

How to use NN-QSAR classification model
#############################################

Download PaDel standalone JAVA application

	a. Calculate Autocorrelation Descriptors

	b. Select only ATSC6c, AATSC5e, AATSC4m, ATSC7c and AATS8i descriptors

Downoad Orange open source machine learning tool

	a. Create an Orange workflow to predict new compounds (widget- File, Load Model, Prediction and Save Data)

	b. load downloaded model in "load Model" widget.

	c. load PaDel descriptor file with 5 discriptors in "File" widget.

	d. Save predicted data from "Save Data" widget.
