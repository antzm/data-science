# Excel Intro

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

