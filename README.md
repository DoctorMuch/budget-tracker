# Budget Tracker

## Description

* This is an early version of a budget tracker that a user can use for simple income/expense tracking.
* Key features include mobile-first design and offline functionality.

## Table of Contents
* [About the Project](#about-the-project)
* [Installation](#installation)
* [Usage](#usage)
* [Built With](#built-with)
* [Future Development](#future-development)
* [Contact](#contact)

### About the Project
* This PWA allows for implementation in an environment where Internet connectivity is not reliable.
* Uses IndexedDB to log transactions when offline to upload when connection returns.
* Service Worker maintains front-end function for logging deposits and withdrawals.

### Installation

* [Budget Tracker](https://evening-hamlet-97238.herokuapp.com/)
* App is deployed through Heroku and uses MongoDB Atlas for database storage.
* No dependencies need to be installed to see app functionality.

### Usage
* This app has a very straightforward interface, though it is not without its limits.
* ![Budget_Tracker](https://user-images.githubusercontent.com/78443941/146714924-4386b81f-cd41-4d08-9b6e-9cae301b0c6e.gif)
   * User enters the name of the transaction
   * Then user enters the amount (value) of the transaction.
   * Selects '+ Add Funds' or '- Subtract Funds', depending on the transaction type.

#### Built With
* Mongoose
* MongoDB Atlas
* Express

#### Future Development
* As mentioned in [Usage](#usage), this UI has room for improvement. It is simple but susceptible to errors.
* Changing buttons to 'Deposit' and 'Withdrawal' and separating them would improve UX.
   * Different color buttons would also improve UX.
   * Validating user entry before committing to database.
* Establishing Delete function for mistaken entries.

#### Contact
* GitHub: [DoctorMuch](https://github.com/DoctorMuch)
* Email: [David Mueth](mailto:davidmueth@gmail.com)
