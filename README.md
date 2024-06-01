In this project, let's build a Password Manager by applying the concepts we have learned till now.

Refer to the image below:

![image](https://github.com/bukka5sandhya/Password-Manager-React-Js/assets/133884532/f289e6cc-3ffe-4c5f-b8ea-517802a62cce)

https://assets.ccbp.in/frontend/content/react-js/passowrd-manager-output-v0.gif

Design Files

Click to view

Extra Small (Size < 576px) and Small (Size >= 576px) - No Passwords View

Extra Small (Size < 576px) and Small (Size >= 576px) - Masked Passwords View

Extra Small (Size < 576px) and Small (Size >= 576px) - Show Passwords View

Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - No Passwords View

Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Masked Passwords View

Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Show Passwords View

Set Up Instructions

Click to view

Download dependencies by running npm install

Start up the app using npm start

Completion Instructions

Functionality to be added

The app must have the following functionalities

Initially, the website input, username input, and password input should be empty and No Passwords View should be displayed

When non-empty values are provided for the website, username, and password and the Add button is clicked,

A new password item should be added to the list of passwords

The passwords count should be incremented by one

The stars image should be displayed in the password items instead of the passwords

The value of the input fields for website, username, and password should be updated to their initial values

When the Show Password is checked, then the password should be displayed instead of the stars image

When a non-empty value is provided in the search input field, then password items whose website is matched with the search input value irrespective of the case should be displayed

When a non-empty value is provided in the search input field, and if the website of any password item does not match the value given in the search input, then No Passwords View should be displayed

When the delete button of a password item is clicked,

The respective password item should be deleted from the list of passwords

The passwords count should be decremented by one

When all password items are deleted, then No Passwords View should be displayed

Important note

Click to view

The following instructions are required for the tests to pass

HTML input element for website should have the placeholder as Enter Website

HTML input element for username should have the placeholder as Enter Username

HTML input element for password should have the placeholder as Enter Password

The delete button for each password item should have the data-testid as delete

Resources

Image URLs

https://assets.ccbp.in/frontend/react-js/password-manager-logo-img.png alt should be app logo

https://assets.ccbp.in/frontend/react-js/password-manager-sm-img.png alt should be password manager

https://assets.ccbp.in/frontend/react-js/password-manager-lg-img.png alt should be password manager

https://assets.ccbp.in/frontend/react-js/password-manager-website-img.png alt should be website

https://assets.ccbp.in/frontend/react-js/password-manager-username-img.png alt should be username

https://assets.ccbp.in/frontend/react-js/password-manager-password-img.png alt should be password

https://assets.ccbp.in/frontend/react-js/password-manager-search-img.png alt should be search

https://assets.ccbp.in/frontend/react-js/no-passwords-img.png alt should be no passwords

https://assets.ccbp.in/frontend/react-js/password-manager-stars-img.png alt should be stars

https://assets.ccbp.in/frontend/react-js/password-manager-delete-img.png alt should be delete

Colors

Hex: #9ba9eb

Hex: #c3caea

Hex: #5763a5

Hex: #f8fafc

Hex: #454f84

Hex: #0b69ff

Hex: #94a3b8

Hex: #b6c3ca

Hex: #7683cb

Hex: #f59e0b

Hex: #10b981

Hex: #f97316

Hex: #14b8a6

Hex: #b91c1c

Hex: #ffffff

Hex: #0ea5e9

Hex: #64748b

Font-families

Roboto

Things to Keep in Mind

All components you implement should go in the src/components directory.

Don't change the component folder names as those are the files being imported into the tests.

Do not remove the pre-filled code

Want to quickly review some of the concepts you’ve been learning? Take a look at the Cheat Sheets.
