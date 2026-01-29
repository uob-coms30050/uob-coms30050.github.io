---
layout: default
title: Lab 2
---

[Home](../index) \| [Assessment Information](../assessment-information) \| [Refresher](../refresher) \| [Blackboard Page](https://www.ole.bris.ac.uk/ultra/courses/_264181_1/outline) \| [Blackboard Forum](https://www.ole.bris.ac.uk/ultra/courses/_264181_1/engagement) \| [Unit Catalogue](https://upc.bristol.ac.uk/unit-programme-catalogue/UnitDetails.jsa?ayrCode=25%2F26&unitCode=COMS30050)

[Data Projects](../data-projects)
---

# Lab 2: Exploring Data Privacy and Ethics

This lab builds on the lectures on data privacy and data ethics and will involve understanding and discussing privacy and ethics issues with datasets for data projects.  This is also an opportunity for you all to start thinking about what dataset you would want to work with for the coursework and find groupmates with similar interests.

## Before the Lab

To prepare for the lab session, revisit Week #14 lectures and familiarise yourself with the datasets that we will use for the coursework *(datasets to be finalised)*. 
- Lecture slides: [Data Privacy](https://www.ole.bris.ac.uk/bbcswebdav/courses/COMS30050_2025_TB-2/lectures/L2-1-data-privacy.pdf); [Data Ethics](https://www.ole.bris.ac.uk/bbcswebdav/courses/COMS30050_2025_TB-2/lectures/L2-2-data-ethics.pdf)
- Description of the datasets is under [Data Projects](../data-projects) 

It is completely understandable that you may not be able to go through all datasets before the lab. 
Skim through the list of projects and datasets, and try to go through one or two datasets that look interesting to you in more detail. 
Think about privacy and ethics concerns that may arise with those datasets.

Note that some projects may involve creating a dataset. For those datasets, you can make assumptions during the lab. The data projects list is still evolving; some projects may be added or deleted.

## Lab Task and Padlets

*Task tldr:* revisit the slides; look at the datasets individually; think about privacy (attributes and sensitivity; dislosure type; attacks; anonymity) and ethics (implications); post your findings on the padlet; discuss.

#### Padlets

- Dataset 1: <https://padlet.com/uob/ads-2025-26-data-privacy-and-ethics-lab-dataset-1-2u2w9zsi9zmi14fn>
- Dataset 2: <https://padlet.com/uob/ads-2025-26-data-privacy-and-ethics-lab-dataset-2-obkproa4mfig0xsa>
- Dataset 3: <https://padlet.com/uob/ads-2025-26-data-privacy-and-ethics-lab-dataset-3-vxvpenljjc5q6yor>
- Dataset 4: <https://padlet.com/uob/ads-2025-26-data-privacy-and-ethics-lab-dataset-4-6v135wi2unrzkppc>
- Dataset 5: <https://padlet.com/uob/ads-2025-26-data-privacy-and-ethics-lab-dataset-5-dtpxql6glfx98kzq>
- Dataset 6: <https://padlet.com/uob/ads-2025-26-data-privacy-and-ethics-lab-dataset-6-4i0wb332kgj9lqps>
- Dataset 7: <https://padlet.com/uob/ads-2025-26-data-privacy-and-ethics-lab-dataset-7-6nukyzrjghty35oq>
- Dataset 8: <https://padlet.com/uob/ads-2025-26-data-privacy-and-ethics-lab-dataset-8-xk9svl0oodq7eu4u>


## Guidance on Lab Tasks

### How to start

- Open the data privacy and data ethics slide decks
- Open a dataset. Look at the format and the attributes
 
### Possible concerns when data is considered on its own

- Is the data anonymized or does it contain any personally identifying information (PII)?
- Are there any attributes that are vulnerable or sensitive? Look for identifiers (for instance, name and passport number) and quasi-identifiers (for instance, age and gender)
  - Look if the attributes are presented in a raw format or a range format (for instance, age = 21 or age-range = 20-29
  - Classify attributes as confidential (or sensitive) or non-confidential (non-sensitive) attributes
- Think about disclosure type:
  - Attribute disclosure
  - Identity disclosure
  - Membership disclosure
- Think about what kind of attacks that could possible:
  - External
  - Internal
  - Dominance
- Is the data represented in an aggregated form or does it contain actual numbers? For example, date of birth or age? age or age range?
  - Think about anonymity:
    - k-anonymity
      - What is the k? How could we make it k-anonymous?
    - l-diversity
    - t-closeness

### Possible concerns when this data is merged with some other information 

- Merged with some other datasets (recall the example from lecture on anonymised health data combined with voter database)
- General knowledge (some information is general knowledge; think of concerns when this knowledge is combined with anonymised data)

### Issues with the dataset when the data is put to use?

- Consider use cases or applications of the dataset such as what new product features to introduce, who to hire, or whose loan application to approve
  - Is the data representative all stakeholders?
