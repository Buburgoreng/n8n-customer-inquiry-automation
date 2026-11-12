# Workflow Documentation
## Customer Inquiry Automation System

### 1. Workflow Overview
This workflow automates customer inquiry handling using n8n and Gmail.

### 2. Workflow Components

#### Node 1 — On Form Submission
**Type:** n8n Form Trigger

**Purpose:**
Receives customer inquiry submissions through an online form.

**Input Data:**
- Full Name
- Email Address
- Company Name
- Message

#### Node 2 — Send Admin Notification
**Type:** Gmail

**Action:** Message → Send

**Purpose:**
Sends an email notification to the administrator whenever a customer submits an inquiry.

#### Node 3 — Send Customer Confirmation
**Type:** Gmail

**Action:** Message → Send

**Purpose:**
Automatically sends a confirmation email to the customer after their inquiry is submitted.

### 3. Process Sequence
1. Customer submits the inquiry form.
2. n8n receives the submitted data.
3. The administrator receives an inquiry notification.
4. The customer receives a confirmation email.
5. The workflow execution completes.

### 4. Expected Business Outcomes
- Faster inquiry notification.
- Reduced manual email handling.
- Improved customer communication.
- More consistent inquiry processing.

### 5. Technical Notes
The customer confirmation email uses data from the original form submission through an n8n expression.

### 6. Workflow Status
Successfully implemented and tested.