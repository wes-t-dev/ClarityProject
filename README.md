# ClarityProject
 This is the assignment for Clarity Ventures job application
 Weston Twiner
 11/12/2022


1. PROJECT SCENARIO
You are being asked to build a working implement of a “client’s” feature request.
The client has a high volume application which must be able to send emails to customer.
It is critical that a user not be interrupted or delayed while navigating the website simply because an email fails to
send – i.e. other code must be able to call a mail routine without waiting for a result.

Your challenge is to address this problem with the following constraints:
• Code should be written in C#.
• Send Email Method should be in a dll that can be reused throughout different applications and entry
points.
• Email sender, recipient, subject, and body (not attachments), and date must be logged/stored indefinitely
with status of send attempt.
• If email fails to send it should either be retried until success or a max of 3 times whichever comes first, and can be sent in succession or over a period of time.
• Please store all credentials in an appsettings instead of hardcoded.
• At minimum that method/dll should be called from a console application.
• Extra Credit if attached to an API that can be called from Postman.
• EXTRA Credit if a front end (wpf/asp.net web application/etc…) calls the API to send the email.
• In any scenario you should be able to take in an input of a recipient email to send a test email.
Feel free to use any third party libraries if necessary.
Please initialize within a git repo (github/etc…) an