---
title: "Greedy for SQL Injection - How we found them on scale"
date: 2022-12-19
categories:
  - blog
---

Slides and code used to present the research in which we implemented custom templates for Semgrep with the purpose of detecting SQL Injection from the analysis of Wordpress plugin source code.

[Github Repository Link](https://github.com/mrnfrancesco/GreedyForSQLi){:target="_blank"}

## CVEs Found

| Name           | Field            | Vulnerability           | Proof of Concept(PoC)                                                               
|----------------|------------------|-------------------------|-------------------------------------------------------------------------------------
| CVE-2022-3241  | Web Application  | SQL Injection(SQLi)     | [Link 2 PoC](https://wpscan.com/vulnerability/a995dd67-43fc-4087-a7f1-5db57f4c828c){:target="_blank"}
| CVE-2022-3860  | Web Application  | SQL Injection(SQLi)     | [Link 2 PoC](https://wpscan.com/vulnerability/d99ce21f-fbb6-429c-aa3b-19c4a5eb7557){:target="_blank"}
| CVE-2023-4724  | Web Application  | SQL Injection(SQLi)     | [Link 2 PoC](https://www.unlock-security.it/it/security-advisory/cve-2023-4724-cve-2023-5882-wp-all-export/){:target="_blank"}
