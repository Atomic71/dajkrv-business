# User type requirements

There are 4 different user types in the system:
- Superuser
- Admin
- Member
- Donor


## SUPERUSER

Is meant to be a manager of the entire system. For security reasons, there should not be more than one or two people.

Requirements list:
- [ ] Organizations (all)
    - [ ] CRUD
- [ ] Transactions
    - [ ] CRUD
- [ ] Users
  - [ ] CRUD
- [ ] Validations
    - [ ] CRUD


## Admin

Is designed to be the person in charge of managing the day-to-day operations, i.e. someone who people come to ask questions in the face of adversity. 

> This role should always be present during working hours, as the day-to-day will sometimes include admin things to do.

Requirements list:
- [ ] Organizations (own)
    - [ ] Update
      - [ ] Blocked hours
      - [ ] Setting availiabiliy
      - [ ] Reading storage
      - [ ] Reading statistics 
- [ ] Transactions
    - [ ] Read all
    - [ ] Make (not possible to create user entry, but transaction has optional "donorId")
- [ ] Users
    - [ ] Create members
    - [ ] Update members 
    - [ ] Delete members
    - [ ] Read all (Members limited to blood type and transaction history)
- [ ] Validations
    - [ ] Read all
    - [ ] Approve