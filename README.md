# Business Intelligence Assessment

This project involves creating a range of values for the "Year Opened" field in the Reseller dimension of the DB661 database. The task must be performed using MS SQL Server Analysis Services (SSAS) with the Tabular Model or PowerPivot.

Requirements
Year Opened Range: The goal is to categorize the "Year Opened" into the following ranges:

1970-1974

1975-1979

1980-1984

1985-1989

1990-1994

1995-1999

=2000

The year ranges must be displayed in ascending order in the Reseller Dimension.

DAX Code: A DAX measure should be created for the "Year Range" field.

Measure: A measure needs to be built to calculate the number of resellers that fall under the year range 1980-1984. The expected result is 106 resellers.

PowerPivot or Tabular Model: Ensure that the solution uses PowerPivot or SSAS Tabular and does not involve the multidimensional cube technique.

# Steps to Complete the Task

Create the Year Range Logic: 

  Use DAX to define the year range for the "Year Opened" field.

  The DAX code should categorize each reseller into the appropriate year range.

Set Up PowerPivot or Tabular Model:

  Load the DB661 database into PowerPivot or SSAS Tabular.

  Apply the DAX measure to create the necessary Year Range field.

Use Pivot Tables in Excel:

  Connect the model to Excel via PowerPivot.

  Build a pivot table to calculate the number of resellers that fall into the 1980-1984 year range.

  Ensure that the result is 106 resellers.
