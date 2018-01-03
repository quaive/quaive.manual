Administrator tool
==================

.. versionadded:: 1.2

The applications eases the life of the site administrators.

---------------
User management
---------------

A fully featured user listing view, providing a search and sorting options,
allows the administrator to have full control on its site users.

The users can be sorted:

- Alphabetically
- By their state
- By creation date
- By login date

Through this application it is possible to add a new user and control their state.


-----------
Screenshots
-----------

The app landing page
--------------------

.. figure:: ../images/administrator-tools-user-searched.png
    :scale: 50%
    :alt: admiinistrator tools landing page

    The app landing page

    It shows all the users sorted alphabetically and with the possibility to
    search for users.
    If you have lots of users do not worry!
    The users are paginated and will load automatically as you scroll the page.


The users sorted by their account status
----------------------------------------

.. figure:: ../images/administrator-tools-sort-status.png
    :scale: 50%
    :alt: the users sorted by their status landing page

    The users sorted by their account status



The activate/deactivate user confirmation panel
-----------------------------------------------

.. figure:: ../images/administrator-tools-activate-user.png
    :scale: 50%
    :alt: The activate/deactivate user confirmation panel

    The activate/deactivate user confirmation panel

    On each rowe of the user listing there is a badge showing the user status.
    By clicking on it you will be redirected to a panel asking you to confirm
    if you want to toggle the user state.



The create user panel
---------------------

.. figure:: ../images/administrator-tools-activate-user.png
    :scale: 50%
    :alt: The create user panel

    The create user panel

    By clicking the plus icon in the app landing page it is possible to add a new user.
    The user will receive an email
    (be sure your mail setting in the Plone control panel are ok)
    with a link to reset his password.


----------
How can I?
----------

How can I delete a user?
------------------------

Deleting a user is discouraged in Quaive, because this could break the "social" aspect of the intranet. Any content that a user has created is suddenly without a connection to the creator. That is why in the Administrator Tool, you can only disable a user to prevent further logging in.

However, there might be a reason to really delete a users, e.g. if you created a duplicate account. This is possible in the CMS https://cms[yourname].quaivecloud.com/profiles/folder_contents.

In the root, click on "Contents", then on Profiles. This takes you here: https://cms[yourname].quaivecloud.com/profiles/folder_contents.

Locate the duplicate profile: just hover over the link to see the URL. Tick the duplicate one, press Delete.
Warning: for a new user who has not created any content yet, this should be no problem. But deleting a user this way who has created content already will lead to broken links.

