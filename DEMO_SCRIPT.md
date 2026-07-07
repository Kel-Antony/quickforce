# QuickForce Demo And Screenshot Plan

Use this as a lightweight plan for a WhatsApp-friendly demo video and README screenshots.

Before recording, switch to a sandbox, scratch org, or demo org with non-sensitive data. Close unrelated windows and avoid showing real customer names, emails, org IDs, or access-sensitive details.

## 60-90 Second Demo Script

1. **Intro**
   - Open Raycast.
   - Say: "This is QuickForce, a Raycast extension for common Salesforce admin and developer tasks."

2. **Manage Orgs**
   - Open **Manage Salesforce Orgs**.
   - Show org list, default org badge, and custom labels/colors if available.
   - Open an org or Setup.

3. **Run SOQL**
   - Open **Run SOQL Query**.
   - Show the org dropdown.
   - Run:

     ```sql
     SELECT Id, Name FROM Account LIMIT 10
     ```

   - Show result detail and copy/export actions.
   - Keep the query result data generic.

4. **Search Records**
   - Open **Search Records**.
   - Search for an Account, Contact, Lead, Opportunity, or Case.
   - Show opening/copying a record.

5. **Create Record**
   - Open **Create Record**.
   - Show the org dropdown on the first screen.
   - Open Lead or Task creation form.
   - Do not create a production record in the demo.

6. **Setup Quick Access**
   - Open **Setup Quick Access**.
   - Search for "Flows" or "Users".
   - Pin a setup page.

7. **Close**
   - Say: "I am looking for feedback on install, usefulness, bugs, and what would make this daily-driver ready."

## Recording Checklist

- Raycast is visible and large enough to read on mobile.
- Demo org is selected before showing Salesforce data.
- No production customer data, emails, org IDs, or tokens are visible.
- The video includes the install/testing guide link in the post text, not inside the screen recording.
- Target length is 60-90 seconds.

## Screenshot Checklist

Capture 5-7 clean screenshots:

- Manage Salesforce Orgs
- Org Details
- Run SOQL Query form
- SOQL Results
- Search Records
- Create Record first screen with org dropdown
- Setup Quick Access
- Manage Users, if using a safe sandbox/dev org
- Org Limits in Menu Bar, if it looks useful and does not expose sensitive limits

## Screenshot Tips

- Use a sandbox or demo org.
- Avoid exposing production customer data, usernames, emails, org IDs, or access-sensitive details.
- Crop around Raycast so the screenshot is easy to read on mobile.
- Keep screenshots in a future `assets/screenshots/` folder if you add them to the repo.
