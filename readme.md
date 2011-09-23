# CrossPoster Plugin for Movable Type

CrossPoster is a plugin for Movable Type 4.0 that allows you to simultaneously
post entries to different weblogs (on different platforms) from Movable Type:

* Personal bloggers enjoy keeping journals on services such as LiveJournal and
  Movable Type but find it hard to keep all of them in synch with each other.
  CrossPoster now allows you to compose your entries in Movable Type and
  simply check boxes to post these to your LiveJournal account.

* Corporate bloggers need somewhere to stage (or preview) an entry before
  publishing it to the production (or live) site. Compose your entry on your
  staging server and once you're ready, simply check a box to post the entry
  to your production server!

* Atom API - CrossPoster makes use of industry standards to crosspost your
  entry. The Atom API is supported by the vast majority of popular weblogging
  platforms.

* Connectors - CrossPoster has been built in a completely extensible fashion.
  Connectors for CrossPoster allow you to crosspost your account to any
  weblogging platform. By default connectors for LiveJournal, Vox and Movable
  Type are available. Forthcoming developer docs will illustrate how easy it
  is to create a connector (a matter of 5 minutes!)

* Post and Edit - in the past, similar plugins have been available but have
  unfortunately been limited in only posting or editing entries. If you were
  to go back and edit an entry that was crossposted, CrossPoster will attempt
  to crossupdate too (provided that the platform being crossupdated to
  supports it!)

# Prerequisites

* Movable Type 4.x


# Installation

To install this plugin follow the instructions found here:

http://tinyurl.com/easy-plugin-install


# Use

## Creating a CrossPosting Account

To be able to crosspost entries to other weblogs, you will need to create
crossposting accounts. These accounts can be created on the blog level:

1. Click Preferences > CrossPosting (or choose the CrossPosting link from the
left hand menu on the blog settings page) to get a list of all the accounts
created for this blog.

    For each account, the following may be listed:

    * A logo that denotes the connector being used (for example the 
      LiveJournal connector)
    * The name of the account (which can be clicked to edit the account)
    * A URL to the blog if required by the connector
    * Any credentials (such as username and password) are also displayed if
      required by the connector

2. To create a new account, simply click the New Crossposting Account link on
the top right hand side of the table. This will open up a dialog box where you
can create your account.

3. First, select the connector that corresponds to the platform of the weblog
you wish to crosspost to. By default, the following connectors are available:

    * LiveJournal
    * Vox
    * Movable Type

    But these can be easily extended by creating custom connectors (developer
    documentation forthcoming!)

4. On choosing the connector, several other fields may appear depending on
what information is needed by the connector. Typically these involve a URL to
the blog and a username and password to log into the system.

5. Once you've entered in all the required information, simply hit Save
Changes to create your account. If successfully, you will be returned to the
account listing screen where you will now see your new account!

## Crossposting an Entry

Actually crossposting an entry to other weblogs (or accounts) is a piece of
cake.

1. First, make sure the entry is set to Published. Crossposter will not post
entries marked as Unpublished

2. Next, click the Select Accounts link that appears in the Crosspost To field
under the Publishing section of the entry editing screen.

3. This will open the following box which lists all the crossposting accounts
configured for the current blog. Simply check those you wish to crosspost the
entry to.

4. Click Save to crosspost your entry. If an error occurs during crossposting,
you will be duly informed by an error message. If the crossposting was
successful, your Activity Log will be updated with an appropriate message:

5. When you edit an entry, sites you have already crossposted to will
automatically be checked (and thus automatically updated).


# License

This plugin is licensed under the GPLv2 license.

#Copyright

Copyright 2007, Arvind Satyanarayan. All rights reserved.
