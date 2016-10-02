# Xojo-Xanadu  

Making Xojo Database Apps Easier for Everyone, especially for FileMaker Developers.

# Overview Video
 
Coming soon after Xojo XDC 2016: http://www.xojo.com/xdc

# Getting Started

- Download and Install Xojo: http://www.xojo.com/download/?lang=en
- Download MBS Plugin: https://www.monkeybreadsoftware.de/xojo/plugins.shtml
- Copy the MBS Plugins into the Xojo Plugins Folder.
- Launch Xojo.
- Download the Xanadu Project and 'database.SQLite'.
- Open and Run the Project file with Xojo.
- Once the App Compiles and Runs, the App will Launch and a Browser window will open.
- Login with the user name 'hal' and password 'hal'.
- The Contacts Page will show how the interface works.
- The Other Page will show an on screen keypad and the HTMLViewerControl.

We'll be blogging about Xanadu. Sign up to receive our blog posts in your email: http://campsoftware.com/contact/

# Why Xanadu?

Xanadu is a Xojo Web App where the App runs on Mac, Windows, Linux, or Raspberry Pi and users access the App using their Web Browser. Web App Deployment and Browser Requirements: http://developer.xojo.com/system-requirements

I've been developing with FileMaker and Xojo since the 90's. I love both platforms but the FileMaker price increases since version 13 has made FileMaker expensive to use, reducing its value. FileMaker based solutions also require users to purchase FileMaker software. Xojo, on the other hand, is priced very fairly and since Xojo is Royalty Free, only the developer purchases Xojo!

That said, I find that it takes longer to work with databases in Xojo than it does with FileMaker. The goal of Xanadu is to reduce the time that it takes to develop database driven apps with Xojo. 

FileMaker makes our life easy and as a FileMaker Developer, you could go years, if not ever, using SQL since you can just create and place fields on a FileMaker Layout without writing any code. In Xojo and other systems like php/mysql you have to code. 

Without Xanadu, you would need to do something like the following: Create a Web Page and place ListBoxes, TextFields, and other control types on the Web Page. Controls have no inherent connection to a database. They are simply controls that can show data. To put data in it from a database, you'd perform a SQL statement like 'SELECT * FROM Contacts' which would return a set of records. For each record, you'd add a Listbox Row and place the record data in the Row. When a user clicks on a ListBox Row, you would extract the record ID from the RowTag, perform a SQL statement like 'SELECT * FROM Contacts WHERE UUID = "theUUID"'. Then you set would each control using the data from the record field. That's not a big deal, but when you get to 20 fields on your eighth window, it becomes very annoying.

# How does Xanadu work?

Xanadu is *meant* to take away as much of this pain as possible. You place your ListBoxes, TextFields, and other controls on the Web Page, and then tell Xanadu a bit about the Table, ListBox, where the Detail controls are, and then run ListLoad and Detail Load. Once that's set up you can add fields to your table and add controls to your Web Page with almost no code!

The Xanandu project requires Xojo and the Monkeybread MBS Plugin.

# Xojo 

We love the Xojo platform. Not only is the development environment very affordable, but it's also powerful, easy to use, and the Xojo Team is very accessible. Time after time, Xojo has responded to new features and bug fixes in a quick and open fashion. It's a pleasure to work with Xojo! 

Xojo is free to evaluate for an unlimited amount of time so you can run and debug. Purchasing Xojo allows you to compile, deploy, and distribute your Apps. Since Xanadu is a Web App, all you need is Xojo Web: https://www.xojo.com/store/ 

# Monkeybread MBS Plugin for Xojo and Monkeybread Web Starter Kit

Monkeybread has been creating software for Xojo for as long as I can remember. The MBS Plugins is their primary product, but the Web Starter Kit super useful too.

Monkeybread's MBS Plugin for Xojo is an amazing plugin for Xojo with over 59,000 functions: http://monkeybreadsoftware.de/xojo/

Monkeybread also has a 'Web Starter Kit' which has a ton of code to help you get started with Xojo Web Apps. Try out the demo: http://monkeybreadsoftware.de/xojo/WebStarterKit/