---
title: "What's inside a MISP event?"
categories: [Opensource, MISP]
tags: [Opensource, MISP data model, outline, MISP object]
---

## Let's visualize the MISP data model within a MISP event
To simplify understanding the MISP data model, we've divided its approach into two main layers: a data layer and a context layer. Let's see this in the context of a MISP event.

## Data layer

The data layer consists of three key components:

**1. Events**
- Primary containers in MISP
- Group related information together

**2. Attributes**
- Individual data points (e.g., IP addresses, file hashes)
- Have a type (e.g., MD5, URL) and category (e.g., Payload delivery)

**3. Objects**
- Group related attributes
- Represent complex structures (e.g., email with sender, subject, and attachment)
- There are templates for MISP objects

## Context layer

While intertwined with the data Layer in practice, a context layer adds crucial information to the event:

**Tags and Taxonomies**
- Provide additional context
- Include free tags, standardized taxonomies, and complex galaxies

## Analysis

The analysis component of an event regroup the dynamic elements. Dynamic means that they can change. Ex: a correlation reveals new indicators, which motivates a new tag to be attached. 

**Correlation**
- Automatically links related attributes across events

**The event timeline**
- Various timestamps provide temporal context

**The event graph**
- To visualize relationships between entities contained in the event

**Pivots**
- Allow analysts to navigate between related events and attributes

**Sightings**
- Record when data points are observed
- Add time dimension to threat intelligence
- Confirm validity of attributes or mark false positives
- Support expiration of indicators
- Can be contributed via UI, API, or automated tools

**Event Reports**
- Narrative descriptions
- Provide context to technical information

**Analyst Notes**
- To describe information, add annotations
- Is attached to the target UUID 
 
**Proposals**
- To correct errors

## Illustrations 

### MISP event

![misp-event.png](./assets/img/misp-event.png)

### An example: Phishing URL findings** 

![phishing-url-findings.png](./assets/img/phishing-url-findings.png)


Pauline Bourmeau

visit: [MISP Project](https://www.misp-project.org/)

[Cubessa](https://www.linkedin.com/company/cubessa/)

