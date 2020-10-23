# Excel Intro

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

So, whenever we import data to Excel, from a CSV or a TXT file, the decimal numbers should have the same format as the one that Excel uses, otherwise those numbers will be treated as text. In such a case, we need to change the decimal point from comma to dot, or vice versa, and then convert those strings to a numbers.

## Conclusion

The safest and easiest way to share data between countries that use different representations for the decimal numbers, is by using an Excel file that has been saved as .xls or .xlsx because it will always represent the decimal numbers correctly.

This means that it would be better to avoid sharing your data in CSV or TXT format because the person who will use them, may have to go through a lot of work to make the decimal numbers appear correctly.

## CSV Files

CSV means "Comma Seperated Values" but actually this applies only when the format for the decimal numbers is 1.23 

When the format used by Excel is 1,23 then obviously the CSV files cannont have the comma as a seperator because the comma is already being used in the decimal numbers. In this case, Excel uses the semicolon to separate the values in the CSV files.

But even if the data in a CSV file are separeted by a semicolon, or a tab, or a space, this type of file would always be called CSV (Comma Seperated Values).

