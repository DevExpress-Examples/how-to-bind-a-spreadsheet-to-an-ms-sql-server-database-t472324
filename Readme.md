<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/SuppliersExample/Form1.cs) (VB: [Form1.vb](./VB/SuppliersExample/Form1.vb))
<!-- default file list end -->
# How to bind a spreadsheet to an MS SQL Server database 


This example demonstrates how to bind a cell range on a worksheet to the sample <strong>Northwind</strong> database to load data from the <strong>Suppliers</strong> data table. To accomplish this task, the <a href="https://documentation.devexpress.com/#CoreLibraries/DevExpressSpreadsheetWorksheetDataBindingCollection_BindToDataSourcetopic">WorksheetDataBindingCollection.BindToDataSource</a> method is used.<br>This application also enables end-users to add, modify or remove data in a data table. They can use the corresponding buttons on the <strong>File</strong> tab, in the <strong>Database</strong> group to edit the data and save their changes back to the database. <br>To insert new rows, a data entry form is used. The user should fill out the given data entry fields and click the <strong>Save </strong>cell to add a new record to the <strong>Suppliers </strong>data table. Clicking the <strong>Apply Changes </strong>button posts the updated data back to the database. To remove a record, the user should select the required Suppliers row on the worksheet and click the <strong>Remove Record </strong>button. The <strong>Delete</strong> dialog will be invoked asking the user to confirm the delete operation. <br>To send the modified data to the connected database, the <strong>Update</strong> method of the <strong>SuppliersTableAdapter</strong> is used. <br><img src="https://raw.githubusercontent.com/DevExpress-Examples/how-to-bind-a-spreadsheet-to-an-ms-sql-server-database-t472324/16.2.3+/media/9daa7d1f-e2e8-11e6-80bf-00155d62480c.png">

<br/>


