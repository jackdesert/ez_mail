EZMail
======

EZMail is a simple ruby class that lets you send an email.


Configuration
-------------

Copy config.yml-EXAMPLE to config.yml, and edit the fields


Sending Mail
------------

    require './ez_mail'

    message = EZMail.new('address@domain.net', 'Cool Subject', 'Warm Body')
    message.deliver


