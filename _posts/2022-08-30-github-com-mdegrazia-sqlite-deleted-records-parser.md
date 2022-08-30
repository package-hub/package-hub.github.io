---
title: SQLite-Deleted-Records-Parser
categories: ['python']
---
## [SQLite-Deleted-Records-Parser](https://github.com/mdegrazia/SQLite-Deleted-Records-Parser)

### Script to recover deleted entries in an SQLite database


    sqlparse.py -f /home/sanforensics/smsmms.db -o report.tsv
    sqlparse.py -f /home/sanforensics/smssms.db -r -o report.txt
	
	Optional switch -p to print out re purposed B-Leaf pages:
	
	sqlparse.py -p -f /home/sanforensics/smsmms.db -o report.tsv
    sqlparse.py -p -f /home/sanforensics/smssms.db -r -o report.txt
	
    