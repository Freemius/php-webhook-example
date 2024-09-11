# Freemius PHP Webhook Example

Super-simple webhook example that does two things:

1. Subscribes new plugin users to MailChimp's mailing list.
2. Send post-uninstall custom emails to users based on different uninstall reasons.

# Requirements
* Freemius PHP SDK (https://github.com/Freemius/php-sdk)
* MailChimp PHP SDK (https://github.com/drewm/mailchimp-api)
* Emails sender (e.g. http://swiftmailer.org/)

# Setup

Please read our [documentation](https://freemius.com/help/documentation/marketing-automation/events-webhooks/#how_to_create_a_webhook) to learn how to set up a webhook listener from the [Developer Dashboard](https://dashboard.freemius.com/).

# Testing
During development on localhost, your webhook will not be accessible from the Internet. Therefore, testing will not automatically work. 

1. You can examine the webhook calls with tools like [RequestBin](http://requestb.in/).
2. Or the recommended way is to use tunneling with services like [ngrok](https://ngrok.com/). This way you can use your IDE and debugger.
