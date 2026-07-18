# Use Case #2 - How to article to view application logs on AWS EKS using AWS CloudWatch

## Problem Statement

A client has an installation of a product on an AWS EKS cluster. The client wants information on how to view logs of the product on AWS CloudWatch, including basic queries to filter their logs. 

## Process

1. Collate existing information on installation, which can consist of:
* The contact details of any Subject Matter Experts (SME) (e.g. DevOps engineers and/or Sales Engineers involved in customer product installation).
* Existing internal documentation on logs retrieval - commonly used log queries, details on customer installation and work done.
* AWS CloudWatch logs documentation for setup on EKS clusters, and basic query examples.

2. Acquire a similar AWS environment to the client and any access permissions to EKS and CloudWatch services.

3. Ask the Subject Matter Expert (SME) if any thing has been set up on the environment to get logs sent from the cluster to CloudWatch. In this case, the SME followed CloudWatch setup covered on the AWS documentation, and has provided this link. Note that this prerequiste is out of scope for this document, but should be mentioned as a prerequisite.

4. On the customer-like AWS environment, try out basic queries from AWS documentation. Try any common queries from existing documentation (convert the syntax if required).

5. List out common queries that would be of use to the customer, for example:
* Fetch logs of specific container
* Fetch all ERROR logs of a specific container
* Fetch logs with a certain thread/job ID

6. Format the document (e.g. wrap queries in code formatting)

7. Send document for review; confirm that those queries are correct.

8. Create the final draft, and send the document via the correct channels to the client.
