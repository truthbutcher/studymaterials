Programming Assignment 4 Tianjian Li

1. This program takes two parts of input. 
One is a excel document that ends with .xlsx . The other is commands in the form of
	Integer Integer -v 
Taken by the console.

2. At line 113,enter the correct directory and name of the xlsx document in your computer. For example, if the document is on your C drive named test.xlsx, replace line 113 with 

InputStream ExcelFile = new FileInputStream("C:\\test.xlsx");

3. The program reads a xlsx document through the library functions provided by apache poi. To get access, go to https://poi.apache.org/download.html#POI-4.1.1
and download the binary distribution and add the external jars to your java build path. 

4. The output is through the console. 

5. For further assistance, please contact tl2387@nyu.edu 
