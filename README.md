Use Case Details:
 1. Have multi step form
 2. Stages as follows , apply loan, document collection, document verification,final approval, dispatch
 3. Auto fill customer ID, date
 4. Duplicate search with loan amount, phone number and name
 5. Skip document verification stage if loan amount less than 1 lack
 6. Create another case called Customer once final approval is done, transfer all customer profile related date (like address, phone, name.etc)
 7. Have appropriate status names and reroute
 8. Max SLA for each stage is 2 days
 9. Mail should be sent to user once each stage approved
 10. On fial approval generate the PDF
 11. Demo should be given as end user, each approval should be done with respective user portal
 12. Use data page to display IFSC code, user selects IFSC code then respective Bank name should be selected.

Sample Data Model:
 
  1. Applicant Information
     . Full name
     . Date of Birth
     . Gender
     . Marital status
     . Social security Number(National ID)
     . Contact Information (Phone, Email)
     . Physical address (Current and permanent)
     . Employment status (Employed, Self-Employed, Unemployed)
     . Employer Name (if employed)
     . Job Title
     . Work Experience
     . Education
  2.Financial Information
     . Monthly Income
     . Other Source of Income
     . Current Debts and Liabilities
     . Credit Score
     . Bank Account Details
     . IFSC code
     . Bank name
     . Tax Information
  3. Loan Details
     . Loan Acount Requested
     . Purpose of the Loan
     . Loan Tensure(Repayment period)
