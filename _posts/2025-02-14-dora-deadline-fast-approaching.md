---
title: "Deadline for reporting DORA Registers of Information is fast approaching"
date: 2025-02-14
image: /assets/images/golden-padlock.jpg
author: Olive Octagon
---

The requirement to comply with the Digital Operational Resilience Act (DORA) came into effect on 17 January 2025, and the first reporting requirement is the Register of Information as at 31 March 2025 which is to be submitted to national regulators shortly thereafter.

DORA is a European Union regulation designed to enhance the digital operational resilience of financial entities within the EU. Its primary goal is to ensure that these institutions can effectively prevent, withstand, and recover from information and communication technology (ICT) disruptions and cyber threats.

Some more information on DORA is available at the end of this article, but we're here primarily to talk about Register of Information reporting.

> If you know what the DORA Register of Information is all about and just need some software to help you then you can go straight to [https://www.oliveoctagon.com/dora/](https://www.oliveoctagon.com/dora/).

## Reporting overview

When is comes to reporting, companies in scope of DORA need to:

- Maintain records on their ICT service providers
- Report information on their ICT service providers to their national regulator (this is the "Register of Information")
- Report on Major ICT-related Incidents and Significant Cyber Threats

The Register of Information needs to be reported as at 31 March 2025 and then annually from 31 December 2025 onwards.

## What needs to be reported in the Register of Information

The best source of information about what you need to report is the implementing technical standard ([https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=OJ:L_202402956](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=OJ:L_202402956)), but here's a summary of the 15 templates required:

- B_01.01 – Entity maintaining the register of information
- B_01.02 – List of entities within the scope of consolidation
- B_01.03 – List of branches
- B_02.01 – Contractual arrangements (general information)
- B_02.02 – Contractual arrangements (specific information)
- B_02.03 – List of intra-group contractual arrangements
- B_03.01 – Entities signing the contractual arrangements for receiving ICT service(s) or on behalf of the entities making use of the ICT service(s)
- B_03.02 – ICT third-party service providers signing the contractual arrangements for providing ICT service(s)
- B_03.03 – Entities signing the contractual arrangements for providing ICT service(s) to other entities within the scope of consolidation
- B_04.01 – Entities making use of the ICT services
- B_05.01 – ICT third-party service providers
- B_05.02 – ICT service supply chain
- B_06.01 – Functions identification (i.e. the functions of the entity making use of the ICT services)
- B_07.01 – Assessments of the ICT services
- B_99.01 – Definitions from entities making use of the ICT Services

These templates are all structured as tables (i.e. data in columns with a new row for each entry you need to report).

## How is the information to be reported?

The templates listed above need to be reported in a format known as XBRL-CSV. This is a specifically structured zip file containing some basic information in a mix of JSON and CSV files, and then a CSV file for each template.

![Contents of a DORA Register of Information zip package](/assets/images/dora-package-contents.png)

There are some intricacies in how these files are put together, so we'd recommend getting some software to do this for you to ensure the package you submit is valid.

## How is the final zip package submitted and what happens?

Each national regulator's process for submitting information will be slightly different, but in general the national regulator will have a portal where you log in and upload your file.

Once you have uploaded your file it will be subjected to a series of validation tests.

Firstly, the structure of the zip package will be inspected to ensure it meets requirements and that all the templates have been reported.

Secondly, a series of data validation checks will be run to ensure things like:

- Mandatory data has been reported
- Numbers and dates are formatted properly
- Appropriate dropdown / closed list items have been chosen
- LEI codes are valid
- Cross-checks between templates to make sure the data being reported is internally consistent

If you fail any of the validations it is likely that the national regulator will ask you to resubmit the data, so again we'd recommend getting some software that can run these validations for you before you submit your file.

## 2024 Register of Information Dry Run exercise

In mid-2024, The European Supervisory Authorities (ESAs) conducted a Dry Run exercise with around 1,000 entities submitting their Register of Information data.

Information and materials relating to the dry run exercise can still be found on the European Banking Authority (EBA) website: [https://www.eba.europa.eu/activities/direct-supervision-and-oversight/digital-operational-resilience-act/preparation-dora-application](https://www.eba.europa.eu/activities/direct-supervision-and-oversight/digital-operational-resilience-act/preparation-dora-application).

For the Dry Run exercise the ESAs made available a spreadsheet with some code in it to create a zip package for you. The ESAs have stated that this won't be made available for the updated templates that need to be reported from 31 March 2025, and so any companies wishing to use Microsoft Excel as their reporting data collation tool will need to find another way of converting this to the final zip package.

The outcome of the Dry Run exercise was generally very positive, but the number of files passing all the validations was low, and the number of validations failed varied significantly by entity. Compliance with validation tests will clearly be a key area of focus for the ESAs in future.

## What to do now

Here's a list of what we think companies in scope of DORA should be doing now:

1. Get yourself some software to report the Register of Information data. This could already be generated for you from whatever tool you use to maintain your data in house, but if not then find a software provider that lets you collate your information and generate the reporting package.
2. Make sure your chosen solution can run the validation tests and report any problems to you.
3. Contact all of the ICT service providers you need to include in your Register of Information and make sure they have LEI codes. EU-based ICT service providers can also be reported using an EU-ID, but there's no real excuse for not having an LEI code - they're easy, cheap and quick to get.

## What's Olive Octagon's role in all of this?

Well apart from just being really generous and wanting to give you clear information of what you need to be doing for DORA Register of Information reporting, we of course have an ulterior motive...

Olive Octagon has a very straightforward software solution for reporting DORA Register of Information data. Here's how it basically works:

1. Download a set of Excel templates
2. Fill them in
3. Use our web application to validate and convert the templates to the final reporting package

If you already have a reporting package and you just want to run validation tests on it then you can do that too.

### Why us?

Our development team has been building software for businesses and regulatory reporting for a long time. We're XBRL specialists and have extensive experience of XBRL reporting having built Solvency II XBRL reporting software since Solvency II reporting came around in 2016.

### Worried about data security?

Don't be. Our web application runs entirely within your browser, so no data leaves your computer during validation or conversion.

For more information, visit [https://www.oliveoctagon.com/dora/](https://www.oliveoctagon.com/dora/)

## More information on DORA

Hopefully by now you're aware of what DORA is all about, but below is some summary information and links to get you caught up.

### Who is in scope of DORA?

DORA applies to a wide range of financial entities, including:

- Credit institutions
- Payment institutions
- Electronic money institutions
- Investment firms
- Crypto-asset service providers
- Insurance and reinsurance undertakings
- Management companies
- Managers of alternative investment funds
- Trading venues
- Central securities depositories
- Central counterparties
- Crowdfunding service providers
- Administrators of critical benchmarks
- Data reporting service providers
- Securitization repositories
- Trade repositories
- ICT third-party service providers

### What are the key objectives of DORA?

1. **Unified Framework:** DORA establishes a harmonized regulatory framework across EU member states, addressing ICT risk management, incident reporting, and oversight of third-party service providers.
2. **Enhanced ICT Risk Management:** Financial entities are required to implement comprehensive ICT risk management frameworks, encompassing regular risk assessments, mitigation strategies, and incident response plans.
3. **Incident Reporting:** DORA standardizes the process for reporting ICT-related incidents, mandating that institutions establish systems to monitor, detect, and analyze significant incidents, and report them to relevant authorities.
4. **Resilience Testing:** Organizations must conduct periodic testing to evaluate their cyber vulnerabilities and responses, ensuring they can survive cyber threats and improve practices based on test results.
5. **Third-Party Risk Management:** DORA strengthens the oversight of critical third-party providers, such as cloud services, by requiring detailed contracts, ongoing due diligence, and robust offboarding processes to ensure that third-party relationships don’t compromise operational resilience.

### Further reading

If you bookmark one page for DORA information, make it this one: [https://www.eba.europa.eu/activities/direct-supervision-and-oversight/digital-operational-resilience-act](https://www.eba.europa.eu/activities/direct-supervision-and-oversight/digital-operational-resilience-act)

The page "Preparations for reporting of DORA registers of information" can be found one the EBA website here: [https://www.eba.europa.eu/activities/direct-supervision-and-oversight/digital-operational-resilience-act/preparation-dora-application](https://www.eba.europa.eu/activities/direct-supervision-and-oversight/digital-operational-resilience-act/preparation-dora-application)

The Central Bank of Ireland has a great resource for finding out more about DORA here: [https://www.centralbank.ie/regulation/digital-operational-resilience-act-dora/communications-and-publications](https://www.centralbank.ie/regulation/digital-operational-resilience-act-dora/communications-and-publications)

In particular, the Central Bank of Ireland's FAQs should address most questions you have, even if you don't report to them: [https://www.centralbank.ie/regulation/digital-operational-resilience-act-dora/dora---frequently-asked-questions](https://www.centralbank.ie/regulation/digital-operational-resilience-act-dora/dora---frequently-asked-questions)
