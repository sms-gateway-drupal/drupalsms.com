---
layout: default
---

Drupalsms.com is just an info site for a Drupal project [SMS gateway](https://www.drupal.org/project/sms_gateway).

SMS gateway currently in Drupal 7.x. The plan for 8.x port, will not happen any
time soon.

## Project info

The sms gateway module provides a Drupal web interface for your sms transactions on your mobile phone with the use of the services provided by smsgateway.me.

This includes per user configuration, sending messages, retrieving messages, managing contacts, group messaging, bulk messaging, and other things you can do with sms in your mobile phone.

The maintainers of the this module are not in any way affiliated with smsgateway.me.

This project was posted in DO in 2016, but the actual development started last March 25, 2017, Saturday.

## Installation

1. Create account in [smsgateway.me](https://smsgateway.me/).
2. Download and install **SMS Gateway** on your mobile phone and sign-in to your account.
3. Download and enable **SMS Gateway** module into your Drupal v7.x website.
4. Set username, which is your smsgateway.me email address, and your password, at /admin/config/sms-gateway.

## Development phases

1. Setup of module files and dependencies.
2. Setup sms-gateway config.
3. List of Devices.
4. Promote sandbox to full Drupal project.
5. Contacts (individual).
6. Messages (inbox).
7. Message (individual thread).
8. Write message form.
9. Reply message form (at the bottom of an individual thread).
10. Group contacts - contact containing several other contacts.
11. Messages (inbox) to add listing of all outgoing messages to multiple contacts.
12. Message (group thread).
13. Reply message form to add sending to multiple contacts.

Those in **bold** are done.
Those in **_italic bold_** are currently in progress.

## Contributions

Contributions are welcome and can be done in various ways. These can be testing
the module, [reporting issues](https://www.drupal.org/project/issues/2799679?categories=All),
[providing patches](https://www.drupal.org/project/sms_gateway/git-instructions),
among others.

Co-maintainership are as well welcome.

For this site, and the demo site, contributions can be made via github.

* [sms-gateway-drupal/drupalsms.com](https://github.com/sms-gateway-drupal/drupalsms.com)
* The demo site will be available after a stable version is released.
