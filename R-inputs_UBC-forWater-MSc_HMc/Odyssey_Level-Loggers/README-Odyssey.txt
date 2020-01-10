Odyssey Capacitance Water Level Logger files

When a CSV file is exported from the logger and saved to a (Windows OS) computer, the file format is:

	row(1:4) = header with 
		column 1: row names = (site name, site number, logger type, serial number)
		column 2: values for rownames(1:4)
	row(5:6) = empty
	row(7) = variable names 
		column 1: "Scan No"
		column 2: "Date and Time"
		column 3: "       Capacitive Water Level"
		column 4:  ""
		column 5: ""
	row(8) = 	variable names continued
		column 1: ""
		column 2: ""
		column 3: "RAW VALUE"
		column 4:  "CALIBRATED VALUE"
		column 5: ""
	row(9) = empty
	row(10:n) = data values
	
Note that row 8 variable names in columns 3 & 4 should be in row 7	columns 4 & 5	