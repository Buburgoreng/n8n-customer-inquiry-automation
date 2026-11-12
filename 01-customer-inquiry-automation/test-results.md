# Test Results – Customer Inquiry Automation System

## 1. Testing Overview

The workflow was tested to verify that customer inquiries are received and processed correctly through n8n and Gmail.

## 2. Test Cases

| No. | Test Scenario | Expected Result | Actual Result | Status |
|---|---|---|---|---|
| 1 | Customer submits inquiry form | Form data is received by n8n | Successfully received | PASS |
| 2 | Admin notification email | Administrator receives inquiry notification | Email successfully delivered | PASS |
| 3 | Customer confirmation email | Customer receives confirmation email | Email successfully delivered | PASS |

## 3. Testing Summary

- Total test cases: 3
- Passed: 3
- Failed: 0

## 4. Notes

The customer confirmation email was initially classified as Spam by Gmail during testing.

## 5. Conclusion

All three core workflow test cases were completed successfully. The automation is functioning as expected for the tested scenarios.

**Project:** Customer Inquiry Automation System  
**Platform:** n8n  
**Email Integration:** Gmail