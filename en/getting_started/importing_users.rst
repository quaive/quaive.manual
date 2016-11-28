Importing Users
===============

To start working with Quaive, you need users. Users are stored as user profiles in Quaive and store everything that Quaive knows about the user - from profile image and name to organisation and telefone number. You can find them in the /profiles folder.

User profiles can be customised as well. Often, organisations have a central user database which supplies the basic information like name and contact details and is mainly used for authenication. If you want to store more data, Quaive user profiles can store this extra information for you.

There are two ways to get users into Quaive.

1. Connect Quaive to LDAP or Active Directory
   Please contact your system administrator to do that, as it requires knowledge about the organisations user database configuration.
2. Import Users from a spreadsheet
   See how it's done below.

-------------------------------
Import Users from a spreadsheet
-------------------------------

There is a bulk upload from CSV option. Column names are mapped to field names, and the data is validated before users are created. The first line needs to contain the field names.

To use the bulk upload, visit the @@import-users browser view on the profiles folder in your site::

    /plonesite/profiles/@@import-users

On this page, you will see a complete list of avaible field names. Here is an example of a CSV file that willl create 2 users::

    username,first_name,last_name,email,password
    barry_white,Barry,White,barry@test.com,replace_this
    doug_carswell,Doug,Carswell,doug@test.com,replace_this



---------------
Portrait images
---------------

After creating users with bulk upload, you can even bulk add portrait images as follows:

* In the siteroot, via the Barceloneta interface on cms.yoursite.com, add a Folder ‘avatars’ to the portal root
* Upload images into this folder with ids like ‘johndoe.jpg’ matching userid ‘johndoe’
* Run::

    http://portal_url/avatars/@@import-avatars
