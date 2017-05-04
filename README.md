CONTENTS OF THIS FILE
---------------------
   
 * Introduction
 * Requirements
 * Recommended modules
 * Installation
 * Configuration
 * Troubleshooting
 * FAQ
 * Maintainers

INTRODUCTION
------------

The Browser Push Notification module send push notification to web browsers
using PUSH WebApi and service-worker.

 * For a full description of the module, visit the project page:
   https://drupal.org/project/browser_push_notification

 * To submit bug reports and feature suggestions, or to track changes:
   https://drupal.org/project/issues/browser_push_notification

REQUIREMENTS
------------

  - SSL certificate is mandatory : Push notification will only work on domain with 
SSL enabled.

  - Web Push library for PHP (https://github.com/web-push-libs/web-push-php)

  - Only supported in following Web Browsers:
    - Chrome:42 or Above
    - Firefox:44 or Above

INSTALLATION
------------

 * Step 1: Install dependent library web push 
   composer require minishlink/web-push. For more details 
   https://github.com/web-push-libs/web-push-php

 * Step 2: Install as you would normally install a contributed Drupal module. 
   See: https://www.drupal.org/docs/8/extending-drupal-8/installing-modules
   for further information.

 * Step 3: Copy js/serviceWorker.js into root of the drupal installation
   Eg:https://www.example.com/serviceWorker.js

 * Step 4: Copy Application Publick Key & Private Key from 
   https://web-push-codelab.appspot.com and set it in browser push notification
   config settings form.  

CONFIGURATION
-------------
 
 

TROUBLESHOOTING
---------------


MAINTAINERS
-----------

Current maintainers:
 * Shylaja r (shylajaphp) - https://www.drupal.org/u/shylajaphp

This project has been sponsored by:
 * Iksula Services
   Visit https://www.iksula.com for more information.
