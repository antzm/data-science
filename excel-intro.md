# Excel Intro

Below are some important notes on Excel, which could be useful for every data scientist.

It's a short introduction to some specialized aspects of Excel.

## Comma vs Semicolon

Depending on the country, decimal numbers are written either as 1.23 or 1,23 and Excel automatically uses the correct format, depending on the regional settings of the computer.

If the format 1.23 is used, then the arguments in the Excel functions should be seperated with a comma (,).

Otherwise, if the format 1,23 is used, then the arguments in the Excel functions should be separated with a semicolon (;) as the comma is reserved for the decimal numbers.

Thus, if we would like to use the RANDINT() function to get a random number i.e. between 1 and 100, then we should write:

* In the American versions of Excel, or when we write decimals as 1.23:

=RANDINT(1, 100)

* In the European versions of Excel, or when we write decimal as 1,23:

=RANDINT(1; 100)

> Important: Sometimes we may find on-line examples where the comma is used to seperate the arguments in an Excel function. If though we are using a European version of Excel, those examples simply won't work and we should firstly replace all the commas with semicolons, so that the functions will work.

## Decimal Point

When using Excel, the decimal point is represented either as a comma or a dot. This is done automatically and it depends on the regional settings of each computer. Changing the regional settings, the decimal point representation will automatically change.  

Thus, the decimal point will appear automatically as a comma or a dot, depending only on the computer where the Excel file will be opened and regardless of the regional settings of the computer where the Excel file had been created or it was last saved.

This means that Excel uses internrally the proper notation for the correct representaiton of the decimal numbers and whenever we save a file as .xlsx or .xls, this notation is retained and the decimal numbers would always appear correctly, in every computer, in every part of the world.

## Exporting Data

Whenever we export an Excel file in CSV format, all the extra information about the decimal numbers is lost. This means that 1.23 will be exported as 1.23, while 1,23 will be exported as 1,23 but when we import those CSV files back to Excel, 1.23 would be different from 1,23 as only one of those numbers (depending on the regional settings) will be treated as number, while the other will be treated as text.

## Importing Data

So, whenever we import data to Excel, from a CSV or a TXT file, the decimal numbers should have the same format as the one that Excel uses, otherwise those numbers will be treated as text. In such a case, we need to change the decimal point from comma to dot, or vice versa, and then convert those strings to a number.

Obviously, it would be preferable to import data from a CSV or TXT file in the same decimal format, as the one that we use in our computer. Whenever though this is not possible, we can use the function `SUBSTITUTE()` in order to replace the dot or the comma in the decimal numbers, and then the function `VALUE()` to transform those strings to numbers.

## Sharing data

From the above we conclude that the safest and easiest way to share data between countries that use different representations for the decimal numbers, is by using an Excel file that has been saved as .xls or .xlsx because it will always represent the decimal numbers correctly.

This means that it would be better to avoid sharing your data in CSV or TXT format because the person who will use them, may have to go through a lot of work to make the decimal numbers appear correctly.

## CSV Files

Excel provides the option to save a file in CSV format. 

CSV means "Comma Seperated Values" but even if the data in a CSV file are separeted by a semicolon, or a tab, or a space, this type of file would still be called CSV (Comma Seperated Values).

Whenever the format of the decimal numbers is 1.23 then Excel uses the comma (,) to seperate the values in a CSV file.

Whenever though the format used by Excel is 1,23 then obviously the CSV files cannont have the comma as a seperator because the comma is already being used in the decimal numbers. In this case, Excel uses the semicolon to separate the values in the CSV files.

## Date format

Excel accepts dates starting from 1/1/1900 and stores them as integer numbers. The date 1/1/1900 corresponds to 1 and every date since then is stored as an integet number that shows how many days have passed since 1/1/1900.

Dates before 1/1/1900 are stored as text.

## Time format

Excel saves the time as a decimal number between 0 and 1 and this applies regardless if the time is expressed as hours:minutes or as hours:minutes:seconds.

## Date and Time format

There's an option to format a cell so to contain both a date and a time. Combining the date and the time into a single cell, means that the foramt is stored as a decimal number. The integer part of this number shows the date, while the decimal part shows the time. In this case, removing the decimal part gives us the date, while removing the integer part  gives us the time.

In fact though, we would get the exact same result if we just add a date and time together, using the plus (+) operator. Thus, it would be better and simpler to use columns that store seperately the date and the time, and if we ever need to combine them, we could simply add the date and the time.

## Spliting columns

Sometimes we may need to split a column into multiple columns. For example, we may have one column which contains names and we may want to split that column into two columns, one with the names and on with the surnames.

To accomplish this, we can use the option "Text to columns", which we can find in the "Data" ribon. In that option, we need to set the delimiter e.g. space, that Excel will use to split the data into columns.

Altrenativley, we could export those data as a text file, and then import them as extrenal data and use the space as delimiter.

## Combining columns

If we would like to combine columns in Excel, we can use the `&` operator as `= A1 & A2 & A3` and if we would like to add a space or another character between the columns, we could use the `&` operator as: `= A1 & " " & A2 & " " & A3`

## File format

Saving an Excel file to .xlsx (default format) will save the complete Excel sheets, which have a size of 1048576 * 16384 but if an Excel file is saved to the old format .xls then the Excell sheets will be saved with a size of 65536 * 256 and any data outside of this range will not be saved.
