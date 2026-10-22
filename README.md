# Support Ticket Priority Prediction and Automated Assignment System Using Agentforce

## 1. Project Overview

This project presents an intelligent support ticket management system built on the Salesforce platform. It automates ticket priority classification and ticket assignment using Salesforce Flow and Agentforce.

## 2. Business Value & Key Objectives

- **Faster Ticket Resolution:** Prioritizes critical issues automatically.
- **Reduced Manual Effort:** Reduces manual ticket review.
- **Improved Customer Satisfaction:** Helps resolve customer issues faster.
- **Intelligent Workload Management:** Assigns tickets to suitable support agents.

## 3. Project Features

- Ticket priority classification: High, Medium, Low.
- Automated assignment of support tickets.
- Agentforce analysis of ticket descriptions.
- Task creation for high-priority tickets.
- Ticket visibility for agents and managers.

## 4. Custom Object Data Model

**Object Name:** Support Ticket Intelligence

**API Name:** Support_Ticket_Intelligence__c

| Field Label | API Name | Data Type |
|---|---|---|
| Ticket Number | Ticket_Number__c | Auto Number |
| Description | Description__c | Long Text Area |
| Priority Level | Priority_Level__c | Picklist |
| Status | Status__c | Picklist |
| Assigned To | Assigned_To__c | Lookup |

## 5. Flow Architecture & Automation Logic

1. Retrieve the support ticket.
2. Analyze the ticket description.
3. Determine priority: High, Medium, or Low.
4. Assign the ticket to a suitable support agent.
5. Create a follow-up task for high-priority tickets.

## 6. Technologies Used

- Salesforce Platform
- Salesforce Flow
- Agentforce
- Custom Objects
- Reports and Dashboards

## 7. Expected Outcome

The system aims to reduce response time, automate repetitive tasks, and improve customer support efficiency.

## 8. Conclusion

This project uses Salesforce automation and Agentforce to improve ticket prioritization and assignment.

