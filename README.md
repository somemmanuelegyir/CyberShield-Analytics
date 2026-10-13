CyberShield Analytics

Security Log Analysis Using Python

Project Overview

CyberShield Analytics is a beginner cybersecurity data analysis project that uses simulated authentication logs to identify repeated failed login attempts and patterns that may require further investigation.

The project combines Python-based data analysis, visualization, and basic rule-based security alerting.

Project Objectives

- Analyze successful and failed login attempts.
- Calculate login failure rates.
- Identify user accounts with repeated failed logins.
- Analyze failed attempts by source IP address.
- Flag patterns that meet a configurable review threshold.
- Visualize findings and generate an automated security report.

Tools and Technologies

- Python
- Pandas
- Matplotlib
- Google Colab
- Jupyter Notebook

Analysis and Visualizations

- Login success and failure statistics.
- Failed login counts by user account.
- Failed login counts by source IP address.
- Rule-based alerts using a threshold of five failed attempts.
- Bar charts, a time-series line chart, and pie charts.
- Automated security interpretation and reporting.

Key Findings

The simulated dataset contains 20 login events:

- Successful logins: 10
- Failed logins: 10
- Login failure rate: 50%
- User with the most failed attempts: U002, with 7
- Source IP with the most failed attempts: 192.0.2.20, with 7

Security Recommendations

Repeated failed login attempts should be reviewed to determine whether they result from legitimate user errors, misconfigured applications, or potentially suspicious activity. Examine relevant authentication logs before drawing conclusions.

Limitations

This project uses a small, simulated dataset for educational purposes. The results do not establish that a real cyberattack occurred. The five-attempt threshold is a demonstration rule, not a universal security standard.

The IP addresses use the documentation-only range "192.0.2.0/24", rather than identifying real attackers.

Future Improvements

- Develop an interactive security dashboard.
- Analyze larger authentication datasets.
- Add time-window-based detection rules.
- Improve alert prioritization and reporting.
- Test the analysis with suitable, authorized security log datasets.

Author

Som Emmanuel Egyir

Interests: Data Analysis | Cybersecurity | AI | Technology

Project Status

Core analysis and visualizations completed. Dashboard development planned.
