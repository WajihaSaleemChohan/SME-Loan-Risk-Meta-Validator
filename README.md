# SME-Loan-Risk-Meta-Validator
 A complete Opus workflow for SME credit assessment and compliance

This repository contains the sample documents, configuration details, and instructions required to run the SME Loan Risk Validation Workflow on Opus.

The workflow performs:
• Registration data extraction
• Bank-statement OCR + financial metrics extraction
• Credit bureau simulation
• AI-based risk scoring
• Eligibility rule validation
• Simulated sanctions screening
• Human reviewer validation
• Audit JSON + report generation

# 1. How to Run the Workflow
Step 1 — Open the Workflow

Click the Opus workflow link provided by the author.

Click “Add to Workspace” or “Duplicate Workflow” into your own Opus workspace.

After it loads, click the Jobs tab on the top.

Step 2 — Create a New Job

	Click Create Job.

You will see the workflow input form.

# 2. Fill In These Input Fields

Enter the following values exactly as shown:
Field	Value

	Country of Registration: 	Canada
	Business Legal Name: 	Brightstar Technologies Inc.
	Registration Number: 	BRN-2024-00123
	Existing Debt: 	15000
	Requested Amount: 	25000

These text inputs simulate a real SME credit application.

# 3. Upload the Required Files

Upload the sample files provided in this repository:

Input Field	

	Bank Statement 1 File	bank_statement_1.pdf
	Bank Statement 2 File	bank_statement_2.pdf
	Registration Document File	registration_document.pdf
	Owner ID Document File	owner_id_document.pdf
