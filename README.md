# Auto-Update-Report

I've prepared a macro which:

1) Adjust data from partial report to the format of main report:
    - concatenate day, month, year and format as a date ("dd/mm/yyyy"), 
    - calculate overhours based on data from columns "OverhoursStartTime" and "OverhoursEndTime"
2) Copy prepared input to sheet containing main report,
3) Refresh pivot table which source data is included in main report.

I used dynamic ranges to spot last rows of both reports. 

Here is how main report looks like:

![main_report](https://github.com/korneldata/Auto-Update-Report/blob/dde8ddea55b456b5db273622738ae3652d1b4d8c/main%20report.jpg)

And that's partial report which needs to be adjusted to the format of main report:

![partial_report](https://github.com/korneldata/Auto-Update-Report/blob/4bbfc93095e8e9a09686c54f8c19131e4c87d767/partial_report.jpg)

Partial report after changes. Columns: "EmployeeNumber", "Date" and "Overhours" will be added to main report: 

![partial_report2](https://github.com/korneldata/Auto-Update-Report/blob/c0afabf5fe6bc8d356ce27f33fadaa18c44af73b/partial_report_2.jpg)
