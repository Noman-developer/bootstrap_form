# Bootstrap Registration Form

A simple Bootstrap form with validation. I made it while learning forms.

## What it is

A registration form with 6 fields. Every field is required. When you press submit, the form checks your input in the browser. Bad fields get a red border and a short error message. When everything is correct, a green success message appears and the form clears.

This form does not save data anywhere. It only checks the input in the browser.

## Fields and validation

* Full Name: required, at least 2 characters
* Email Address: required, must be a valid email like name@example.com
* Phone Number: required, digits only with optional + at the start, 7 to 15 characters
* Password: required, at least 6 characters
* Confirm Password: required, must match the password
* Gender: required, pick one option

## Tech stack

* HTML5
* CSS (Bootstrap 5.3.2 through CDN)
* JavaScript (plain, no libraries) for the confirm-password check and the success message

## How to view

1. Download or clone this repo.
2. Open `index.html` in any browser.
3. You need internet so the Bootstrap style file can load from the CDN.

## Author

Noman Javed
