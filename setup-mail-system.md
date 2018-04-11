# Setup Email System

- [Mailgun Signup](#mailgun-signup)
- [Setup Mailgun to CRM](#set-mailgun-configuration)

## MailgunSignup

Register to Mailgun from mailgun [website](https://www.mailgun.com/). Do following ways to complete setup,

* Do signup from this [link](https://signup.mailgun.com/new/signup) .
* Active your account from activation mail
* Go to domain [url](https://app.mailgun.com/app/domains) .
* Add your domain
* Click on your added domain and copy api keys.

## SetMailgunConfiguration

Copy the configuration details and set in the `.env` file.

In the `.env` file you will see Mailgun setting options.

``MAILGUN_DOMAIN=w3bd.com
MAILGUN_API_KEY=key-306943cdf9f5b3b57d8829a448508278
MAILGUN_PUBLIC_API_KEY=pubkey-456ce405c626029aa27ab0537a5a822e
MAILGUN_FORM_NAME=W3BD
MAILGUN_FORM_EMAIL=crm@w3bd.com
MAILGUN_REPLY_TO_EMAIL=crm@w3bd.com
``

You will found full mailgun configuration in following file,
`config/mailgun.php`

