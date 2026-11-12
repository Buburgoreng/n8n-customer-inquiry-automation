# Customer Inquiry Automation System

## Project Overview
An automated customer inquiry management system built using n8n and Gmail.

This project automates the process of receiving customer inquiries, notifying administrators, and sending confirmation emails to customers.

## Business Problem
Businesses often handle customer inquiries manually. This can lead to:
- Delayed responses.
- Missed customer inquiries.
- Repetitive administrative tasks.
- Inconsistent customer communication.

## Proposed Solution
An automation workflow that:
1. Receives customer information through an online form.
2. Sends an email notification to the administrator.
3. Sends an automatic confirmation email to the customer.

## Workflow Architecture
Customer Inquiry Form → n8n Form Trigger → Admin Notification Email → Customer Confirmation Email

## Form Fields
| Field | Description |
|---|---|
| Full Name | Customer's full name |
| Email Address | Customer's email |
| Company Name | Customer's company |
| Message | Inquiry details |

## Tools & Technologies
- n8n — Workflow automation
- Gmail — Email notifications
- Google OAuth2 — Gmail authentication
- diagrams.net — Business process flowchart

## Business Benefits
- Reduces repetitive administrative work.
- Improves inquiry notification speed.
- Provides automatic customer confirmation.
- Creates a more consistent inquiry-handling process.

## Testing Results
| Test | Result |
|---|---|
| Form submission | Passed |
| Admin notification email | Passed |
| Customer confirmation email | Passed |

## Project Documentation
- `documentation/customer-inquiry-flowchart.png`
- `documentation/customer-inquiry-flowchart.drawio`
- `documentation/workflow-details.md`

## Project Status
Core workflow successfully implemented and tested.

## Future Improvements
- Google Sheets integration.
- Automatic inquiry categorization.
- CRM integration.
- AI-powered inquiry classification.