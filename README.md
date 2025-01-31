[<kbd> TEST PLAN </kbd>](#test-plan)
[<kbd> TEST CASES </kbd>](#test-cases)
[<kbd> BUG REPORTS </kbd>](#bug-reports)


# PROJECT 1

## Exploratory testing of [Rainbow Tours](https://r.pl) website

### TEST PLAN
TEST PLAN for testing the Rainbow Tours web application

#### 1. Introduction
This document outlines the test plan for the Rainbow Tours web application. The application is designed for the following purposes:
- Presenting trip options divided into many different categories (e.g. All-inclusive, Cruises, Skiing, Last minute, Charters, etc.).
- Searching for the trip offers using filtering options like destination, dates or form of transport.
- Creating the user account with personal data (e.g. Name, Surname, Address, ID number/ Passport number, etc.).
- Updating personal data in the user's account.
- Presenting the detailed descriptions of the offers with pictures and customer reviews.
- Booking the trips.
- Paying for trips using different payment options.
- Providing customer support via phone, email or chat.
- Providing travel inspiration through a blog (articles and guides).
- Offering discounts and loyalty programs like last-minute deals or points systems (Boomerang).
- Providing an informative section ‘About us’ with information about the company, addresses of the regional offices, careers section, etc.
- Displaying links to social media platforms.

#### 2. Purpose of Testing
Manual regression tests to ensure that the application functions correctly and without issues after updating the Chrome browser to the latest version.

#### 3. Scope of Testing

##### Test scenario TS001 Login to the system

Test scenario description:
The purpose of this test is to verify if the login to the user’s account functionality is working correctly.

The test will cover:
- login with correct credentials
- login with incorrect credentials or empty fields
- blocking the account after entering incorrect password multiple times
- login using social media accounts
- using remember me functionality
- reseting password
- deleting account

Test cases:

1. Test case TC001 Login to the system with correct login and password

2. Test case TC002 Login to the system with incorrect login

3. Test case TC003 Login to the system with incorrect password

4. Test case TC004 Login to the system with empty login field

5. Test case TC005 Login to the system with empty password field

6. Test case TC006 Login to the system with empty login and password field

7. Test case TC007 Login to the system with incorrect format of email (login)

8. Test case TC008 Login to the system with incorrect password multiple times

9. Test case TC034 Attempt to log in using image in the login

10. Test case TC009 Login to the account blocked due to multiple unsuccessful tries 

11. Test case TC010 Login to the system using social media - facebook account

12. Test case TC011 Login to the system using social media - google account

13. Test case TC012 Login to the system using social media - apple account

14. Test case TC013 Remembering credentials after using ‘Remember me’ (‘Zapamietaj mnie’) functionality

15. Test case TC014 Resetting password using ‘Forgot the password?' (’Nie pamiętasz hasła?') functionality

16. Test case TC015 Login to the system after changing the password

17. Test case TC033 Creating an account to delete

18. Test case TC016 Login to the account that has been previously deleted



##### Test scenario TS002 Testing the booking process for a trip 

Test scenario description:
The purpose of this test is to verify if the main feature of the website: booking a trip is working correctly.

The test will cover:

- searching for a trip,
- selecting a trip,
- adding trip to the cart,
- completing the reservation form.

Test cases:

1. Test case TC026 Searching for a trip

2. Test case TC027 Selecting a trip offer

3. Test case TC028 Adding the trip to the cart

4. Test case TC042 Verifying radio button functionality in the booking form - personal data

5. Test case TC043 Verifying checkbox functionality in the booking form - personal data

6. Test case TC045 Verifying hyperlinks in the booking form - personal data

7. Test case TC044 Entering personal information for the travelers in the trip booking process - 'Zablokuj za darmo' option

8. Test case TC029 Entering personal information for the travelers in the trip booking process - 'Zarezewuj teraz' option

9. Test case TC030 Selecting additional services in the trip booking process

10. Test case TC031 Entering personal information of the accompanying person during the trip booking process

11. Test case TC035 Booking information summary - verification of participant 1 data

12. Test case TC036 - Booking information summary - verification of participant 2 data

13. Test case TC037 - Booking information summary - room configuration validation

14. Test case TC038 - Booking information summary - price details

15. Test case TC039 - Booking information summary -  adding loyalty cards

16. Test case TC040 - Booking information summary - adding voucher

17. Test case TC041 - Booking information summary - choosing payment options
    

#### 4. Testing Approach
Exploratory and functional testing of the system will be conducted.

#### 5. Testing Environment
- Operating system: Windows 10 Home, 
- Processor: AMD Ryzen 7 4800H
- RAM: 32,0 GB
- Web browser: Google Chrome version 131.0.6778.86 ,
- Software used: Jira, Screenpresso.

#### 6. Risks
- Login data security: User’s private data will be used during testing; login details must not be shared or cached.
- Server overload during peak hours.
- Browser compatibility issues with the website.

#### 7. Artifacts
- Test scenarios,
- Test cases,
- Bug reports,
- Test summary report.

#### 8. Roles and Responsibilities
Tester responsible for executing the project: Wiktoria Mozalewska

#### 9. Test Completion Criteria
Testing will be considered complete upon:

- Execution of the test scenarios,
- Reporting bugs in the form of bug reports,
- Completion of the test summary report.
  
### TEST CASES
#### TEST SCEANRIO TS001 Login to the system
|Id |Title                                                          |TEST CASE|
|:-:|:-------------------------------------------------------------:|:---------------:|
|1  |Login to the system with correct login and password|[TEST CASE TC001](https://drive.google.com/file/d/1rDZgi__dxm1XLZkwyc7SPGPaU16e2mHg/view?usp=sharing)|
|2  |Login to the system with incorrect login|[TEST CASE TC002](https://drive.google.com/file/d/1fqbMYnS4ptqajvhrSICFU6NuKxBo0XYa/view?usp=drive_link)|
|3  |Login to the system with incorrect password|[TEST CASE TC003](https://drive.google.com/file/d/1izBCELRcKxRiTLzBemVauvdZyIbS2mTd/view?usp=drive_link)|
|4  |Login to the system with empty login field|[TEST CASE TC004](https://drive.google.com/file/d/1_AvSd4vBNwIia4g2KzNVthNR5sih3Cwv/view?usp=drive_link)|
|5  |Login to the system with empty password field|[TEST CASE TC005](https://drive.google.com/file/d/171huTlUok_hprmOtp2SeC9lbYh8UILZ4/view?usp=drive_link)|
|6  |Login to the system with empty login and password field|[TEST CASE TC006](https://drive.google.com/file/d/1gZL9ZRKU3zkQaO3fk0EYFBLDIvoYAJg-/view?usp=drive_link )|
|7  |Login to the system with incorrect format of email (login)|[TEST CASE TC007](https://drive.google.com/file/d/1ejPYr7qAlaywearFmMwxd1pAF9mj6I1t/view?usp=drive_link )|
|8  |Login to the system with incorrect password multiple times|[TEST CASE TC008](https://drive.google.com/file/d/1IikAhQ6D5TJ3WMWTMuwb6gAojGWvbmwA/view?usp=drive_link )|
|9  |Attempt to log in using image in the login|[TEST CASE TC034](https://drive.google.com/file/d/1y2xOJB9rgiEL5SCkKlZBXXiK2hYowb69/view?usp=drive_link )|
|10 |Login to the account blocked due to multiple unsuccessful tries |[TEST CASE TC009](https://drive.google.com/file/d/19pfqfRBbehRvDTNNlPppDt1LWw5CMwUL/view?usp=drive_link )|
|11 |Login to the system using social media - facebook account|[TEST CASE TC010](https://drive.google.com/file/d/13l7t1WnglcW7CTNTDvcvZQGR0KN5T50f/view?usp=drive_link )|
|12 |Login to the system using social media - google account|[TEST CASE TC011](https://drive.google.com/file/d/1X1gejvAyPj5-8cvgt30weuFDs97_PFmB/view?usp=drive_link)|
|13 |Login to the system using social media - apple account|[TEST CASE TC012](https://drive.google.com/file/d/1cALOjMTGVNwy8n6lMesnHfn_1j70Nd9T/view?usp=drive_link)|
|14 |Remembering credentials after using ‘Remember me’ (‘Zapamietaj mnie’) functionality|[TEST CASE TC013](https://drive.google.com/file/d/10Op3AUmpSBJqDXNTOdINmk7MYPHX255o/view?usp=drive_link)|
|15 |Resetting password using ‘Forgot the password?' (’Nie pamiętasz hasła?') functionality|[TEST CASE TC014](https://drive.google.com/file/d/1-W3PW0G8hE3wDQaSBFscUx1O1xxKHB3R/view?usp=drive_link)|
|16 |Login to the system after changing the password|[TEST CASE TC015](https://drive.google.com/file/d/1I0ZyVe2AW1yCotx-tj8HeBF6ZCDtSRz4/view?usp=drive_link)|
|17 |Creating an account to delete|[TEST CASE TC033](https://drive.google.com/file/d/1_wldPpw3d7X2p-Pcs67zCIAjC6Cs31MH/view?usp=drive_link)|
|18 |Login to the account that has been previously deleted|[TEST CASE TC016](https://drive.google.com/file/d/17d9Ldfa9fwL-_421xyzzGlDGlB9JD_Bi/view?usp=drive_link)|


#### TEST SCENARO TS002 Testing the booking process for a trip 
|Id |Title                                                          |TEST CASE|
|:-:|:-------------------------------------------------------------:|:---------------:|
|1 |Searching for a trip|[TEST CASE TC026](https://drive.google.com/file/d/1w9pHayNeXxfRCzP-UsZ24vpC4afZwlq6/view?usp=drive_link)|
|2 |Selecting a trip offer|[TEST CASE TC027](https://drive.google.com/file/d/1tkItT7tbrqtAd-OdpL3nnP2xtBg9YNzO/view?usp=drive_link )|
|3 |Adding the trip to the cart|[TEST CASE TC028](https://drive.google.com/file/d/1VAOuA-d8tblKt0Q7V6Q4BlOBjosRrz7T/view?usp=drive_link )|
|4 |Verifying radio button functionality in the booking form - personal data|[TEST CASE TC042](https://drive.google.com/file/d/1GWEQVhWF3WKP_3OtJz2dSSzpIoB1HpYZ/view?usp=drive_link )|
|5 |Verifying checkbox functionality in the booking form - personal data|[TEST CASE TC043](https://drive.google.com/file/d/1po4EocjkDz2g8Eplk9bVJtNZPmQ7BmS1/view?usp=drive_link )|
|6 |Verifying hyperlinks in the booking form - personal data|[TEST CASE TC045](https://drive.google.com/file/d/1WtguuCa2MN67GzKQgTIYBfCWjY39JUSe/view?usp=drive_link )|
|7 |Entering personal information for the travelers in the trip booking process - 'Zablokuj za darmo' option|[TEST CASE TC044](https://drive.google.com/file/d/1aspXRFT8Flnou5jCcIIY57ktAB2SVY2f/view?usp=drive_link )|
|8 |Entering personal information for the travelers in the trip booking process - 'Zarezewuj teraz' option|[TEST CASE TC029](https://drive.google.com/file/d/1ttFzdpIwUNC-ZoXbffPEwQMLeucTffVa/view?usp=drive_link )|
|9 |Selecting additional services in the trip booking process|[TEST CASE TC030](https://drive.google.com/file/d/1Qu6bIG0_8b76vaeWVAMr-aMP8dFLcEZN/view?usp=drive_link )|
|10 |Entering personal information of the accompanying person during the trip booking process|[TEST CASE TC031](https://drive.google.com/file/d/1NHl7xR-14_pBfJn0WmfAfSzPYR-RlKi-/view?usp=drive_link)|
|11 |Booking information summary - verification of participant 1 data|[TEST CASE TC035](https://drive.google.com/file/d/18hE_vHx56sUbpwuv821U5PnEgOQrPHmO/view?usp=drive_link )|
|12 |Booking information summary - verification of participant 2 data|[TEST CASE TC036]( https://drive.google.com/file/d/1himrDQ4xX_HlZDR8Ag1eh09hVK8mBug7/view?usp=drive_link )|
|13 |Booking information summary - room configuration validation|[TEST CASE TC037](https://drive.google.com/file/d/1d7zOmnNZlV1Rd0cJqwJak3bI5khwD2za/view?usp=drive_link)|
|14 |Booking information summary - price details|[TEST CASE TC038](https://drive.google.com/file/d/19FwvcUdDLVAYPQMoPxCHUYcVGhuUSb91/view?usp=drive_link )|
|15 |Booking information summary -  adding loyalty cards|[TEST CASE TC039](https://drive.google.com/file/d/1NBMH6SFAgMKmJHlUeZV9cG8AZYDovLMi/view?usp=drive_link )|
|16 |Booking information summary - adding voucher|[TEST CASE TC040](https://drive.google.com/file/d/1hOj2itr5C4ABSmS7bFnJfgCZCxzHyys4/view?usp=drive_link)|
|17 |Booking information summary - choosing payment options|[TEST CASE TC041](https://drive.google.com/file/d/1vKVfBhZgynm-CmRvdaAwxBI0BFfx-J0L/view?usp=drive_link)|

### BUG REPORTS
|Id |Title                                                          |BUG REPORT|Screencast|Screenshot|
|:-:|:-------------------------------------------------------------:|:---------------:|:--------:|:--------:|
|1  |Lack of specific error message when assigning an already registered phone number in the user's account|[BUG REPORT 1](https://drive.google.com/file/d/1L78n-mFgrkqubkogBj0A4SDTm4GmnoQr/view?usp=drive_link)|[Screencast](https://drive.google.com/file/d/135PgzW-qDmwhW3mNqcWnTi11GH8VdOEK/view?usp=drive_link)|[Screenshot](https://drive.google.com/file/d/1vITccxw4ntYXsqrQTProijPS9OJxOgbe/view?usp=drive_link)|
|2  |The map is not displayed in the section ‘Czartery’|[BUG REPORT 2](https://drive.google.com/file/d/11ZzQRParFVf94yYw48ZQw8_pYS37g00M/view?usp=drive_link)|[Screencast](https://drive.google.com/file/d/1TUZbp7DQ32ldvBizKv2SYqRgrv9IZ6-8/view?usp=drive_link)|[Screenshot](https://drive.google.com/file/d/1EKn9TI95rMF7yNiINNB-QhGahgqlnPH8/view?usp=drive_link)|
|3  |The misleading statement 'Pan na dokwaterowanie' appears during the booking process|[BUG REPORT 3](https://drive.google.com/file/d/1VPsYBZet6nNFrEnjP-KPDMLaG5d3Uy3t/view?usp=drive_link)|[Screencast](https://drive.google.com/file/d/1V_MQlQYDYCjtuNxnMySpSCCeMmvgGZZ6/view?usp=drive_link)|[Screenshot](https://drive.google.com/file/d/1Qw2E5LTbTtlKFyNdMXE_fk8_XnBZhD1H/view?usp=drive_link)|
|4  |The button redirecting to the out-of-date information is displayed|[BUG REPORT 4](https://drive.google.com/file/d/1khynDQKgeciJVcnOYJRh2aVnKCl-YPqL/view?usp=drive_link)|[Screencast](https://drive.google.com/file/d/14H3L3SpLz3C6o1Sq-oQZhuyW7qH-Z4MI/view?usp=drive_link)|[Screenshot 1](https://drive.google.com/file/d/1paQwceW3R401jO8TE8JYRoRVRnRtSCHK/view?usp=drive_link) [Screenshot 2](https://drive.google.com/file/d/10JRfTpI6Jkcn0OEQShZCX_9qpvJkReQ7/view?usp=drive_link)|
|5  |Missing hyperlink for 'Vallnord' destination|[BUG REPORT 5](https://drive.google.com/file/d/1-nbqNg89QiwWGyhs0q7b_pVzrUIAhI0r/view?usp=drive_link)|[Screencast](https://drive.google.com/file/d/1GA0uftmu8KyeJqKHP8fe9livugnt-2DU/view?usp=drive_link)|[Screenshot](https://drive.google.com/file/d/1DaBBqwwGQc6RhQr20D-F8N-B_9nc6jbd/view?usp=drive_link)|
|6  |Account is not blocked after multiple incorrect login attempts|[BUG REPORT 6](https://drive.google.com/file/d/1_kpxtrk9iEuyWOz1bG4Ii9CbhYeuHSgF/view?usp=drive_link)|[Screencast](https://drive.google.com/file/d/1Dy0e7RLAlG_FL6YoAw5PIpzfIpCjIqbN/view?usp=drive_link)|-|
