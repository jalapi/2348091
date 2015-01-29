INTRODUCTION
============
Insightly Integration for Drupal module takes the contact information from an 
EntityForm and sends it to Insightly CRM. From the configuration page you can 
select which fields to send to Insightly. Possible fields are first and last 
name, phone number and email address. You can also select the forms used.

REQUIREMENTS
============
This module requires the following modules:
 * Entityform (https://www.drupal.org/project/entityform)

INSTALLATION
============
 Install as you would normally install a contributed Drupal module. See:
 https://drupal.org/documentation/install/modules-themes/modules-7
 for further information.

CONFIGURATION
==========
Configure the module at admin/help/insightly_integration_for_drupal:

1. Enable the module from the Modules list.
2. Configure the module.
  2.1. Add you Insightly API key.
  2.2. Select the fields you want to use.
  2.3. Save.
  2.4. Select the forms you want to use.
  2.5. Save.
3. The module is up and running, and sends the contact informations to your 
Insightly.

The fields selected must be named field_last_name, field_first_name, 
field_phone_number and field_email_address for the module to recognize them.


MAINTAINERS
============
Current maintainer:
 * Teemu Aro (teemuaro) - https://www.drupal.org/user/3014169

This project has been sponsored by:
 * Drupaletti Oy (http://www.drupaletti.fi)
