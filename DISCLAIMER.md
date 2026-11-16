# ⚠️ Disclaimer & Liability Limitation

**Repository:** `n8n-connecteam-field-checklist-hubspot-deal-updater`
**Author:** DH Robin (dhRobin Systems)
**Last updated:** November 2026

Use at your own risk. The code, workflows, and scripts in this repository (`n8n-connecteam-field-checklist-hubspot-deal-updater`) are provided for educational and architectural demonstration purposes.

* **No Liability:** The author and dhRobin Systems accept no responsibility or liability for any direct, indirect, incidental, or consequential damages that result from using, misusing, or deploying these scripts. That includes, without limitation, checklists attached to the wrong deal, deal stages advanced too early, too late or not at all, invoices issued on incomplete work, safety findings that are missed or not escalated, lost or expired photos and signatures, lost revenue, API charges, and any record created or changed in a connected system.

* **No Warranty:** All software, n8n JSON blueprints and JavaScript modules are provided "AS IS", without warranty of any kind, express or implied. This includes, but is not limited to, warranties of merchantability, fitness for a particular purpose, and non-infringement. The matching scores, address normalisation, checklist pass rules and redaction patterns are illustrative defaults and are not guaranteed to be correct for your data.

* **Production Testing Required:** Always test thoroughly in an isolated staging environment, such as a HubSpot developer test account or sandbox, a test Connecteam form and a test Slack channel, with `SANDBOX_MODE=true` and `DRY_RUN=true` enabled, before you connect live Connecteam, HubSpot or Slack credentials. Review every automatic stage change before you invoice from it.

* **Not a Safety System:** This workflow is not a safety management system. It doesn't stop work, notify authorities or replace your safety procedures, supervisors or incident reporting. A safety finding must be handled by the people responsible on site, whether or not an alert arrives.

* **Third-Party APIs & Compliance:** You alone are responsible for complying with the terms of service, rate limits, data privacy regulations (GDPR/CCPA), employment, employee-monitoring and workplace-safety rules, and security policies of Connecteam, HubSpot, Slack and any connected services. That includes telling field staff and customers how checklist answers, photos, locations and signatures are shared and stored, restricting who can see them in HubSpot, n8n executions and alert channels, and reviewing every automatically created or updated record.

* **No Affiliation:** This project is independent. It is not affiliated with, endorsed by, or sponsored by Connecteam, HubSpot, Inc., Slack Technologies, LLC, Salesforce, Inc., or n8n GmbH. All product names and trademarks belong to their respective owners and are used only to describe compatibility.

* **Fictional Sample Data:** All names, phone numbers (from the 555-01xx fiction range), addresses, job numbers, checklist answers, form and question IDs, media URLs, record IDs and secrets in the pinned sample data and documentation are fictional and exist only for testing. Any resemblance to real people or organisations is coincidental. Placeholder values such as `YOUR_CONNECTEAM_WEBHOOK_SECRET`, `YOUR_CONNECTEAM_API_KEY`, `YOUR_HUBSPOT_PRIVATE_APP_TOKEN`, `YOUR_HUBSPOT_PORTAL_ID` and `YOUR_SLACK_WEBHOOK_URL` must be replaced with your own values, which you keep in environment variables or n8n credentials.

* **Not Professional Advice:** Nothing in this repository is legal, privacy, safety, accounting or compliance advice. Consult qualified professionals for decisions in those areas.

## Open-Source License Notice

This project is released under the MIT License. You may use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the software, subject to the conditions in [LICENSE](./LICENSE). The MIT License's own warranty disclaimer and limitation of liability apply in addition to this document. If the two conflict, the terms more protective of the author apply to the extent permitted by law.

---

Full text: DISCLAIMER.md · Licensed under the MIT License. License: MIT © 2026 DH Robin (dhRobin Systems) · Provided as-is, see the disclaimer.
