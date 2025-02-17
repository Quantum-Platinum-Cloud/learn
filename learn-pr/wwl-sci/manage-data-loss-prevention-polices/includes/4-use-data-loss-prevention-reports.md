After you create data loss prevention policies, administrators need to verify and monitor the performance of their DLP policies in production. This is an important recurring task for an organization to ensure they stay compliant with policies while minimizing impact on user productivity. 

## Data loss prevention reports in the Microsoft Purview compliance portal

The Microsoft Purview compliance portal provides the following DLP reports that can be accessed in reports under organization data:

- DLP Policy Matches

- DLP Incidents

- DLP false positive overrides

The following table provides an overview for each DLP report.

| **Report**| **Report contains…**| **Report is used for…**| **Recommendation**|
| :--- | :--- | :--- | :--- |
| **DLP Policy Matches**| The count of DLP policy matches over time at a rule level, grouped by the available Microsoft 365 service locations. The report can be broken down by services, actions, or policies and get filtered by date, location, policy, or action. | Tune or refine your DLP policies as you run them in test mode. You can view the specific rule that matched the content.| The policy matches report is used for identifying matches with specific rules and fine-tuning DLP policies, to increase the accuracy of the policies matching a company's individual data shared regularly.|
| **DLP Incidents**| The count of DLP policy matches over time on item level, grouped by the available Microsoft 365 service locations. The report can be filtered by date, location, policy, or action. | Identify specific pieces of content that are problematic for your DLP policies.| The incidents report is used for identifying specific pieces of content that are problematic for your DLP policies and to identify groups of items that may require more protective actions.|
| **DLP false positives and overrides**| A count of user overrides and reported false positives. This report can be filtered by date, location, or policy.| Tune or refine your DLP policies by seeing which policies incur a high number of false positives.| The false positives and user overrides report should be used to identify the accuracy of the existing DLP policies, to be able to react fast when suddenly large numbers of faulty matches occur in a business impact.|

> [!TIP]
> All DLP reports can display data from the most recent four-month time period. The most recent data can take up to 24 hours to appear in the reports.

## Data loss prevention alert management dashboard

Reports provide a quick overview of DLP events and can inform about an organization's trends.  DLP policies can be configured to trigger an alert when the conditions are met. Use the incident report to investigate events.

The DLP alert management dashboard in the Microsoft Purview compliance portal can be used to show alerts of the following workloads:

- Exchange

- SharePoint

- OneDrive

- Teams

- Devices

The remediation of Microsoft Defender for Cloud Apps DLP alerts is done through the Defender for Cloud Apps dashboard.

## Data loss prevention alerts in the Microsoft Defender for Cloud Apps dashboard

You can also view a report for DLP alerts in the Defender for Cloud Apps Dashboard. This report shows the alerts and matches of all your Defender for Cloud Apps policies that are part of the DLP category. You can select each alert or match to gain information about:

- The type of sensitive information

- Location of the sensitive information

- The policy creating the alert

- The user triggering the policy match

- The actions that have been taken to secure the matched file

[ ![Alerts screen example.](../media/alerts-report-microsoft-cloud-app-security.png) ](../media/alerts-report-microsoft-cloud-app-security.png#lightbox)

Use the Defender for Cloud Apps DLP alerts report to view an overview of Defender for Cloud Apps policy alerts. Since policies created on the Defender for Cloud Apps side have different options and scopes compared to Defender for Cloud Apps policies created in the Microsoft Purview compliance portal, it's prudent to be aware of alerts in both dashboards.

