---
title: GarminDB
categories: ['python', 'garmin', 'dbs']
---
## [GarminDB](https://github.com/tcgoetz/GarminDB)

### Download and parse data from Garmin Connect or a Garmin watch, FitBit CSV, and MS Health CSV files into and analyze data in Sqlite serverless databases.


[Python](https://www.python.org/) scripts for parsing health data into and manipulating data in a [SQLite](http://sqlite.org/) DB. SQLite is a light weight DB that requires no server.

What they can do:
* Automatically download and import Garmin daily monitoring files (all day heart rate, activity, climb/descend, stress, and intensity minutes) from the user's Garmin Connect "Daily Summary" page.
* Extract sleep, weight, and resting heart rate data from Garmin Connect, store it as JSON files, and import it into the DB.
* Download and import activity files from Garmin Connect. A summary table for all activities and more detailed data for some activity types. Lap and record entries for activities.
* Summarizing data into `stats.txt` and a common DB with tables containing daily summaries, weekly summaries, and monthly summaries.
* Graph your data from the commandline or with Jupyter notebooks.
* Retain data as JSON files or FIT files so that the DB can be regenerated without connecting or redownloading data from Garmin Connect.
* Export activities as TCX files.

Once you have your data in the DB, I recommend using a SQLite browser like [SQLite Studio](http://sqlitestudio.pl) or [DB Browser for SQLite](https://sqlitebrowser.org/) for browsing and working with the data. The scripts create some default [views](http://www.tutorialspoint.com/sqlite/sqlite_views.htm) in the DBs that make browsing the data easier.
