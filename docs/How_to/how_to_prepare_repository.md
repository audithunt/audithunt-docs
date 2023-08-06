---
sidebar_position: 1
---

# How to preparing repository for Audit?

1. Make Your Repository Public

Audit Hunt relies on community-driven efforts, and auditors must be able to access and review your smart contract's source code.

- Navigate to your GitHub repository.
- Click on **Settings**.
- In the **Options** tab, scroll down to the Danger Zone section.
- Click on **Change visibility**.
Choose **Public** and follow the prompts to make your repository publicly accessible.

2. Set Up the Audit Hunt Issue Template

Using a standardized issue template ensures that all audit submissions are consistent, making it easier for you to review and address them. Audit Hunt provides a template to ensure this consistency.

How to Add the Template:

- Visit [Audit Hunt's issue template](https://github.com/audithunt/Issue-Template/blob/main/.github/ISSUE_TEMPLATE/audit-hunt.md) and click on the Raw button. Copy all the content.
- Go to your GitHub repository and click on the **Settings** tab.
- In General tab find section **Features** and click on **Issues**.
- If not already activated, click on **Set up templates**.
- Click on **Add template** and choose **Custom template**.
- Clicl **Preview and edit**.
- Paste the content you copied from the Audit Hunt issue template.
- At this stage make sure to add "audithunt" label to your template. 
It is important for your submissions to be recognized and indexed by the Audit Hunt platform, every audit issue must be tagged with the "audithunt" label.
- Ensure you name the template something recognizable, like Audit Hunt Submission.
- And click **Propose changes and commit these changes**

By following the above steps, your repository will be primed and ready for a smooth auditing process on the Audit Hunt platform. Best of luck with your audit!