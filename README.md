# Xojo-Xanadu coming soon

Making Xojo Database Apps Easier for Everyone, especially for FileMaker Developers.

Xojo-Xanadu is a Xojo Web App where the App runs on Mac, Windows, Linux, or Raspberry Pi and users access the App using their Web Browser. Web App Deployment and Browsers Requirements: http://developer.xojo.com/system-requirements

I've been developing with FileMaker and Xojo since the 90's. I love both platforms but the FileMaker price increases since version 13 has made FileMaker expensive to use, reducing it value. Developing with FileMaker also requires the users of the solution to purchase the FileMaker software. Xojo, on the other hand, is priced very fairly and since Xojo is Royalty Free, only the developer purchases Xojo!

That said, I find that it takes longer to work with databases in Xojo than it does with FileMaker. This project intends to reduce the time it takes to work with databases in Xojo. 

FileMaker makes our life easy and as a FileMaker Developer, you could go years if not ever using SQL since you can just create and place fields on a FileMaker Layout without writing any code. In Xojo and other systems like php/mysql you have to code. 

Without Xojo-Xanadu, you would need to something like the following: Create a Web Page and place ListBoxes, TextFields, and other control types on the Web Page. Controls have no inherent connection to a database. They are simply controls that can show data. To put data in it from a database, you'd perform a SQL statement like 'SELECT * FROM Contacts' which would return a set of records. For each record, you'd add a Listbox Row and place the record data in the Row. When a user clicks on a ListBox Row, you would extract the record ID from the RowTag, perform a SQL statement like 'SELECT * FROM Contacts WHERE UUID = "theUUID"'. Then you would each control using the data from the record field. That's not a big deal, but when you get to 20 fields on your eighth window, it becomes very annoying.

Xojo-Xanadu is mean to take away as much pain as possible. Instead, you'd place your ListBoxes, TextFields, and other controls on the Web Page, and then tell Xanadu about the Table, ListBox, and Detail and then run ListLoad and Detail Load. Once that's set up you can add fields to your table and add controls to your Web Page with almost no code!

Overview Video: coming soon

Getting Started:
- bullet points coming soon

Xojo is free to evaluate for an unlimited amount of time so you can run and debug. Purchasing Xojo allows you to build your Apps. Since Xojo-Xanadu is a Web App, all you need is Xojo Web: https://www.xojo.com/store/index.php 