checkservers
============
Simple check script for HTTP with logging, email and SMS notification (through 
`Mollie <http://www.mollie.nl/>`_), which checks the availability of an internet connection before checking.


Requirements
------------
* CURL
* Mollie account (when SMS notification is used)

Getting Started
---------------
#. Copy the files in `etc` to the system `/etc/` directory.
#. Copy the files in `sbin` to `/usr/local/sbin/`.
#. Copy the `config.example` files to `config` in `/etc/checkservers/` and `/etc/sendsms/`, and edit them.
#. Add a cron job to execute the `checkservers` script at regular intervals (ie. 10 minutes).