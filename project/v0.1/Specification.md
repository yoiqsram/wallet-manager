# WalletManager v0.1

Approved by:
- [ ] @yoiqsram


## Description

WalletManager is a progressive web application that could be used to track personal incomes & expenses accross devices through decentralized data. This early version is used to test the concept of implementing decentralized system.


## Target Audience

This version will only be used by me (@yoiqsram) as a proof of concept.


## Technology Stack

This version will only use simple HTML, CSS, and JavaScript. JavaScript library that will be used to handle decentralized data is IPFS.


## Features

This app will use clien-side browser to do front end (FE) and back end (BE).

### [BE] Authentication

Authentication will use hash from combination of username and password. The authentication process is used to allow users access their data from local database and be able to share their data to other device using the same username and password. It will not handle any modification of both username and password.

### [BE] Database

Database will be used to handle income and expense data for a specific user account. It should handle syncronization through device and resolve unmatch records.

### [FE] User Account Management

At the beginning of a session, user will be asked to login to their account and be able to log out anytime after. It should have login interface and capability to log out in dashboard.

### [FE] Income & Expense Input Forms

Input forms will be very simple. It should only asked for simple transaction detail (type, name, description, amount)

### [FE] Sync Data

Show online devices used by a user account and sync database accross them all.


## Mockups



## Acceptance Criteria

- [ ] Have login session
- [ ] Create local database for a user account
- [ ] Read and update local database only for a specific user
- [ ] Show online devices used by a user account
- [ ] Show different transactions between devices
- [ ] Merge database accross devices
