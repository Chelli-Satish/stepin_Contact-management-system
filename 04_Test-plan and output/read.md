# TEST PLAN:

## Table no: High level test plan

| **Test ID** | **Description**                                              | **Exp I/P** | **Exp O/P** | **Actual Out** |**Type Of Test**  |    
|-------------|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  H_01       |  adding a new contact|contact-number:, contact-name:, phone-number:,mail -id  : |contact-number:1, contact-name:abcd, phone-number:1234567890,mail -id  :xy| contact-number:1, contact-name:abcd, phone-number:1234567890,mail -id  :xy|Boundary based    |                                     
|  H_02        |adding a new contact-2| contact-number:, contact-name:, phone-number:,mail -id  :|contact-number:2, contact-name:sasi, phone-number:135792340,mail -id  :eeegmail.com|contact-number:2, contact-name:sasi, phone-number:135792340,mail -id  :eeegmail.com|Scenario based |   
|  H_03       |Delete  of  contact details|  Enter Account  Number:2|   Deleted Second  account|Deleted Second  account|Boundary based    |
 |04      |Modification  of    contact Details  |Enter  Contact account number  to  modify  or  change :1    |Modify  first contact details|Modify  first contact details|Boundary based    | 
 | H_05      |List  all the contacts |Enter contact names :1,2   |contact-number:1, contact-name:abcd, phone-number:1234567890,mail -id  :xy| contact-number:1, contact-name:abcd, phone-number:1234567890,mail -id  :xy|Modify  first contact details:contact-number:2, contact-name:sasi, phone-number:135792340,mail -id  :eeegmail.com|contact-number:2, contact-name:sasi, phone-number:135792340,mail -id  :eeegmail.com|Boundary based    |
