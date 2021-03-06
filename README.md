Introduction
============
This document is a work-in-progress spesification for botylicious. It's meant to be a school book example on how not to brainstorm.

Botylicious is (will eventually be) an userfriendly, lowadmin, minimal configuration IRC bot for hassle free administration of IRC channels.

For techincal stuff, see tech.md

== Requirements ==
Devtools
--------
	- bug/feature tracker (agile, anon-input)

== Issues ==
Strategical
-----------
	- Language
	- Framework
	- Coding standards/Criteria for implementing new code into master
	- Releaseplan strategy

Core functionality
==================
Modularity
----------
The bot must consist of a lighweight core that lets the admin easily plug functionality in and out as (s)he sees fit. Modules must be integrades in such a way that it is a minimal effort to write new ones expanding Botylicious functionality.

Security
--------
Must implement some sort of security.

Storage
-------
Must provide easy to set up and flexible storage of data important to the bot.

Interfaces
----------
Provide text based administration through communication via IRC.
Web frontend for easy administration, installing modules and so on.


Suggested modules
=================
Autoop
------
Automatic opping and voicing of users joining the channel if the bot has operator status.

Karma
-----
Karma system for the channel to credit good users and discredit bad ones.

Meeting minutes
---------------
Take notes during meetings.

URL expander
------------
Watch for urls from popular url shortening services and post title or full url to the channel to avoid spam and fools.

Spotify expander
----------------
Watch for Spotify URLs and post name of song, artist and so on.

FAQ/Wiki
--------
Store frequently asked questions in a database for easy reply to noobs.

User tracking
-------------
Keeping track on who is on the channel so one can request when the person was last seen.

Logging
-------
Channel logging with search functionality.

Statistics
----------
Channel statistics. Display on web.