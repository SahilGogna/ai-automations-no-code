# Automated Resume & Cover Letter Generator for LinkedIn Job Posts

This repository hosts community submissions for a hackathon project focused on automating the job application pipeline with Make.com (Integromat) and AI tools.

## 🎯 Objective

Job applications often require manual tailoring of resumes and cover letters for each posting, which is time-consuming and repetitive.  
These automations solve that by:

- **Fetching** latest LinkedIn job posts via RSS feeds  
- **Extracting** key job details (title, company, recruiter info, skills, posting date)  
- **Analyzing** job descriptions with OpenAI to generate:
  - Tailored resume (aligned with job requirements)
  - Tailored cover letter (storytelling-driven, company specific)
- **Converting** generated HTML → PDFs with PDF.co  
- **Uploading** files to OneDrive/Google Drive for easy sharing  
- **Logging** all job details and file links into Google Sheets for centralized tracking
