# allele-table-automation
VBA code of macro created to perform automated web browsing of LIMS site to populate allele tables.

Automating a previously mind-numbing workflow which data needed to be selected for each sample of a case to populate an allele table for reporting. Due to slow site load times this process can take up hours. With this macro, cases can be input and the macro directs windows to click through the needed HTML elements to populate the tables without the need for manual input.

Setup: 
- In Visual Basic, under tools, select References and ensure 'Microsoft Internet Controls' is selected. 
- Navigate to the appropriate LIMS page - AT to the shipment level.
- Add cases to the excel file column starting at A2.
