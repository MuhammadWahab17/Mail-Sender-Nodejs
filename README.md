# Mail-Sender-Nodejs

**Step 1: Create a Gmail App Password**
To send emails through Gmail using Nodemailer, you'll need to create an app password. This is an additional layer of security for your Gmail account when using third-party applications like Nodemailer.

Follow these steps to create a Gmail app password:
Go to your Google Account.
Select Security.
- Under "Signing in to Google," select 2-Step Verification.
- At the bottom of the page, select App passwords.
- Enter a name that helps you remember where you'll use the app password.
- In the "Select app" dropdown, choose "Mail" if it's available; otherwise, select "Other (custom name)."
- In the "Select device" dropdown, choose "Other (custom name)."
- Give your app password a name (e.g., "Nodemailer") and click on the "Generate" button.
- Google will generate a unique app password for you. Make sure to copy this password because you won't be able to see it again.

**Step 2: Understand and Use the Provided Code**
The provided code is a Node.js function that uses Nodemailer to send an email. It takes three parameters: the sender's email address, the app password you generated earlier, and the receiver's email address.

Replace the placeholders in the code with your own values:

Replace Your_MAIL with your Gmail email address (e.g., "example@gmail.com") as the sender.
Replace YOUR_APP_PASSWORD with the app password you generated in Step 1.
Replace RECEIVER with the receiver's email address (e.g., "recipient@example.com") as the receiver.
Once you've updated the code with your credentials, you can use the sendMail function to send an email. The function will log "Email sent" along with the email response if the email is sent successfully. If there's an error, it will log "Error sending email" along with the specific error details.


**Step 3: Setup**
To use the code, create a new JavaScript file (e.g., sendEmail.js) and paste the provided code into it. Save the file.
Open your terminal (command prompt) and navigate to the folder where you saved the sendEmail.js file.
Initiate npm and install mail sender module - Nodemailer and Run the script using Node.js:
**- npm init -y**
**- npm install nodemailer**
**- node sendEmail.js**
