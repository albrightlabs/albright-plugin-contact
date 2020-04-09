# Contact Plugin for OctoberCMS
A simple OctoberCMS plugin that provides a contact form, message keeper, and notifications.

## Purpose
This plugin is intended to be used for in-house projects only and installed/managed via the private plugins and themes partnership with the OctoberCMS project. Anyone, however, is free to use this plugin if they find value.

## Install
Install by running `git clone https://github.com/albrightlabs/albright-plugin-contact.git plugins/albrightlabs/contact; php artisan october:up;` from project root.

## Usage
Add the Contact Form component to the page you wish to display the form. Customize the form as needed.

Set the notification recipient, company contact information and location, and form submission success message in Settings > Contact.

Display other contact information on the site using the following Twig variables:
* `{{ contact.email }}` will display email from Contact settings
* `{{ contact.phone }}` will display phone from Contact settings
* `{{ contact.address }}` will display address from Contact settings

## Contribute
Feel free to fork and contribute to this plugin! Please email support@albrightlabs.com with any and all questions.
