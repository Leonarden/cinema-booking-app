# cinema-booking-app
A Python 3 CLI app example that uses sqlite3 for persistence

/cinema.db
$ sqlite3 cinema.db
SQLite version 3.22.0 2018-01-22 18:45:57
Enter ".help" for usage hints.
sqlite> select * from Seat;
A1|0|120.0
A2|1|100.0
A3|0|120.0
B1|0|100.0
B2|1|150.0
B3|1|120.0
sqlite> 

/banking.db
$ sqlite3 banking.db
SQLite version 3.22.0 2018-01-22 18:45:57
Enter ".help" for usage hints.
sqlite> select * from Card;
Master Card|23456789|234|Marry Smith|5000.0
Visa|12345678|123|John Smith|4400.0
sqlite> 
Note install requirements.txt (pip3 install -r requirements.txt)
#Example of use:
$ python3 -d main.py
Your full name: John Smith
Preferred seat number: A1
Your card type: Visa
Your card number: 12345678
Your card cvc: 123
Card holder name: John Smith

Purchase successful!





