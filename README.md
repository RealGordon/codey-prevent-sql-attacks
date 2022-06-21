## COMMON ATTACKS ON WEB APPLICATIONS

## Background
### Codey's Confectionery: Preventing SQL Injection Attacks

Codey’s Confectionery added a new page on their website where visitors can enter their customer ID number to see the information that the bakery has on file. A clever hacker discovered that the form is vulnerable to a SQL injection where submitting malicious code to the form will display all of the customer information.

# Project 
this project hardens the web form by validating that the submission is a number using 
`validator.js`, as well as convert the SQL query to a named prepared statement preventing a SQL injection attack.