# TRANSACTIONS

The system functions on a ledger-type source of truth. Actual state of the blood bank is computed at runtime, via transactions.


## Transaction meta

Transactions have the following fields
- Transaction type
- User id
- Amount (in ml)
- Comment
- Organisation
- Blood type

## Transaction types
- INTERNAL (made by the admin or member)
  - can be classified as 
    -  `help`
    -  `waste removal`
    -  `ledger correction`
- DONATION (made by the donor exclusively)

