![banner](https://www.olivertacke.de/labs/wp-content/uploads/2017/12/h5pxapikatchu_bar_1920.png "banner")

# H5PxAPIkatchu
This Wordpress plugin is a simple solution to catch 'em all, those xAPI statements
that have been sent by [H5P](https://h5p.org) content types. Users should be able
to store and view/export the xAPI statements.

This plugin is NOT intended to provide functionality for analysis, etc. There is
no point in recreating what is already available in Learning Record Stores or
what you can do yourself with a spreadsheet software, scikit-learn, etc.

If you need more, you should give [Learning Locker](https://learninglocker.net/)
a shot. It's [open](https://github.com/LearningLocker/learninglocker), free and shiny.

## Features
* Store important values of xAPI statements emitted from H5P content types in your database.
* View and export the data for further analysis.
* Optionally limit capturing to particular H5P content types only.
* Optionally store the complete xAPI statements as a string - know what you're doing ...

## Support me at patreon!
If you like what I do, please consider to become my supporter at patreon: https://www.patreon.com/otacke

## Install/Usage
Install H5PxAPIkatchu from the [Wordpress Plugin directory](https://wordpress.org/plugins/h5pxapikatchu/) or via your Wordpress
instance and activate it. Done.

The most important parts  of the xAPI statements that are emitted by H5P content
types on your system should now be stored in your database. You can view and
download them via the new WordPress menu item.

## Screenshots
You can change some options to your particular needs.

![options](https://www.olivertacke.de/labs/wp-content/uploads/2017/12/screenshot-1.png "Options")

You cannot only view the stored data, but also download them as an CSV file.

![table_view](https://www.olivertacke.de/labs/wp-content/uploads/2017/12/screenshot-2.png "Data in Table")

## License
H5PxAPIkatchu is is licensed under the [MIT License](https://github.com/otacke/h5pxapikatchu/blob/master/LICENSE).

## GDPR
Please note that as of May 25, 2018 you may have to comply with the General Data Privacy Regulation ([GDPR](http://gdpr-info.eu/)).

H5PxAPIkatchu supports the functions that WordPress offers to

- use suggestion for your privacy statement text,
- export personal data of a user, and
- delete personal data of a user.

Background: If you're using H5PxAPIkachu, by processing the xAPI statements you're processing at least these personal data items according to art. 4 GDPR:

- xAPI statement: Actor/name (Full name of the Agent)
- xAPI statement:Actor/Inverse Functional Identifier (email address, openID or account data within the host system)
- WordPress user id (ID given by the WordPress host system)

Please make sure to account for these items in your GDPR processes and documentation.
