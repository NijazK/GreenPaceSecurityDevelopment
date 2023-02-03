# Green Pace Secure Policy Development
![image](https://user-images.githubusercontent.com/75659218/198822857-01c4c2ed-ec8a-4854-8929-7e7f515f1c56.png)

* Software development at Green Pace requires consistent implementation of secure principles to all developed applications. Consistent approaches and methodologies must be maintained through all policies that are uniformly defined, implemented, governed, and maintained over time.

## Purpose
* This policy defines the core security principles; C/C++ coding standards; authorization, authentication, and auditing standards; and data encryption standards. This article explains the differences between policy, standards, principles, and practices (guidelines and procedure): Understanding the Hierarchy of Principles, Policies, Standards, Procedures, and Guidelines.

# Scope
* This document applies to all staff that create, deploy, or support custom software at Green Pace.

# First publication
* First publication included seven steps that were outlined below that align with the elements and user requests.

# Second Publication/Improvements
## Revise the C/C++ Standards
* Completed one of these tables for each standards in the second iteration. Since the first iteration, I have added revisions to improve the explanation and examples as needed. Add rows to accommodate additional examples of compliant and noncompliant code. Coding standards begin on the security policy.

## Risk Assessment
![image](https://user-images.githubusercontent.com/75659218/198823009-ac04372c-8657-4d0b-91b1-7512b989a20c.png)

* Complete this section on the coding standards tables. Enter high, medium, or low for each of the headers, then rate it overall using a scale from 1 to 5, 5 being the greatest threat. You will address each of the seven policy standards. Fill in the columns of severity, likelihood, remediation cost, priority, and level using the values provided in the appendix.

## Automated Detection
* Complete this section of each table on the coding standards to show the tools that may be used to detect issues. Provide the tool name, version, checker, and description. List one or more tools that can automatically detect this issue and its version number, name of the rule or check (preferably with link), and any relevant comments or description—if any. This table ties to a specific C++ coding standard.

## Automation
![image](https://user-images.githubusercontent.com/75659218/198823031-61280997-2f38-4753-879d-1a0423d7b979.png)

* Automation will be used for the enforcement of and compliance to the standards defined in this policy. Green Pace already has a well-established DevOps process and infrastructure. Define guidance on where and how to modify the existing DevOps process to automate enforcement of the standards in this policy. Use the DevSecOps diagram and provide an explanation using that diagram as context.

## Created Policies for Encryption and Triple A
![image](https://user-images.githubusercontent.com/75659218/198823321-ec2af6c4-34c6-4119-a3a2-bc31e312754f.png)

 * Include all three types of encryption (in flight, at rest, and in use) and each of the three elements of the Triple-A framework using the tables provided.
  a. Explain each type of encryption, how it is used, and why and when the policy applies.
  b. Explain each type of Triple-A framework strategy, how it is used, and why and when the policy applies.
