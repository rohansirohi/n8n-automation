# Form Submission Automation (Sheets + Email Notifications)

## Purpose
This workflow automates the handling of form submissions by storing responses in Google Sheets and sending email notifications to both the user and the internal team.

## Trigger
- Form submission (via webhook / connected form)

## Workflow Steps
1. Receives form submission data
2. Appends the data as a new row in Google Sheets
3. Sends a confirmation email to the user
4. Sends an internal notification email to the team

## Notifications
- **User Email:** Confirmation that the submission was received
- **Internal Email:** Alert with submission details for follow-up

## Use Cases
- Contact forms
- Lead capture
- Feedback collection
- Simple customer inquiries

## Notes
This workflow is intentionally kept simple to demonstrate a clean and reliable end-to-end automation flow.
