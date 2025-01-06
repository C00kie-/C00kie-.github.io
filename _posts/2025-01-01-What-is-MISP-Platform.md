---
title: "What is the MISP Platform"
categories: [MISP, CTI, opensource]
tags: [MISP, MISP objects, CTI]
---


### Hello MISP

MISP is an opensource threat intelligence platform that plays a crucial role cyber threat intelligence sharing, by enabling the collection, storage, distribution, and sharing of cyber threat information.

Developed as a community-driven project, MISP has evolved from its initial focus on malware indicators to encompass a broader range of threat intelligence, including fraud and vulnerability information. And its usage now extends to fields not directly involved in cybersecurity, such as investigative journalism and OSINT.

### Some MISP features

The platform has many features, just to list a few: standardization, collaboration, correlation engines, automation and third parties tools integration, as well as synchronization. Its originality lies in its information distribution model, where the sharing of information among organizations is layered by groups and communities, and sharing protocols managed by MISP instances themselves.

MISP offer the possibility to standardize data sharing. It uses common formats for representing information, facilitating easier sharing and understanding of cyber threats. In terms of collaboration, the platform allows multiple individuals and organizations to contribute to and access shared threat information, enabling collaborative threat analysis.

![MISP-automation](/assets/img/misp-automation.png)

### Automation

MISP can automatically correlate related events, linking various indicators such as malware files, hashes, and email addresses associated with specific threats. To support both automation and the management of data imports, MISP supports integration with other security tools and platforms, allowing for seamless information sharing and automation in threat intelligence workflows.

The architecture is designed to facilitate flexible and secure threat intelligence sharing through a system of events, feeds, groups, and users (the MISP data model).

Its structure ensures that the scope of sharing is controlled and secure, offering distinct options for the distribution of events and their related attributes. It is also highly adaptable and analysts can derive the model to their own needs, by modifying or creating new tags and ways of encoding the information they receive.

### Synchronization

One of the most powerful features of MISP is the synchronization between MISP instances. Synchronization allows two or more MISP servers to exchange events, attributes, and other relevant information through pull and push mechanisms (to receive data or to send data) among organizations using MISP, or withing the same organization. These processes are also customizable for each instance and any setup can be easily changed within the platform itself.

But keep in mind this is a very short tour of MISP features. The platform is evolving fast. You can find the full list of its current features here and the features requested by the community on Github.

### Who uses MISP today?

MISP’s versatility allows it to be used across various sectors. Broadly used in the financial sector, MISP is also intensively used by government agencies and public entities: national cybersecurity agencies and law enforcement use MISP to share threat information with other entities.

Across private sectors and research communities, cybersecurity researchers and academics use MISP to share findings about new attack techniques and vulnerabilities.

MISP facilitates the creation of sharing communities which are networks of individuals and organizations that share threat intelligence. These communities consist of trusted partners or peers facing similar types of threats, which helps to improve the relevance of shared information.

Each point deserves a full post in itself. Next time, we will explore MISP sharing model.

Stay posted!

**Sources:**

MISP Project: [https://www.misp-project.org](https://www.misp-project.org)

[https://github.com/MISP/](https://github.com/MISP/)

[MISP support and services at cubessa](www.cubessa.io/misp)