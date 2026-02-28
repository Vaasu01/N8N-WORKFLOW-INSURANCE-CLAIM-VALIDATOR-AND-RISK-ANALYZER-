## n8n Workflow Overview

This workflow handles insurance claim submissions.

### Steps

1. Trigger  
   - Starts when a claim is submitted (Webhook/Form/Manual)

2. Validate Data  
   - Checks if required fields are present

3. Process Data  
   - Formats the submitted information

4. Send Notification  
   - Sends an email to notify about the new claim

5. Store Record  
   - Saves the claim details to storage (e.g., database or Google Sheets)

### Nodes Used

- Trigger Node
- AI Risk Analyzer
- Groq Chat Model
- Simple Memory
- Create A Document
- Update A Document
- Google Drive 
- Gmail Node
  
