---
title: "Struggle in Creating Nessus/Tenable Custom Audit Compliance File"
date: "2022-08-16"
layout: single
categories: VAPT
permalink : VAPT/customcomplianceaudit

---

As a Security Engineer or Penetration Tester that performs VA/Compliance Scan for their assets hardening, I believe it is general known that we can utilise Nessus Scanner and Tenable.sc to do Compliance scan.
Either DISA STIG or CIS Benchmark are the usual guidelines that the majority of people followed while conducting a compliance audit of their server. You can learn more about other common compliance standard rules and guides by visiting this [LINK](https://docs.tenable.com/nessus/compliancechecksreference/Content/ComplianceStandards.htm).
Tenable scanning template usually alreaady came with the most recent .audit file. All the audit files for Tenable are available [HERE](https://www.tenable.com/audits) for download.

You will need to create your own .audit file based on the needs of the organisation at some point. Custom .audit files are typically created when a policy value differs from a readily available template or when an additional compliance check is required.
My previous experience has taught me that creating my own custom audit file can be difficult. The syntax of the .audit file must be understood in the first place; please read it in detail [HERE](https://docs.tenable.com/nessus/compliancechecksreference/Content/PDF/NessusComplianceChecksReference.pdf) and [HERE](https://docs.tenable.com/nessus/compliancechecksreference/Content/ComplianceCheckTypes.htm). 
Understanding the syntax is essential for determining which parts of the .audit file need to be edited and added.

When I create my own custom audit file for compliance scanning, I always get "syntax error." Going through line by line to find the incorrect syntax is not easy in my experience; in the end, it is easier for me to redo the entire thing.
I did find a way to validate through Tenable Community. You can find more information about auditing file syntax errors before uploading to the scanner [HERE](https://community.tenable.com/s/question/0D53a00007StplcCAB/how-to-validate-audit-file-syntax) and [HERE](https://community.tenable.com/s/article/How-do-I-know-if-my-audit-file-is-actually-checking-files).

However, for those who want to get started, Tenable has introduced an IDE for compliance custom audit files via Visual Code Studio beginning 1 August 2022.
More information can be found [HERE](https://community.tenable.com/s/article/Tenable-AuditLang-Extension-for-Visual-Studio-Code), where they also explain how to set it up.

There may be a second part to this to show you how to troubleshoot everything. Please leave a comment if you have any questions. Don't be SHY :)
