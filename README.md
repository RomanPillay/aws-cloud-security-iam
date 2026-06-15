# Cloud Security with AWS IAM

**Author:** Roman Pillay
**Email:** romanpillay72@gmail.com

---

## Project Overview

In this project, I demonstrate how to use AWS IAM to control access and 
permissions settings in an AWS account. I built this to learn about cloud 
security from the absolute foundations — every company thinks about access 
permissions, and there are entire jobs focused on these skills.

## Tools and Concepts

Services used: Amazon EC2 and AWS IAM.

Key concepts covered: IAM users, policies, user groups, account aliases, 
JSON policy structure, IAM Policy Simulator, EC2 instance tagging, 
and environment-based access control.

## What I Built

- Launched two EC2 instances tagged as production and development environments
- Created a custom JSON IAM policy restricting intern access to development 
  only
- Set up IAM user groups and attached the policy at group level
- Configured an account alias for simplified login
- Tested policies by logging in as the IAM user and attempting actions 
  on both instances
- Used the IAM Policy Simulator to test permissions without disrupting 
  live resources

## Key Learning

The most challenging part was understanding the JSON policy structure with 
multiple statements. The most rewarding moment was seeing "permission denied" 
when the intern user attempted to stop the production instance — confirming 
the access controls were working correctly.

## Documentation

Full project documentation with screenshots available as PDF in this repository.
