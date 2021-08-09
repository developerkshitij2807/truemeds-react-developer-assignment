# Truemeds React Developer Assignment Project

`Feature Story`: Upon landing the user should be able to see a login screen with options to enter his
mobile number & generate OTP. App should generate a new OTP using the generateOTP API
provided below, once generated, user should be able to enter the OTP. App should validate the OTP
using the loginAPI, after successful login app should save the access token received which would be
used throughout the application for all the other API calls.

## Contents

- [Task](#task)
- [Approach](#approach)
- [Initial Setup](#initial-setup)
- [Dependencies](#dependencies)

### Task

On successful login, redirect the user to a new screen where the user sees a countdown timer
(minutes & seconds) start from 1 minute - once the timer reaches 00:00, hit the fetchArticle API(with
access token) to get data required to load it in a list with the article image, name, author &
categoryName as it’s elements. Allow the user to reset the timer to 1 minute only when the timer has
reached 00:00, once the timer resets and counts down to 00:00 again, fetch the same listing and
refresh the data.
Allow the user to log out from the app, which should clear the saved access token for new users to
login and use the app.

`Mandatory points`:

1. Make use of create react app command to initiate your project
2. Make use of Axios for API calls
3. Make use of Redux for state management
4. All pages should be mobile friendly
5. Console log API success and errors

   `Data validations`:
6. Mobile number should be only 10 numbers
7. Mobile number should only start from 6,7,8,9
8. OTP should only be numeric and 4 digits
9. Access token should be saved on login and passed inorder to fetch successful response from
the fetch article API

### Initial Setup
- Created a react app using cra
- Cleared out the src folder for clearing not required files.
- Installed material-ui as the frontend library for the use


### Dependencies
- [material-ui/core]
- 