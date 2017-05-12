# sms_inject

This class can send SMS messages using Gammu MySQL storage.

It can send messages to one or more recipients using the Gammu MySQL database.

The class creates records for the new messages in the outbox table in Gammu's MySQL database.

It can also send long messages by splitting them in multiple parts.