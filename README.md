# Freemius PHP Webhook Example

Super-simple webhook example that does two things:

1. Subscribes new plugin users to MailChimp's mailing list.
2. Send post uninstall custom email to users based on different uninstall reasons.

# Requirements
* Freemius PHP SDK (https://github.com/Freemius/php-sdk)
* MailChimp PHP SDK (https://github.com/drewm/mailchimp-api)
* Emails sender (e.g. http://swiftmailer.org/)

# Setup
Currently, the developer's dashboard do not expose an option to add your webhook address. You would need to contact us first via support@freemius.com

# Testing
During development on localhost, your webhook will not be accessible from the "Internet", therefore testing will not automatically work. 

1. You can examine the webhook calls with tools like [RequestBin](http://requestb.in/).
2. Or the best way is to use tunneling using services like [ngrok](https://ngrok.com/).
