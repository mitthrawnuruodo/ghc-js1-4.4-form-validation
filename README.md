# Exercises for JS1 Lesson 4.4: Managing Web Forms with JavaScript

Make an HTML file with a form: **Sign up for news and promos.**

The form should have the following input fields:

* Username
    - needs to be at least 6 characters long
* Password
    - needs to be at least 8 characters long
    - needs to contain at least one digit
    - needs to contain at least one lower case letter
    - needs to contain at least one upper case letter
* E-mail
    - needs to be a valid email (you should use a ready made reg ex pattern for this)
* E-mail, retype
    - needs to be the same as the other E-mail
* One check-box, I have read the T&C
    - needs to be checked
* Two check-boxes, receive news + receive promos
    - at least one of which needs to be checked (no need to sign up for news and promos and not get at least one of them)

Use JavaScript to: 
- set up an eventListener to invoke a validation function
- validate form fields
    - add informative error messages when a validation fails
- do not submit form until all fields are valid