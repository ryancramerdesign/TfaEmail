# ProcessWire Two Factor Authentication

## Email or SMS delivery module

Requires ProcessWire 3.0.109 or newer. 

### How to install 

1. Place the files for this module in /site/modules/TfaEmail/
2. In the admin, go to Modules > Refresh.
3. Go to Modules > Site > Tfa, and click install for this module.  

### How to setup two-factor authentication

1. Edit your user profile in the ProcessWire admin.
2. Scroll to the bottom and you should see a new field for “Two factor authentication”. 
3. Select the “Email/SMS” option and click Submit (note: it’ll ask for your password first). 
4. After submitting the change, go back to the field to provide additional info. 
5. It’ll ask you to confirm that everything is working by having you enter a code. Once you’ve completed that, you are done.

Once two-factor authentication is enabled, when you login, there will be a second step
where it will ask you to enter a code. 

### How to use SMS delivery

This module sends emails, however most mobile network providers also provide a free email-to-text
service that can be very useful with this module. For instance, AT&T emails look like 
`5551234567@txt.att.net` where the number portion represents the mobile phone number. You will want
to google “email to text provider” to find out what email address you should use (replacing “provider” 
with your mobile service provider). 
