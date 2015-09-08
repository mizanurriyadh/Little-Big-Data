# cool-data
a random collection of interesting data

<h3>a few commands you might want:</h3>
  cat top-1-million-websites.tsv | cut -f2 -d$'\t' | sort | uniq -c | sort -n
  
  mysql -u USERNAME DBNAME < FILENAME.sql
  
  mongoimport --db DBNAME --collection COLNAME --type json --jsonArray --file FILENAME.json
  
  mysqlimport --columns='head -n 1 FILENAME.csv' --ignore-lines=1 -uUSERNAME -p TABLENAME FILENAME.csv
