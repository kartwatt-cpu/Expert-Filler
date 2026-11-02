# ResumeFiller

**ResumeFiller** is a browser extension that helps job seekers fill recruitment application forms with information they choose to save locally.

> The repository name is **Expert-Filler**; the product name shown in the extension is **简历填表助手 · ResumeFiller**.

![ResumeFiller options page](assets/screenshot.png)

## What it does

- Suggests matching resume data when the user clicks a form field.
- Supports education, work, project, preference, custom-answer, and attachment data.
- Provides a preview before a full-page fill and lets the user deselect fields.
- Fills a field only after the user selects a suggestion or confirms a fill action.
- Never submits applications, bypasses CAPTCHAs, or uploads resume data to a server.

## Privacy and permissions

Resume data, attachments, preferences, and field-matching choices are stored locally in the browser's extension storage. The developer does not receive this information.

- [Privacy policy](https://kartwatt-cpu.github.io/Expert-Filler/privacy-policy.html)
- The extension runs on `http://` and `https://` pages so it can identify form fields on arbitrary company career sites and ATS domains.
- `activeTab` lets the popup read the current site address for the per-site on/off switch.
- `storage` / `unlimitedStorage` keep the local resume library and an attachment of up to 10 MB.

## Public test form

A public, account-free test form is available here:

**https://kartwatt-cpu.github.io/Expert-Filler/demo.html**

### Reviewer test steps

1. Install the extension package.
2. Open the extension's options page.
3. Go to **设置与数据** and click **载入测试数据（假）** to load the built-in fake review data.
4. Open the public test form and click the **Name** field.
5. Select **张三**. You can also press `Alt+Shift+G` to preview a page fill.

No test account is required. The fake data is only for testing and must not be used for a real application.

## Repository contents

This repository hosts the public privacy policy and review test form for the ResumeFiller browser extension. The extension package is distributed through supported browser extension stores.

## Contact

For support or privacy questions:

- Email: [17841094191@163.com](mailto:17841094191@163.com)
- GitHub: [kartwatt-cpu](https://github.com/kartwatt-cpu)

---

Privacy policy last updated: November 2, 2026.
