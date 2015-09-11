Roundcube Dropbox Attachment Plugin
===========================================

Uses Dropbox dropins api: https://www.dropbox.com/developers/dropins.

This plugin is for adding large files to the message body as the share URL.
It is based on dropbox api only and service clients need to the account of dropbox for each.


Install
=======
Follow the steps in https://www.dropbox.com/developers/dropins/chooser/js and get your appKey

####  Manual Install
* Place this plugin folder into plugins directory of Roundcube.
* Rename config.inc.php.dist to config.inc.php. Update config.inc.php with the above appKey and other optional options
* Add `dropbox_attachments` to $config['plugins'] array in your Roundcube config

### Via Composer
* require the package in composer: `"hassansin/dropbox_attachments": "dev-master"`
* `composer update`
* Update the generated dropbox_attachments/config.inc.php with the above appKey and other optional options

Screenshot
==========
![Screnshot](https://raw.githubusercontent.com/hassansin/dropbox_attachments/master/screenshot.png)
