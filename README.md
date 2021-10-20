# Technical Assessment

## Assessment Introduction

This repository contains the materials for the DocuSign Technical Support Engineer candidate technical assessment. You will need a [Developer sandbox](https://go.docusign.com/sandbox/productshot/) to complete these tasks, please request one via the link. 

Please utilize the contents of this repository to complete the following tasks:

1. Using the purchase_order.pdf file in this repository, create and send an envelope.
2. Import the DS_TSE_TechTemplate.zip template to your account and attempt the following:
     - Create a new envelope using the purchase_order.pdf
     - Why does the template matching of the imported template not automatically match the uploaded purchase_order.pdf?
3. After resolving the template matching, modify the template provided with the following changes and send the envelope to yourself:
    - Add a conditional recipient with the following parameters
        - Sending order 1
        - Group Name: Accounting
        - Role: High value deal approval
        - Name and Email that you have access to
        - Add a signature to the Purchase Order ( anywhere in the document ) for the conditional recipient
        - Add a rule for this signature
            - If the the Grand Total is Greater than 1000
            - Route to the High value deal approval role
    - Add a second recipient role named Legal
    - Add a 1 page Document to the template ( e.g. a blank word doc )
    - Make the Legal role's recipient action "needs to view"
    - Restrict the visibility of the 1 page document you uploaded to the legal recipient.
		
4. Modify the API call in API TEST 1 to send successfully.

## Completion
When prompted, please submit the envelopeIDs of the successfully sent envelopes for sections 1, 3, and 4. For section 4 also include your completed API call to the recruiting coordinator.

## Notice
Please be prepared to discuss your progress during the technical portion of your interview, including any challenges you encountered, potentially sending one of the envelopes and/or running the API call live during the interview. If you were unsuccessful at any portion of this assessment, please be prepared to discuss the obstacles you encountered and the steps you attempted to move forward.

## Resources
- [DocuSign Dev Sandbox](https://go.docusign.com/sandbox/productshot/)
- [DocuSign User Guide](https://support.docusign.com/en/guides/ndse-user-guide)
- [DocuSign Admin Guide](https://support.docusign.com/en/guides/ndse-admin-guide)
- [API Reference](https://developers.docusign.com/docs/esign-rest-api/reference/)
- [DocuSign Postman Collection](https://www.docusign.com/blog/dsdev-please-mr-postman)

