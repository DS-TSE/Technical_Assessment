# Technical Assessment

## Assessment Introduction

This repository contains the materials for the DocuSign Technical Support Engineer candidate technical assessment. You will need a [Developer sandbox](https://go.docusign.com/sandbox/productshot/) to complete these tasks, please request one via the link. During this assessment, you may experience error messages, inconsistent application behavior, or steps that cannot be achived. Please treat the tasks below as hypotheitcal cases that a customer has submitted. 

Please utilize the contents of this repository to complete the following tasks:

1. Using the purchase_order.pdf file in this repository, create and send an envelope.
     - **Case submission:** Hello support, I tried to send the attached purchase_order.pdf to my co-worker but I'm receiveing an error message, I'm not sure what it means, can you help?
     - Please also include a response you would write to this cusotmer in your sbmission to the recruiter. 
2. Import the DS_TSE_TechTemplate.zip template to your developer account and attempt the following:
     - This imported template has automatic template matching enabled, and uploading the purchase_order.pdf would normally trigger automatic template matching.
     - Create a new envelope using the purchase_order.pdf
     - **Case submission:** Hello support, I migrated this template from my demo account to my production account, but when I try to use template matching, it's not working automatically. Why does the template matching of the imported template not automatically match the uploaded purchase_order.pdf?
3. Modify the template provided with the following changes and send the envelope to yourself:
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
    - Make the Legal role's recipient the last in the routing order, and set their action to "needs to view"
    - Restrict the visibility of the 1 page document you uploaded to the legal recipient.
    - Ensure open the envelope as each of the signers and ensure that the legal recipient cannot view the additional 1 page document.
    - Send the envelope based on the template and make sure all roles sign, including the High value deal approval role. 
		
4. Modify the API call in API TEST 1 to send successfully.

## Completion
When prompted, please submit the envelopeIDs of the successfully sent envelopes for sections 1, 3, and 4. For question 3, also export the template and include the zip file in your submission.  For section 4 also include your completed JSON API call to the recruiting coordinator.

If you run into issues or have questions with the evaluation please contact us at [ds-tse-interview@docusign.com](mailto:ds-tse-interview@docusign.com)

## Notice
Please be prepared to discuss your progress during the technical portion of your interview, including any challenges you encountered, potentially sending one of the envelopes and/or running the API call live during the interview. If you were unsuccessful at any portion of this assessment, please be prepared to discuss the obstacles you encountered and the steps you attempted to move forward.


## Resources
- [DocuSign Dev Sandbox](https://go.docusign.com/sandbox/productshot/)
- [DocuSign User Guide](https://support.docusign.com/en/guides/ndse-user-guide)
- [DocuSign Admin Guide](https://support.docusign.com/en/guides/ndse-admin-guide)
- [API Reference](https://developers.docusign.com/docs/esign-rest-api/reference/)
- [DocuSign Postman Collection](https://www.docusign.com/blog/dsdev-please-mr-postman)

