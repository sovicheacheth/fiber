Model information provided by Eric Kenny, Marist College. Django app created by Michael Rudden for use at Marist College.

Readme in progress.

Needed for this program:
* Django 1.4.3
* psycopg2 2.4.6 (if using postgres)

---
Setting Up
---
* Set up Apache (details forthcoming)
* Clone git repo to correct location on deployment server
* Set up settings.py with correct database information

------
Models
------

Building

Name: Name of building. Ex: Hancock Center
Short name: Abbreviation. Ex: HC
Date added: Date and time entry was made.

LanRoom

Building id: Building that LAN room is located in.
LAN room name: Name of LAN room.
Date added: Date and time entry was made.
