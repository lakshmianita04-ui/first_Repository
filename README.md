# first_Repository
Basics 
To find 

• What is the total price of all products in the dataset?			
total sum of prices  =SUM(D2:D35) =10100  =SUM(num1,[num2] ,..)
Total sum of prices of all products with quantity = prices*Quantity =PRODUCT(D2 * E2) Then drag and calculate the sum  SUM(I38:I71)=289700
Summing all the products, as shown in the Dth column. The total sum can be calculated by multiplying prices by quantity.

• How many products are there in the dataset?		
=COUNTA(B12:B35) =24    
COUNTA is used to count text-type products.  =COUNTA(value1,[value2] ,..)

• Calculate the average price of the products.		
=AVERAGE(D2:D35) =297.0588235
Average of the products column.
=AVERAGE(num1,[num2] ,..)
2) Min and Max:	
	• Determine the minimum price among all products.
=MIN(D2:D35)=30
The minimum value in the D-th column is determined using MIN().
MIN(num1,[num2] ,..)

• Find the maximum price among all products.
=MAX(D2:D35)=1000
The maximum value can be determined from the D th column
MAX(num1,[num2] ,..)
3) IF Function:	
• Using an IF function, create a new column named Price Range to categorize products with a price greater than or equal to $500 as 'High Price' and others as 'Standard Price'.												
IF(D2>=500, "High Price", "Standard Price") D2 greater than 500 is denoted as High Price, and less than 500 is called Standard Price.
IF(logic test, value if true, value if false)
Price Range 
High Price
Standard Price
Standard Price
High Price
Standard Price
Standard Price
Standard Price
Standard Price
High Price
Standard Price
High Price
Standard Price
Standard Price
Standard Price
Standard Price
Standard Price
Standard Price
High Price
Standard Price
Standard Price
High Price
Standard Price
Standard Price
Standard Price
High Price
Standard Price
Standard Price
Standard Price
Standard Price
Standard Price
Standard Price
Standard Price
High Price
Standard Price


4) SUMIF and COUNTIF:		
• Calculate the total price for products in the 'Electronics' category using the SUMIF function.
=SUMIF(F2:F34,"Electronics",D2:D35) = 8050  =SUMIF(range,criteria,[sum range])


  • Determine the count of products with a price less than $100 using the COUNTIF function.					
=COUNTIF(D2:D35,"<100") = 11  =COUNTIF(range,criteria)

          
		
5) Text Formatting - LEFT, RIGHT, MID:			

• Create a new column named Day with the first 2 characters of each 'Product ID' using the LEFT function.							
Day
28
15
03
11
22
07
19
23
05
14
17
25
08
18
16
21
20
27
01
14
14
09
19
21
29
03
11
16
07
13
24
02
17
09
LEFT(text,[num chars])
• Create a new column named Country Code by extracting the last 2 characters from the 'Product ID' column using the RIGHT function.								
Country Code
US
US
US
US
US
UK
UK
UK
UK
UK
IN
AU
DE
CA
ES
CA
CN
IT
UK
US
RU
CA
BR
CA
CA
CA
CA
ES
CA
CA
CA
CA
IN
FR
RIGHT(text,[num chars])
• Create a new column named Month by extracting the 4th to 6th characters from the 'Product ID' column using the MID function.								
Month
JAN
FEB
MAR
APR
MAY
JUN
JUL
AUG
SEP
OCT
JUN
NOV
DEC
FEB
APR
AUG
AUG
JAN
MAR
AUG
MAY
JAN
JUL
AUG
SEP
JUN
JUL
APR
MAR
APR
MAY
DEC
JUN
JUL
MID(text,start num,num chars)


