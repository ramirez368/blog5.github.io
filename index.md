---
layout: default
---


[Ldap and Active Directory how they interact](https://www.youtube.com/watch?v=QyhNaY5O468&t=1s).

[//]: #  There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

## What are the business benefits of RPA?
Robotic process automation streamlines workflows, which makes organizations more profitable, flexible, and responsive. It also increases employee satisfaction, engagement, and productivity by removing mundane tasks from their workdays.

RPA is noninvasive and can be rapidly implemented to accelerate digital transformation. And it’s ideal for automating workflows that involve legacy systems that lack APIs, virtual desktop infrastructures (VDIs), or database access. 



## LDAP Authentication:
![Ldap Authentication](https://api.softwarekeep.com/media/nimbus/helpcenter/LDAP_Authentification.png)

* _Anonymous authentication_: Grants client anonymous status to LDAP.
* _Unauthenticated authentication_: For logging purposes only, should not grant access to a client.
* _Name/Password authentication_: Grants access to the server based on the credentials supplied – simple user/pass authentication is not secure and is not suitable for authentication without confidentiality protection.

SASL authentication binds the LDAP server to another authentication mechanism, like Kerberos. The LDAP server uses the LDAP protocol to send an LDAP message to the other authorization service. That initiates a series of challenge response messages that result in either a successful authentication or a failure to authenticate.

It’s important to note that LDAP passes all of those messages in clear text by default, so anyone with a network sniffer can read the packets. You need to add TLS encryption or similar to keep your usernames and passwords safe.

### Why is RPA transformative?
RPA technology is changing how the world gets work done.

Software robots—instead of people—do repetitive and lower-value work, like logging into applications and systems, moving files and folders, extracting, copying, and inserting data, filling in forms, and completing routine analyses and reports. Advanced robots can even perform cognitive processes, like interpreting text, engaging in chats and conversations, understanding unstructured data, and applying advanced machine learning models to make complex decisions.

When robots do these types of repetitive, high-volume tasks, humans are freed to focus on the things they do best and enjoy more: innovating, collaborating, creating, and interacting with customers. Enterprises get a boost too: higher productivity, efficiency, and resilience. It’s no wonder that RPA is rewriting the story of work.


### LDAP vs. Active Directory
LDAP is a way of speaking to Active Directory.

LDAP is a protocol that many different directory services and access management solutions can understand.

The relationship between AD and LDAP is much like the relationship between Apache and HTTP:

* HTTP is a web protocol.
* Apache is a web server that uses the HTTP protocol.
* LDAP is a directory services protocol.
* Active Directory is a directory server that uses the LDAP protocol.
Occasionally you’ll hear someone say, “We don’t have Active Directory, but we have LDAP.” What they probably mean is that they have another product, such as OpenLDAP, which is an LDAP server.
It’s kind of like someone saying “We have HTTP” when they really meant “We have an Apache web server.”



![Table with Differences between LDAP and Active Directory ](https://ipwithease.com/wp-content/uploads/2020/06/LDAP-VS-AD-TABLE.jpg)

### What is an LDAP Query?
An LDAP query is a command that asks a directory service for some information. For instance, if you’d like to see which groups a particular user is a part of, you’d submit a query that looks like this:

(&(objectClass=user)(sAMAccountName=yourUserName)
(memberof=CN=YourGroup,OU=Users,DC=YourDomain,DC=com))

Beautiful syntax, huh? Not quite as simple as typing a web address into your browser. Feels like LISP.

Luckily, in most cases, you won’t need to write LDAP queries. To maintain your sanity, you’ll perform all your directory services tasks through a point-and-click management interface like Varonis DatAdvantage or perhaps using a command line shell like PowerShell that abstracts away the details of the raw LDAP protocol.

TL;DR: LDAP is a protocol, and Active Directory is a server. LDAP authenticates Active Directory – it’s a set of guidelines to send and receive information (like usernames and passwords) to Active Directory. Want to learn more? Get a 1:1 AD demo and learn how Varonis helps protect your Active Directory environment.


### I hope this was useful to how to setup Apache Server and being expose to more Linux


```
Thank you readers, and wait for next week blog
For Contact e-mail me at ramirez368@hotmail.com

```
