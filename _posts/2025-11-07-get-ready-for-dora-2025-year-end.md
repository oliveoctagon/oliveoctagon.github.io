---
layout: post
title: "DORA Year End 2025 Reporting"
date: 2025-11-07
image: /assets/images/padlocks-snow.jpg
author: Ben Joyce FIA
description: Things to think about when getting ready for DORA Reporting as at 31 December 2025

ogtype: article
ogtitle: DORA Year End 2025 Reporting
ogdescription: What you need to know, and how to get ready.
ogimage: /assets/images/padlocks-snow.jpg
ogimagealt: Pink and purple padlocks fixed to a railing with a dusting of snow on top.
---

The second DORA Reporting date (31&nbsp;December 2025) is approaching. In this article we consider what companies should be doing to prepare, including lessons learned from the 31&nbsp;March 2025 reporting feedback.

What's changing for year end 2025?
---

Nothing essentially. The reporting format is the same and the taxonomy to use is still [Reporting Framework v4.0](https://www.eba.europa.eu/risk-and-data-analysis/reporting/reporting-frameworks/reporting-framework-40), with no changes expected until [v4.3](https://www.eba.europa.eu/risk-and-data-analysis/reporting/reporting-frameworks/reporting-framework-43) is released, which is expected to apply from Q4 2026.

There have been some minor relaxations in the ZIP package structure, most notably that it is now possible to omit CSV files for tables not being reported whereas previously files with just a header row had to be included in the package. You still need to report positive filing indicators for these tables (although the reason for this is unclear, contrary to normal practice, and contrary even to the EBA filing rules, but that's just the way it is for now).

What did we learn from Q1 2025 reporting?
---

On 16&nbsp;April 2025, the ESAs published ["Observations from reporting of RoI to the ESAs. Key common issues identified"](https://eba.europa.eu/sites/default/files/2025-04/717e7e5f-14ac-45c6-b336-b0aac6a9062a/Observations%20from%20RoI%20reporting%20testing%20-%20common%20issues%20-%20April%202025%20%281%29.pdf). In this document, the key issues encountered in Q1 2025 reporting were highlighted, and the can be summarised as:

- Invalid report package structure
  - Entity ID and/or reporting date not matching the ZIP package file name
  - Missing table CSV files or CSV files with an upper-case 'B' in the name
  - Filing indicators set to 'false' (again, we don't understand why this isn't acceptable)
  - Headers in CSV files that do not appear in the taxonomy (or more likely were upper-case instead of lower-case)
- Inconsistent data
  - The tables link together using 'key columns', and so if you report an entity with a given LEI code on one table then that same LEI code must appear in other tables
  - Duplicated rows in tables (i.e. duplicated 'key columns')
- Invalid data
  - Invalid LEI codes (reported codes must appear in the [GLEIF database](https://search.gleif.org/#/search/simpleSearch=))
  - Invalid EUID codes (these are harder for reporters to check so care must be taken when completing the data)
  - Missing mandatory fields

The above issues can generally be highlighted early to reporter by running the a high-quality set of validation tests on reporting packages before submission.

What should companies do to prepare for year end 2025?
---

1. If you haven't already got some software to help with the reporting process and you're instead producing the packages in-house, then you will likely benefit from buying a solution to help with at least part of the process.

2. Review the above learning points to make sure you have a process to identify and remediate these issues before submission. If you have a software provider then make sure the software is capable of reporting all of these issues to you.

3. DORA RoI data generally doesn't change very frequently, so given the tight deadline in January 2026 when reporting teams are likely to be busy with other things, it is recommended that companies start getting their data together and their packages validated this side of Christmas so that only minor changes are needed in the new year.

Should companies use Olive Octagon's DORA reporting solution?
---

Well, we think that's a great idea, but we admit we are somewhat biased.

Olive Octagon's [DORA reporting solution](https://www.oliveoctagon.com/products/dora/) allows companies to convert a simple Excel workbook of data into the required package format and report all of the issues in either the validations or the learning points highlighted above.

Even if companies have an existing solution, Olive Octagon's package validation tool can be used as either an independent check or as the validation system for those companies producing their own reporting packages.

And at €600, it's not a bad idea to have a back-up solution in place should you have any issues with your current reporting approach.