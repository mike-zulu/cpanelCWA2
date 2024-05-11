# cpanelCWA2, cwa, CPCP


In the context of DNS resolution, what is the term for passing a received query over to another nameserver?
recursion

To force the local system to resolve a domain to a specific IP address, which of the following files would you modify to accomplish this?
/etc/rndc.conf

In a cPanel & WHM environment, DNS zone templates can be used to ensure which of the following? To standardize a set of zone records and structure that will be used for a large number of DNS zones

Which of the following command-line tools can be used to list running processes in a Linux environment? ps

Which cPanel-provided script should be to restart the DNS service and will provide any startup-related errors and events in its output?
/scripts/restartsrv_named

Which of the following options best describes the role of DNSSEC?
Provides cryptographic authentication of DNS zones.

Which of the following nameserver applications does not load all of its DNS zones upon startup? MyDNS

When operating within a cPanel & WHM server, which of the following indicates the best method to restart the DNS server from the command line? /scripts/restartsrv_named

The localhost_resolver view, if it exists on its own without any other views defined, would make your BIND/named server a ______________ nameserver. caching-only

Which of the following is one method that you can use, within the WHM interface, to repair a malformed DNS zone using a zone template? Reset a DNS Zone

In the  named.conf file, which section appears first by default? key

The recursion option in the named.conf defines whether your BIND server uses recursive behavior or __________ behavior when handling queries. iterative

Which of the following MySQL/MariaDB-related variables can be controlled via an option found within WHM's Tweak Setting interface? max_allowed_packet

What header information would be present in both email messages being exchanged between two cPanel servers but not appear in the Exim logs of either server? Message ID

When referencing the Apache error log, what does the highlighted portion of this log entry represent?

[Fri Sep 09 10:42:29.902022 2011] [core:error] [pid 35708:tid 4328636416] [client 72.15.99.187] File does not exist: /usr/local/apache2/htdocs/favicon.ico 
The name of the Apache module that triggered the error.

Which of the following options best describes the yellow-highlighted portion of the Apache access log entry shown below?
127.0.0.1 - frank [10/Oct/2000:13:55:36 -0700] "GET /apache_pb.gif HTTP/1.0" 200 2326
The HTTP status code.

Which of the following yum commands would remove, or uninstall, the mod_speling RPM?
yum remove ea-apache24-mod_speling

Which of the following best describes the difference between a process and a thread?
Threads can contain multiple processes, and the processes contained in the thread share its resources.

Which of the following options accurately describes an action one performs in WHM's EasyApache 4 interface?”
Install new PHP extensions for use in your active Apache/PHP environment.

Which of the following PHP handlers works on only one PHP version at a time?
DSO

Which interface can be used to set a virtual host's PHP version?
WHM only

Why is it suggested against using PHP DSO without mod_ruid2 or mpm_itk?
PHP DSO runs as the user nobody by default. In a shared hosting environment, this is a security issue.

During PHP requests, which of the following statements accurately describes how the DSO handler processes the request?
PHP handling operates internally by Apache's own processes.

In a cPanel & WHM environment operating with EasyApache 4, one could define an EasyApache profile as which of the following?
A collection of packages that can be provisioned.

When operating in a cPanel & WHM environment, which of the following files are used by Apache to define the PHP configuration?
/etc/apache2/conf.d/php.conf

Yudith manages a small web hosting company and has accidentally deleted a zone belonging to a cPanel account. The deleted zone did not contain any custom records.Which of the following interfaces in WHM should she use to recreate the zone?
WHM » DNS Functions » Add a DNS Zone.

In which of the following WHM interfaces would you enter the default nameservers for accounts that root creates?
WHM Home >> Server Configuration >> Basic WebHost Manager Setup

The following options found in the Exim Configuration Manager - Basic Editor interface in WHM enables the checking of DNS resolution to see if the sender's domain exists?
Sender Verification

As a WHM administrator, you receive the following email alert:
The hostname server.example.com resolves to the 10.0.2.5 IP address. It should resolve to the 10.0.3.5 IP address.
What is the most likely scenario to have caused this notification to be sent?
The hostname does not point to the main IP address on the server.

In what mode does cPanel create SPF records by default?
Development mode (non-production)

What happens when a domain with two NS records in its zone is queried for its NS records?
Both records are returned.

After installing cPanel & WHM in a new environment, what is the initial, default state of DNS clustering?
DNS clustering is initially disabled and must be manually enabled.

Which important configuration file would allow you to change important server options, such as enabling debug logging for BIND/named?
/etc/named.conf

Which of the following is a term that indicates a trait of the object described by the table, or can be otherwise referenced as a table column?
Field

Which of the following options indicate the correct number of characters that a MySQL 4.1 password contains before being updated to the current standard of 41 character-hashes?”
16 characters

Given the options below, which of these accurately indicate a point during WHM user interactions, which triggers the system to create grants for all pre-existing cPanel accounts, is based on the configurations set within the Additional MySQL Access Hosts interface?
These are only created from the individual cPanel account interfaces, and cannot be applied within WHM.

What language is used to add, remove, and view data in a MySQL/MariaDB database?
SQL

Which of the following database-related terms defines marking a table or row so that only one process can access it a time?”
Locking

MySQL Profiles can set up what kind of relationship between servers
1-to-1 (1:1) only

Which of the following files can be found in the /var/cpanel/databases directory in a cPanel & WHM environment?
none of these

What is the name of the executable responsible for the initial setup of database mapping, as well as any updates that occur between versions in a cPanel & WHM environment?
dbmaptool

What type of syntax is demonstrated in the following example, can also be found in some of cPanel's mapping-related files stored in the file system?MYSQL: 

  animals: 
    animals: 
      - GRANT USAGE ON *.* TO 'animals'@'localhost' IDENTIFIED BY PASSWORD '*75FE48658430441870C524D7ECB8F71EADFAEFD1'
      - GRANT ALL PRIVILEGES ON `birds`.* TO 'animals'@'localhost'
      - GRANT ALL PRIVILEGES ON `animals\_fish`.* TO 'animals'@'localhost'
PGSQL: {}
JSON

Which of the following SQL queries would be the most effective in identifying MySQL users that still have pre-4.1 passwords in use?
SELECT DISTINCT user FROM user WHERE length(password) < 41;

What is the role of the -f flag when used with the exiqgrep utility?
Select messages by message ID.

What header information would be present in both email messages being exchanged between two cPanel servers but not appear in the Exim logs of either server?
Exim ID

What does the line in the Exim log that contains the SpamAssassin warning signify?
The cPanel account that the message was scanned by.

Which of the following describes what is indicated by the use of the localuser router during a message's delivery, as seen in the Exim logs?
The message was delivered to a default (cPanel) account.

Of the following mailbox formats, which of these are supported for use in cPanel & WHM environments?
mdbox

Given the following, which option best describes an actual reason that the system may place a message into the Exim queue?
None of these options describe reasons for Exim to queue a message.

Within which of the following WHM interfaces would you look to determine why the system did not deliver an email message?
WHM Home » Email » Mail Delivery Reports

All mail from a specific user is neither delivered to the inbox nor bounced. When you check the WHM Home » Email » Mail Delivery Reports interface, you see a funnel-shaped icon next to the message. Which of the following options best describes what this probably indicates?
The message was likely caught in a user-level filter and deleted.

Which of the following mail diagnostics are available within the WHM interface, and can help you troubleshoot mail?
A diagnostic tool that performs a permission reset or a reset on an account’s mailbox files permissions on an account's mailbox files and folders.

If you receive a report that emails from a particular user on your server are not being delivered to the inbox or bounced back, and you see a green checkmark icon next to the message when you check the WHM Home » Email » Mail Delivery Reports interface, what is the most likely explanation for this icon?
That the message has been caught in a user-level filter and deleted.

What does it mean when a mail server "relays" its mail?
It is sending spam.

Given the following options, which accurately describe the Mail Troubleshooter interface's behavior, found in WHM?
It sends an actual test message, but only to local destinations on the server.

Given the following, which best describes an actual reason that the system may place a message into the Exim queue?
The load average on the server is above the delivery threshold.

































