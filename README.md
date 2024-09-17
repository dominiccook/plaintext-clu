# Plain-Text Accounting (PTA) Command-Line Utility

 This is a very simple script for adding transactions to a running journal
 built to work with ledger-cli.

 It simply takes a date, description, 2 accounts and an amount, and
 appends an existing journal file.
 
## Functionality

   1: The date is grabbed from system and formatted as YYYY-MM-DD.
   If you don't wish to use the current date, you have to enter
   the desired date manually (input is not sanitized).

   2: User is then prompted for a transaction description.

   3: Using the ledger "account" function, and rofi's dmenu option,
   the user can select both a source account and target account
   for the transaction. The user can also enter a new account, but 
   has to enter the entire name manually (i.e. no auto-complete, see below).

   4: User is prompted for amount of the transaction.


### It may be beneficial to add:
 - a list of standard transactions like cash-deposit/withdrawal,
   credit card payments, etc. 
 - functionality for transactions involving more than 2 accounts
 - better date handling (e.g. shortcut for previous day)
 - file handling (e.g. create journal if one doesn't exist)
 - auto complete accounts in GUI
 - display transaction as it is being built

