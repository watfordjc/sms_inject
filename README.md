# sms_inject

This class can send SMS messages using Gammu MySQL storage.

It can send messages to one or more recipients using the Gammu MySQL database.

The class creates records for the new messages in MySQL database with the outbox of Gammu.

It can send also long messages by splitting them in multiple parts.