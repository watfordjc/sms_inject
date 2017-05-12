# sms_inject

This class can send SMS messages using Gammu MySQL storage.

It can send messages to one or more recipients using the Gammu MySQL database.

The class creates records for the new messages in the outbox table in Gammu's MySQL database.

It can also send long messages by splitting them in multiple parts.

## PHP 5.6 and PHP 7

This class has been updated for PHP versions 5.6 and 7.0.

The MySQL extension has been replaced by the MySQLi extension in the code.

If you haven't already installed the PHP MySQLi extension on Debian Jessie:

    sudo apt install php5-mysqlnd

For Ubuntu Xenial:

    sudo apt install php-mysql

Package names may differ for other operating systems.