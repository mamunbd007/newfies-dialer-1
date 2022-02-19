.. image:: https://github.com/newfies-dialer/newfies-dialer/raw/master/newfies/resources/images/newfies.png

.. DANGER:: Newfies-Dialer open source development was discontinued in 2015, but Newfies-Dialer continues to be developed as a commercial closed source product. See https://www.newfies-dialer.org

Newfies-Dialer is an auto-dialer supporting multi-tenancy and billing. You use your own VoIP carrier so there are potentially huge savings to be made when using Newfies-Dialer compared to competing products who insist on using their VoIP termination.

In recent years, there are countless improvements in terms of features, benefits and capacity of Newfies-Dialer. There is a list of changes at https://www.newfies-dialer.org/newfies-dialer-sms-voice-broadcasting-software-changelog/

Please contact us for pricing and a live demo at newfies-dialer@star2billing or via our website at https://www.newfies-dialer.org


Overview
--------

Newfies-Dialer is a voice broadcast application, which can fulfil a variety 
of roles for a range of industries and organisations who wish to contact 
large numbers of people by phone in a short space of time.

The Newfies-Dialer aplication has been built using a messaging system so that
it can support distributed processing on cloud servers. The platform is
focused on real-time operations and task call distributions to clustered
brokers and workers meaning that many millions of calls can be processed daily.

Newfies-Dialer can be installed on a standalone server for smaller deployments.
It currently utilises the Freeswitch Telephony engine
(http://www.freeswitch.org) to process the the outbound calls. However support
for other telephony engines, such as Asterisk may be added in the future.

Newfies-Dialer is written in Lua & Python using the Django Framework, and 
operates with message brokers such as RabbitMQ.

In order to communicate with external systems, Newfies-Dialer has been
released with a substantial set of API's to easily integrate the platform
with third-party applications.

Newfies-Dialer is supplied with a comprehensive administrative and user
interface which allows you and your customers to create outbound call
campaigns, add phonebooks, subscribers, as well as record audio messages
and design more complex IVR (Interactive Voice Response) applications.
When ready and tested, the campaign can be launched from the interface.


Who is it for ?
---------------

NGOs:

    The platform can be used to offer complex data collection, voting
    applications, notification for availability of supplies and
    dissemination of health information.

Marketing:

    Newfies-Dialer is a telephony based marketing tool to deliver
    advertising to company contacts.

Emergency:

    Provide a message delivery platform to quickly and efficiently send
    messages to communities.

Finance:

    Debt Recovery and Reminders, this can be easily integrated with call
    centre software and processes.

Health & Welfare:

    Deliver appointment reminders to patients of dentists, doctors and
    other organisations.


Documentation
-------------

Complete documentation :

    - http://docs.newfies-dialer.org/


Screenshot
----------

* Customer Frontend :

    http://localhost:8000/
    This application provides a User interface for restricted management of
    the User's Campaign, Phonebook, Subscriber. It also provides detailed
    Reporting of calls and message delivery.

.. image:: https://github.com/newfies-dialer/newfies-dialer/raw/develop/docs/source/_static/images/customer_screenshot.png


* Dashboard Frontend :

    http://localhost:8000/dashboard/
    Newfies-Dialer Dashboard provides a contact and call reporting for the running campaign.

.. image:: https://github.com/newfies-dialer/newfies-dialer/raw/develop/docs/source/_static/images/newfies-dialer-dashboard.png


* Admin Dashboard :

    http://localhost:8000/admin/
    This interface provides user (ACL) management, a full control of all
    Campaigns, Phonebooks, Subscribers, Gateway, configuration of the
    Audio Application.

.. image:: https://github.com/newfies-dialer/newfies-dialer/raw/develop/docs/source/_static/images/admin_screenshot.png


Translation
-----------

Help us translate Newfies-Dialer, we use Transifex: https://www.transifex.com/projects/p/newfies-dialer/


Additional information
-----------------------

* Official website : http://www.newfies-dialer.org

* `Twitter account for news and updates`_

.. _`Twitter account for news and updates`: https://twitter.com/newfies_dialer


Support & Installation
----------------------

The Newfies-Dialer project is supported by Star2billing S.L.
For more information, see http://www.newfies-dialer.org/

Please email us at newfies-dialer@star2billing.com for more information
