# Trend® IMSVA Add-on for Splunk®


Trend IMSVA Add-on for Splunk provides CIM compliant field extractions and data enrichment for your Trend InterScan Messaging Security (IMSVA) data.


# Version 1.0.0


# Release Notes


1.0.0: Jul 2020

- Initial release


# Trend IMSVA data

The add-on provides field extractions and data enrichment for both 'Policy events' and 'Message tracking' IMSVA data.

'Policy events' provide details on the filtering process while 'Message tracking' data provides insight on the final action taken by the virtual appliance.

Policy events:
Provides details on the policy rules that were triggered, the actions taken, and the message details.

Message tracking:
Records message details such as the sender, recipient(s), message size, and the final action that IMSVA or Cloud Pre-Filter has taken. The query result also indicates the name and type of the policy rule that was triggered.

MTA events:
Provides connection details of Postfix on the local computer where the central controller is installed.

IP filtering:
Provides the time when IMSVA started and stopped blocking messages from the queried IP address.


# Forwarding Trend IMSVA data

Through the IMSVA console, log forwarding via syslog and UDP or TCP port must be configured.


# Add-on deployment


Install the Add-on on your Splunk platform.

For distributed environments, the Add-on needs to be deployed on the on Indexer(s) as it includes parsing configuration parameters.


# Index IMSVA data

The data is indexed via syslog.


# Additional notes

For lack of documentation on the format of the fields, there may be some extractions of missing fields.


If you have more info on the missing fields, please share with us and we will improve the add-on.


# For any help and suggestions, please contact us [jjfeitosa@gmail.com]

