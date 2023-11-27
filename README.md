# About project 
✅ The scope of this project was to perform testing on different user scenarios from a course web and mobile page that addressed critical and edge cases

✅ Conducted different testing types such as functional, exploratory and compatibility

✅ Applied different test techniques (EP, BVA, Decision Table, STT) on given requirements

✅ Created bug reports for different issues such as usability and visual

# Test Case #1
### Business Requirement 
_As a User I can access to my bank accounts from the main menu_
### Test Name
User accounts
### Description
User can view different owned accounts when accessing accounts module
### Test Steps 
1. Access bank webpage;
2. Introduce valid email ID and password;
3. Click on "Submit"
4. Click on "Accounts" module
### Precondition
_User with active account numbers_
### Test Data
email: gregohio98@gmail.com
password: Psol5.Asc!v
### Priority
High
### Expected result
User should be able to see all his active accounts 
### Tester 
George-Marian Lupu
### Status 
To Do
### Comment
N/A

# Test Case #2
### Business Requirement 
_User can have multiple accounts_
### Test Name
User accounts
### Description
User that has 4 account numbers can see all 4 on the accounts list
### Test Steps 
1. Access bank webpage;
2. Introduce valid email ID and password;
3. Click on "Submit"
4. Click on "Accounts" module
### Precondition
_User with 4 different active account numbers_
### Test Data
email: marianatimbure12@gmail.com
password:martim12123.
### Priority
High
### Expected result
User should be able to see the 4 active accounts
### Tester 
George-Marian Lupu
### Status 
To Do
### Comment
N/A

# Test Case #3
### Business Requirement 
_User can see Balance next to the account number_
### Test Name
User account
### Description
While an user access his active account, he can see the current balance next to the account numbers
### Test Steps 
1. Access bank webpage;
2. Introduce valid email ID and password;
3. Click on "Submit"
4. Click on "Accounts" module
### Precondition
User accounts with positive balance 
### Test Data
email: rondorothy5@gmail.com
password: LsM51.s!gga
### Priority
High
### Expected result
User should be able to see balance next to the account numbers
### Tester 
George-Marian Lupu
### Status 
To Do
### Comment
N/A

# Test Case #4
### Business Requirement 
_Placeholder should appear if user has no accounts_
### Test Name
User account
### Description
User with no account will observe a placeholder
### Test Steps 
1. Access bank webpage;
2. Introduce valid email ID and password;
3. Click on "Submit"
4. Click on "Accounts" module
### Precondition
User that has no accounts
### Test Data
email: reyrey61@gmail.com
password: Estamp!msa.@135
### Priority
High
### Expected result
User should see a placeholder image next to account information
### Tester 
George-Marian Lupu
### Status 
To Do
### Comment
N/A

# Test Case #5
### Test Name
User account balance
### Description
User with negative balance account can see the value next to the account
### Test Steps 
1. Access bank webpage;
2. Introduce valid email ID and password;
3. Click on "Submit"
4. Click on "Accounts" module
### Precondition
User that has negative balance account
### Test Data
email: mariandorohoi56@gmail.com
password: mari65dorohoi.
### Priority
High
### Expected result
User should see the negative balance account
### Tester 
George-Marian Lupu
### Status 
To Do
### Comment
N/A

# Test Case #6
### Test Name
Deleted user account
### Description
User is unable to see a deleted account number
### Test Steps 
1. Access bank webpage;
2. Introduce valid email ID and password;
3. Click on "Submit"
4. Click on "Accounts" module
### Precondition
User has a deleted account number
### Test Data
email: georgethethird@yahoo.com
password: thegreatesthumanonearth51.!
### Priority
High
### Expected result
User shouldn't be able to see the deleted account number
### Tester 
George-Marian Lupu
### Status 
To Do
### Comment
N/A

# Negative testing

Given the following requirements, create negative test cases:

1. The password must include both letters and numbers

2. Users can publish a maximum of 5 microblog posts per day

3. Only JPEG photos are supported in posts

4. Posts cannot exceed 200 words

## Test Case #7
### Test Name
Password field
### Description
The password must include both letters and numbers
### Test Steps 
1. Access shop webpage;
2. Click on "Log in"
3. Click on password field
4. Introduce special characters
### Precondition
Web browser installed
### Test Data
$%!@#^^^!
### Priority
Medium
### Expected result
System displays an error message "Only letters and numbers are accepted!"
### Tester 
George-Marian Lupu
### Status 
To Do
### Comment
N/A

## Test Case #8
### Test Name
Daily post limit
### Description
Users can publish a maximum of 5 microblog posts per day
### Test Steps 
1. Access social webpage;
2. Click on "Log in"
3. Provide fields with valid data and submit;
4. Do 6 posts in a row.
### Precondition
- Web browser installed
- Existing account
### Test Data
N/A
### Priority
High
### Expected result
System displays an error message "Daily post limit is reached"
### Tester 
George-Marian Lupu
### Status 
To Do
### Comment
N/A

## Test Case #9
### Test Name
Unsuported picture format
### Description
Only JPEG photos are supported in posts
### Test Steps 
1. Acces social webpage;
2. Click on "Log in"
3. Provide fields with valid data and submit;
4. Click on "Post" field;
5. Upload a picture that has PNG format.
### Precondition
- Web browser installed
- Existing account
### Test Data
Picture with PNG. format
### Priority
High
### Expected result
System should not upload the picture and has to display error message "Only JPEG format is accepted"
### Tester 
George-Marian Lupu  
### Status 
To Do
### Comment
N/A

## Test Case #10
### Test Name
Post character limit
### Description
Posts cannot exceed 200 words
### Test Steps 
1. Acces social webpage;
2. Click on "Log in"
3. Provide fields with valid data and submit;
4. Click on "Post" field;
5. Provide the field with 201 words
### Precondition
- Web browser installed
- Existing account
### Test Data
The weather in England is renowned for its variability, marked by frequent changes that can occur within a single day. England's maritime climate is heavily influenced by the North Atlantic Drift, which ushers in mild temperatures and high humidity. Rainfall is a constant presence throughout the year, often accompanying overcast skies. Winters in England tend to be relatively mild, with occasional snowfall, especially in the north. Spring brings blooming flowers and gentler temperatures, though rain showers remain common. Summers provide longer daylight hours and warmer weather, occasionally punctuated by heatwaves, though clouds are never far away. Autumn transforms England with vivid displays of red and gold foliage, along with cooler temperatures and more rain. Regardless of the season, carrying an umbrella is wise, as rain can appear unexpectedly. Despite its unpredictable weather, England's natural beauty shines year-round, making it an enticing destination for explorers
### Priority
High
### Expected result
System should display the following error message "Character limit is reached"
### Tester 
George-Marian Lupu
### Status 
To Do
### Comment
Test field also with 199 words

# Bug Report #1
### Bug Title 
Website shows improper alignment for images
### Bug Priority
Medium
### Summary
When an user access the webpage of softwaremasterclass, the page displays images with improper alignment
### Steps to reproduce
1. Access https://softwaretestingmasterclass.com/web-application-testing/
2. Check images
### Expected result
Website homepage should display images with the proper alignment
### Actual result
Webpage displays images with improper alignment
### Attachments
<img width="1292" alt="Screenshot 2023-10-25 at 16 52 07" src="https://github.com/GeorgeMarian01/Software-Testing-Masterclass/assets/137145497/dfab4bc1-430d-4270-8461-fb3680e06169">

# Bug Report #2
### Bug Title 
Page /testypes of website softwaretestingmasterclass displays error message
### Bug Priority
Critical
### Summary
Page /testtypes of the website softwaretestingmasterclass displays an error message instead of the page that shows different test types
### Steps to reproduce
1. Access http://softwaretestingmasterclass.com/testtypes; 
### Expected result
Page should display informations about test types
### Actual result
Website page /testtypes shows error message "This page could not be found!"
### Attachments
<img width="1516" alt="Screenshot 2023-10-25 at 17 36 40" src="https://github.com/GeorgeMarian01/Software-Testing-Masterclass/assets/137145497/1feacba2-2946-471c-86d0-6ca7eae40737">

# Bug Report #3
### Bug Title 
Website does not respond to the request of accessing "More Testing" page
### Bug Priority
High
### Summary
When an user clicks on the "More Testing" field, system does not redirect user to the required page
### Steps to reproduce
1. Access https://softwaretestingmasterclass.com/web-application-testing/#
2. Click on "More Testing" 
### Expected result
Website redirects user to the required page
### Actual result
Website does not respond to the request of accessing "More Testing" page
### Attachments
N/A

# Bug Report #4
### Bug Title 
Website does not respond to the request of accessing "Learn More" page
### Bug Priority
High
### Summary
When an user clicks on the "Learn More" field, system does not redirect user to the required page
### Steps to reproduce
1. Access https://softwaretestingmasterclass.com/web-application-testing/#
2. Click on "Learn More"
### Expected result
Website redirects user to the required page
### Actual result
Website does not respond to the request of accessing "Learn More" page
### Attachments
N/A

# Bug Report #5
### Bug Title 
When accessing "View products" field, system displays page with error message
### Bug Priority
Critical
### Summary
User cannot view products as system displays error message when accessing the page as following "This page could be not found"
### Steps to reproduce
1. Access https://softwaretestingmasterclass.com/test-assignment-1/
2. Click on "View products" field
### Expected result
Website should redirect user to the page that displays the products
### Actual result
Website redirects user to a page that displays system error message as following "This page could be not found"
### Attachments
<img width="1283" alt="Screenshot 2023-10-25 at 18 20 26" src="https://github.com/GeorgeMarian01/Software-Testing-Masterclass/assets/137145497/c08375b7-2230-4f47-a2ee-bd39964adcad">

# Bug Report #6
### Bug Title 
Website modules have improper logo designs
### Bug Priority
Low
### Summary
Different logo designs of website modules are not properly related to the required pages
### Steps to reproduce
1. Access https://softwaretestingmasterclass.com/test-assignment-1/
2. Check the logo designs of the different website modules
### Expected result
Logo designs of the modules should be properly related to the required pages
### Actual result
Website modules have the improper logo design 
### Attachments
<img width="1027" alt="Screenshot 2023-10-25 at 18 38 04" src="https://github.com/GeorgeMarian01/Software-Testing-Masterclass/assets/137145497/98de60ed-a3b5-4d23-82ae-692cee944bfa">

# Bug Report #7
### Bug Title 
Address field information is missing from homepage
### Bug Priority
Medium
### Summary
Important information such as address of the service from website homepage is missing 
### Steps to reproduce
1. Access https://softwaretestingmasterclass.com/test-assignment-1/
2. Check the bottom of the page for field "Address"
### Expected result
Information of the service such as address should be displayed properly 
### Actual result
Address information is missing from homepage
### Attachments
<img width="574" alt="Screenshot 2023-10-25 at 18 45 02" src="https://github.com/GeorgeMarian01/Software-Testing-Masterclass/assets/137145497/29ae0b51-3db8-4c05-8d64-45f9a061df76">

# Bug Report #8
### Bug Title 
"Address" field from website homepage is written improperly as following "Adress"
### Bug Priority
Low
### Summary
When checking for address information, it is observed that "Address" is written improperly
### Steps to reproduce
1. Access https://softwaretestingmasterclass.com/test-assignment-1/
2. Check the bottom of the website homepage for address field
### Expected result
"Address" field should be written properly
### Actual result
"Address" field is written improperly as following "Adress"
### Attachments
<img width="236" alt="Screenshot 2023-10-25 at 18 50 48" src="https://github.com/GeorgeMarian01/Software-Testing-Masterclass/assets/137145497/e6dd4e62-1ea5-4fb4-b16f-6d508f59f552">

# Bug Report #9
### Bug Title 
"More Testing" and "Learn More" buttons do not respond 
### Bug Priority
High
### Summary
As an user, I cannot access "More Testing" or "Learn More" buttons as they don't respond to click
### Steps to reproduce
1. Access https://softwaretestingmasterclass.com/web-application-testing/
2. Click on "More Testing" or "Learn more" buttons
### Expected result
Web application should open the required web page
### Actual result
Buttons do not respond to click
### Attachments
N/A

# Bug Report #10
### Bug Title 
Facebook logo image and text field do not correspond
### Bug Priority
Medium
### Summary
On the main page of web application there is a text field that is not corresponding to the facebook logo image
### Steps to reproduce
1. Access https://softwaretestingmasterclass.com/mobile-testing-bug-bounty/
### Expected result
Image and text field should correspond
### Actual result
Facebook logo image and text field do not correspond
### Attachments
![IMG_0054](https://github.com/GeorgeMarian01/Software-Testing-Masterclass/assets/137145497/c8d2ab68-22f5-4038-9e82-7e46650b5967)


# Bug Report #11
### Bug Title 
Twitter logo image and text field do not correspond
### Bug Priority
Medium
### Summary
As an user, I see a logo image of Twitter that does not correspond to the text field attached
### Steps to reproduce
1. Access https://softwaretestingmasterclass.com/mobile-testing-bug-bounty/
### Expected result
Logo image and text should correspond
### Actual result
Twitter logo image and text field do not correspond
### Attachments
![IMG_0055](https://github.com/GeorgeMarian01/Software-Testing-Masterclass/assets/137145497/fd8f4710-abe9-4463-b74f-884669706b2a)

# Bug Report #12
### Bug Title 
Clicking on "Learn more" field redirects to 404 error message
### Bug Priority
High
### Summary
As an user, I get redirected to a 404 page error when accessing "Learn more" field
### Steps to reproduce
1. Access https://softwaretestingmasterclass.com/mobile-testing-bug-bounty/
2. Click on "Learn more" field
### Expected result
Web application should open a page with informations
### Actual result
Clicking on "Learn more" field redirects to 404 error message
### Attachments
![IMG_0056](https://github.com/GeorgeMarian01/Software-Testing-Masterclass/assets/137145497/9e964b55-277e-40c4-baaf-5e88e06dc8e9)

# Bug Report #13
### Bug Title 
Web title has alignment issues on horizontal mode
### Bug Priority
High
### Summary
As an user that uses his mobile on horizontal mode, I get text alignment issues for the main web page title 
### Steps to reproduce
1. Access https://softwaretestingmasterclass.com/mobile-testing-bug-bounty/
2. View web page on horizontal mode
### Expected result
Text should have proper alignment
### Actual result
Web title has alignment issues on horizontal mode
### Attachments
![IMG_0057](https://github.com/GeorgeMarian01/Software-Testing-Masterclass/assets/137145497/f39ee00b-2027-4b1d-aff7-16ac16693ae1)

# Equivalence Partitioning #1
_The number field should accept integer values within the range of -5000 to 5000_

CLASS I (-5000 - 5000) => VALID CLASS

CLASS II ( <-5000) => INVALID CLASS

CLASS III (>5000) => INVALID CLASS 

__TEST CASE #1 (input value = 2)__

__TEST CASE #2 (input value = -5004)__

__TEST CASE #3 (input value = 6023)__

# Boundary Value Analysis #2
_Field can accept values between 1 and 100. Perform 2 and 3 point BVA_

CLASS I (1-100) => VALID CLASS

CLASS II (<1) => INVALID CLASS

CLASS III (>100) => INVALID CLASS

__TCs for 2 point value = 0, 1, 100, 101__

__TCs for 3 point value = 0, 1, 2, 99, 100, 101__

# Decision Table Testing

### Requirements ###

- _User should have positive account balance in order to transfer money to another account_

- _The user should not be banned_

<img width="637" alt="Screenshot 2023-10-28 at 11 57 20" src="https://github.com/GeorgeMarian01/Software-Testing-Masterclass/assets/137145497/df8b261e-faa9-4991-bb9b-5234e0a30047">

**TEST CASE #1**

_System should perform the money transfer if user has positive account balance and is not banned_

**TEST CASE #2**

_System should not transfer money if user has positive account balance and is banned_

**TEST CASE #3**

_System should not transfer money if user is not banned and doesn't have a positive account balance_

**TEST CASE #4**

_System should not transfer money if user is banned and doesn't have a positive account balance_

# Black-box testing technique

![IMG_9845](https://github.com/GeorgeMarian01/Software-Testing-Masterclass/assets/137145497/a8347b5a-1cef-40c5-b005-2e4885aae9be)

**Requirement**
_One of the fields on a signup form contains a text box that accepts numeric values in the range of 20 to 30. Based on that requirement, define the proper equivalence partitions and boundary values_

**EQUIVALENCE PARTITIONS**

CLASS I (20 to 30) => VALID

CLASS II (<20) => INVALID

CLASS III (>30) => INVALID 

**BOUNDARY VALUE ANALYSIS**

2 point value BVA = 19 and 20; 30 and 31

3 point value BVA = 19, 20, 21 and 29, 30, 31

**TEST CASES**

_TC1 (Password field should accept input as 21 values)_

_TC2 (System should display error message when input is 2 values)_

_TC3 (System should display error when input is 32 values)_

_TC4 (System should display error when input is 19 values)_

_TC5 (Password field should accept input as 20 values)_

_TC6 (Password field should accept input as 21 values)_

_TC7 (Password field should accept input as 29 values)_

_TC8 (Password field should accept input as 30 values)_

_TC9 (System should display error when input is 31 values)_

# State Transition Testing #1

**Question**
_How many test cases you need for 100% 0-switch coverage?_

<img width="465" alt="Screenshot 2023-10-31 at 12 22 51" src="https://github.com/GeorgeMarian01/Software-Testing-Masterclass/assets/137145497/e46d8d07-3feb-4430-8966-93975c7ac922">

**Answear**

_We need 5 test cases to obtain 100% coverage for 0 switch_

S1 -> S2

S2 -> S1 

S2 -> S3

S3 -> S2

S3 -> S1

**Question**
_How many test cases you need to cover all 1-switch transitions?_

**Answear**

9 test cases as following:

S1-S2-S3

S1-S2-S1

S2-S3-S1

S2-S1-S2

S2-S3-S2

S3-S2-S1

S2-S3-S1

S3-S2-S3

S3-S1-S2

# State Transition Testing #2

**Question**
_How many test cases you need to achieve 100% valid transitions coverage?_

<img width="687" alt="Screenshot 2023-10-31 at 12 30 26" src="https://github.com/GeorgeMarian01/Software-Testing-Masterclass/assets/137145497/07cea786-8f75-4343-a34f-ea90088f6231">

**Answear**

8 test cases as following:

START -> Wait for pin (1)

Wait for pin -> 1st try (2)

1st try -> access to account (3)

1st try -> 2nd try (4)

2nd try -> 3rd try (5)

3rd try -> eat card (6)

2nd try -> access to account (7)

3rd try -> access to account (8)

# Boundary value analysis #3

In a system designed to work out the tax to be paid:

- An employee has 1000 euro of salary tax-free
- The next 500 euro is taxed at 10%
- The next 3000 euro after that is taxed at 22%
- Any further amount is taxed at 40%

**Question**
_How many test cases do you need to cover all 3-value Boundary Value Analysis (BVA)?_

**Answear**

9 test cases as following:

#### test case #1
As an user, if I earn 999, I will not pay any taxes

#### test case #2
As an user, if I earn 1000, I will not pay any taxes

#### test case #3
As an user, if I earn 1001, I will pay 10% tax

#### test case #4
As an user, if I earn 1499, I will pay 10% tax

#### test case #5
As an user, if I earn 1500, I will pay 10% tax

#### test case #6
As an user, if I earn 1501, I will pay 22% tax

#### test case #7
As an user, if I earn 4499, I will pay 22% tax

#### test case #8
As an user, if I earn 4500, I will pay 22% tax

#### test case #9
As an user, if I earn 4501, I will pay 40% tax

# State transition testing #3
_How many test cases do you need to achieve 100% valid transition coverage?_

![IMG_9890](https://github.com/GeorgeMarian01/Software-Testing-Masterclass/assets/137145497/785330e7-7224-49b0-aa40-e56becf2c15c)

**Answear**

#### test case #1
SS -> S1

#### test case #2
S1 -> S2

#### test case #3
S2 -> S3

#### test case #4
S2 -> S1

#### test case #5
S2 -> ES

# Checklist exemple (for banking app)
<img width="1260" alt="Screenshot 2023-10-26 at 14 46 10" src="https://github.com/GeorgeMarian01/Software-Testing-Masterclass/assets/137145497/4a3b7118-1d15-4944-b482-db8ea7400208">

# Risk-based testing practice

_Consider a video sharing application. For the following scenarios, determine the priority for testing based on the mentioned test result, probability of occurrence and impact_

<img width="800" alt="Screenshot 2023-11-02 at 13 09 26" src="https://github.com/GeorgeMarian01/Software-Testing-Masterclass/assets/137145497/56881ff4-1b83-4c6d-a678-11960433b991">

**USER LOGIN** 
_PRIORITY 1_


**WATCH VIDEOS** 
_PRIORITY 1_


**LIKE VIDEOS** 
_PRIORITY 2_


**WEBSITE ANIMATIONS** 
_PRIORITY 3_

**DELETE VIDEOS** 
_PRIORITY 4_

# Mind Map practice using MIRO tool

## Business requirements

<img width="362" alt="Screenshot 2023-11-07 at 16 30 57" src="https://github.com/GeorgeMarian01/Software-Testing-Masterclass/assets/137145497/75c433be-6443-4ef6-bcf2-e16c8026d34f">

## Mind Map ilustration

![Mind Maps-3](https://github.com/GeorgeMarian01/Software-Testing-Masterclass/assets/137145497/b0a3f85b-12b3-4846-9d13-a76779ee8870)

## Planning test scenarios using a Kanban board template

![Mind Maps-4](https://github.com/GeorgeMarian01/Software-Testing-Masterclass/assets/137145497/9c2640ae-1133-48bc-a6ae-e0067150488f)

