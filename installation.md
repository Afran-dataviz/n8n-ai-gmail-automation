# Installation Guide

## Prerequisites

Before using this workflow, ensure you have:

* n8n installed and running
* A Google account
* Gmail access
* Google Sheets access
* Google Gemini API key

---

## Step 1: Import Workflow

1. Open n8n.

2. Click **Import Workflow**.

3. Select:

   workflow/gmail-automation.json

4. Save the workflow.

---

## Step 2: Configure Google Sheets

1. Create a Google Sheet.

2. Add columns:

   * Name
   * Email
   * Company
   * Status

3. Connect Google Sheets credentials in n8n.

4. Update the Sheet ID in the workflow.

---

## Step 3: Configure Gemini AI

1. Obtain a Gemini API key.
2. Create Gemini credentials in n8n.
3. Add your API key.
4. Test the connection.

---

## Step 4: Configure Gmail

1. Create Gmail OAuth credentials.
2. Connect Gmail to n8n.
3. Authorize email sending permissions.
4. Test the Gmail node.

---

## Step 5: Activate Workflow

1. Enable the workflow.
2. Verify Schedule Trigger settings.
3. Run a test execution.
4. Confirm emails are sent successfully.

---

## Workflow Process

Schedule Trigger
→ Read Pending Records from Google Sheets
→ Generate Email using Gemini AI
→ Send Email through Gmail
→ Update Status in Google Sheets

---

## Troubleshooting

### Gmail Authentication Error

* Reconnect Gmail credentials.
* Verify OAuth permissions.

### Google Sheets Not Updating

* Check Sheet ID.
* Verify Google Sheets permissions.

### Gemini API Error

* Confirm API key is valid.
* Check API quota and usage limits.

---

## Author

A Afran
