# Use Case #1 - Installation Document for Product A

## Problem Statement

Client A wants an installation document for their product, Product A (Version 2). 

The configuration must be addressed in the installation steps, which include:
* Setting up a license URL (Required)
* External PostgreSQL settings (Optional)

## Process

1. Collate existing information on installation, which can consist of:
* The contact details of any Subject Matter Experts (SME) (e.g. DevOps engineer who created the Product A deployment artefacts)
* Existing internal documentation on Product A installation (this can include previous versions).
* The Product A Version 2 deployment package.

2. Determine if there is enough installation information (e.g. are there any installation steps already documented?) If this is not the case, request a meeting with the SMEs to run through an installation, record the meeting/take notes. If there are any additional gaps in server requirements, also bring this up during the meeting.

3. Set up or request for a server to test installation:
* If any system requirements have been mentioned in internal documentation and/or SME calls, request for an environment with those requirements specifically. (Note: this could be an environment that replicates Product engineer test environments)
* Install Software (In this case, Docker and Docker Compose) by following Docker documentation, ensuring Docker and Docker Compose have the correct versions.

4. Create a first draft of the document with the information currently provided. Roughly organise the information into the appropriate sections. As this is for a customer facing document, typical installation details could include: 
* High Level Summary 
* Server Requirements
* Software Requirements
* High level infomration on the deployment package
* Steps to install
* Post-Installation/Confirmation install has been successful

5. Using the first draft document alone, attempt to install Product A version 2 into the server.If any problems arise, refer to the gathered information from SMEs and Internal documentation to check the information matches.
* If there are any blockers in install, then reach out to installation SME with error and log information.Whilst going through installation steps, edit the first draft.
* Any other missing information that should be included (e.g. make sure you are logged into the server as a user with the correct information)

6. Use personal installation experience to create a near final draft. Flag any missing details, and send to the SME for a review.

7. Create the final draft, and send for publication.
