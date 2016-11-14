# Xojo-Xanadu  

Making Xojo Database Apps Easier for Everyone, especially for FileMaker Developers.

# More info, Overview Video, and Download

We've moved the download to our website:
http://campsoftware.com/products/xanadu-for-xojo.php

# What is Xanadu?

Xanadu is a Xojo Web App where the App runs on Mac, Windows, Linux, or Raspberry Pi and users access the App using their Web Browser. Web App Deployment and Browser Requirements: http://developer.xojo.com/system-requirements

I've been developing with FileMaker and Xojo since the 90's. I love both platforms but the FileMaker price increases since version 13 has made FileMaker expensive to use, reducing its value. FileMaker based solutions also require users to purchase FileMaker software. Xojo, on the other hand, is priced very fairly and since Xojo is Royalty Free, only the developer purchases Xojo!

That said, I find that it takes longer to work with databases in Xojo than it does with FileMaker. The goal of Xanadu is to reduce the time that it takes to develop database driven apps with Xojo. 

FileMaker makes our life easy and as a FileMaker Developer, you could go years, if not ever, using SQL since you can just create and place fields on a FileMaker Layout without writing any code. In Xojo and other systems like php/mysql you have to code. 

Without Xanadu, you would need to do something like the following: Create a Web Page and place ListBoxes, TextFields, and other control types on the Web Page. Controls have no inherent connection to a database. They are simply controls that can show data. To put data in it from a database, you'd perform a SQL statement like 'SELECT * FROM Contacts' which would return a set of records. For each record, you'd add a Listbox Row and place the record data in the Row. When a user clicks on a ListBox Row, you would extract the record ID from the RowTag, perform a SQL statement like 'SELECT * FROM Contacts WHERE UUID = "theUUID"'. Then you set would each control using the data from the record field. That's not a big deal, but when you get to 20 fields on your eighth window, it becomes very annoying.