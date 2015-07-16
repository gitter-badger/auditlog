Audit Log plugin for Craft CMS
=================

[![Join the chat at https://gitter.im/timkelty/auditlog](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/timkelty/auditlog?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Plugin that allows you to log adding/updating/deleting of categories/entries/users.

Features:
 - Log Entries, Users and Categories
 - View exact details on what fields have changed
 - View who changed what on what page
 
Roadmap:
 - Log more ElementTypes (Tags, Globals, Assets)
 
Important:
The plugin's folder should be named "auditlog"

Changelog
=================
###0.2.2###
 - Added the ability to clear the log
 - Better fieldtype parsing
 - You can now easily go to origin
 - ID (and for Entries, Title) are also stored now

###0.2.1###
 - Fix "changes" url in CP - Thanks to Tim Kelty
 - Avoid Twig errors on array value - Thanks to Tim Kelty

###0.2.0###
 - Transformed AuditLog into an ElementType for easier sorting, filtering, searching and pagination

###0.1.0###
 - Initial push to GitHub