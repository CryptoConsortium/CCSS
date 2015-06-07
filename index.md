---
layout: default
---

CryptoCurrency Security Standard (CCSS) is a set of requirements for all information systems that make use of cryptocurrencies, including exchanges, web applications, and cryptocurrency storage solutions. By standardizing the techniques and methodologies used by systems around the globe, end-users will be able to easily make educated decisions about which products and services to use and with which companies they wish to align.

CCSS is designed to complement existing information security standards (i.e. ISO 27001:2013) by introducing guidance for security best practices with respect to cryptocurrencies such as Bitcoin. CCSS is not designed to substitute or replace these standards; in fact, following the CCSS to the letter while ignoring standards like ISO 27001:2013 will likely lead to compromise. CCSS is a cryptocurrency standard that augments standard information security practices. As with any standard, knowledgeable and experienced security professionals and/or auditors are necessary when implementing any information system to ensure coverage of all classes of attack as well as the appropriate handling of all potential risks.

# Overview

CCSS covers a list of 10 security aspects of an information system that stores, transacts with, or accepts cryptocurrencies. An information system is a collection of technologies (hardware and/or software), personnel, policies and procedures that work together to provide a secure environment. A security aspect is a discrete technique of securing one piece of an information system. The minimum value of all 10 aspects determines an information system’s overall score within three (3) levels of increasing security: Level I is the lowest and offers strong security measures, while Level III is the highest and offers the most comprehensive security.

These 10 aspects are organized into 2 domains that help structure the guidelines. A summary of the standard can be seen in the below example which depicts sample results after auditing Acme Exchange, a "Level I" system. You'll note that even though there are some aspects with scores in the Level II and Level III range, Acme Exchange is classified a Level I system overall since that is the lowest consistent grade across all aspects:

## Acme Exchange's CCSS Audit Results: ![img](/CCSS/images/CCSS Matrix.png)

# Scope
The CCSS covers controls that increase the security of the cryptocurrency portion of an information system, however it does not cover common standards and practices for increasing the cybersecurity of an information system. For this reason, CCSS should be considered as a separate set of recommendations that are applied overtop standard security practices in other domains including business continuity, disaster recovery, network intrusion prevention, physical security, and vulnerability management.

# Applicability

The CCSS applies to any information system that makes use of cryptocurrencies. This includes (but is not limited to):
* Cryptocurrency Exchanges (i.e. Information Systems that allow its users to exchange cryptocurrencies for other forms of money)
* Cryptocurrency Marketplaces (i.e. Information Systems that allow its users to exchange cryptocurrencies for other goods and services)
* Cryptocurrency Games (i.e. Information Systems that allow users to gamble their cryptocurrencies for a chance at winning more)
* Cryptocurrency Processors (i.e. Information Systems that automate the acceptance of cryptocurrencies for payment)
* Cryptocurrency Storage (i.e. Information Systems that facilitate the receipt and transmission of cryptocurrencies amongst other actors)
* Any Information System that handles cryptocurrencies as part of its business logic.

# Levels

CCSS is broken into three (3) levels of increasing security. Details of these are outlined in this section.

## Level I

An information system that has achieved Level I security has proven by way of audit that they protect their information assets with strong levels of security. Most risks to the system’s information assets have been addressed by controls that meet industry guidelines. While this is the lowest level within CCSS, it still represents strong security.

## Level II

An information system that has achieved Level II security has proven by way of audit that they exceed strong levels of security with additional enhanced controls. In addition to covering most risks to the information system’s assets, the use of decentralized security technologies such as multiple signatures have been employed which exceed industry guidelines and provide redundancy if any one key or person becomes unavailable or compromised.

## Level III

An information system that has achieved Level III security has proven by way of audit that they exceed enhanced levels of security with formalized policies and procedures that are enforced at every step within their business processes. Multiple actors are required for all critical actions, advanced authentication mechanisms ensure authenticity of all data, and assets are distributed geographically and organizationally in such a way to be resilient against compromise of any person or organization.


# This Repository

This repository is meant to operate as a collaborative document. Wherever possible, the details of the standard have been separated from the design elements to allow for both to easily evolve independantly. Your contirbution to either is encouraged. 

See the _data directory for discussion on the standard.

See the Jekyll project for more information regarding the structure/design of this static site. 
