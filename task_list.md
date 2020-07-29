# Email Capture Service

## Prerequisites

* Task a: Install google cloud sdk

### Do
https://cloud.google.com/appengine/docs/standard/java11/quickstart

### Do
https://cloud.google.com/appengine/docs/standard/java11/building-app

* Task b: Install IntelliJ IDEA
* Task c: Setup GitHub account
* Task d: Install git

## Capture emails (post request to database, send email)

### Publish landing page

* Task 1: Get template landing page hosted on the Internet
* Task 2: Modify the landing page to customize it for your business
* Task 3: Modify the landing page to send a post request to a url with a fake campaign_id and the entered email address

### Save email addresses

* Task 4: Create an email endpoint to receive the email post request
* Task 5: Create a database table to save email addresses
* Task 6: Save the email address received to the email database table

### Send email response

* Task 7: Modify the email endpoint to send a thank you response email

### This is now functional!

## Process emails (restful processing, database)

### Administrative pages (add authentication)

* Task 8: Create an administrative website for restricted access
* Task 9: Add authentication to the website for administrative pages
* Task 10: Add an administrative user account

### Get the list of email addresses (get request to return a list)

* Task 11: Add an endpoint that returns the list of emails
* Task 12: Add a web page that displays the list of emails

### Add products (post request to create records in the database)

* Task 13: Create a web page to post a product
* Task 14: Create a product endpoint to receive the product post request
* Task 15: Create a database table to save products
* Task 16: Save the product received to the product database table

### Add campaigns (containment database relationships)

* Task 17: Create a web page to post a campaign
* Task 18: Create a campaign endpoint to receive the campaing post request
* Task 19: Create a database table to save campaigns
* Task 20: Save the campaign received to the campaign database table

### Associate emails to products by campaign (aggregate database relationships)

* Task 21: Modify the email endpoint to look up the campaign
* Task 22: Create a database table to save the product-email associations
* Task 23: Modify the email endpoint to create the product-email association
* Task 24: Modify the email listing to show the products an email is interested in

### Email templates (using templates)

* Task 25: Create an email template to use for sending the thank you response email
* Task 26: Modify the thank you response email to use the template
* Task 27: Create a web page to post an email template
* Task 28: Create an endpoint to receive an email template
* Task 29: Create a database table to save the email template
* Task 30: Save the email template received to the email template database table
* Task 31: Use the email template to send the thank you response email

## Scheduling tasks (restful, database, sending emails)

### Schedule email (more restful)

* Task 32: Create an endpoint to receive a scheduled email
* Task 33: Create a database table to save the scheduled email
* Task 34: Create a web page to post a scheduled email
* Task 35: Save the scheduled eamil to the scheduled email database table

### Send scheduled emails (running scheduled tasks)

* Task 36: Create a scheduled process that sends scheduled emails
* Task 37: Fetch scheduled emails to send
* Task 38: Send emails

### Campaign flow (scheduling the next task)

* Task 39: Modify the scheduled process to schedule the next email template as a scheduled email
