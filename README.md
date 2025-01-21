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

9. Test case TC009 Login to the account locked due to multiple unsuccessful tries 

10. Test case TC010 Login to the system using social media - facebook account

11. Test case TC011 Login to the system using social media - google account

12. Test case TC012 Login to the system using social media - apple account

13. Test case TC013 Remembering credentials after using ‘Remember me’ (‘Zapamietaj mnie’) functionality

14. Test case TC014 Reseting password using ‘Forgot the password?' (’Nie pamiętasz hasła?') functionality

15. Test case TC015 Login to the system after changing the password

16. Test case TC033 Creating an account to delete

17. Test case TC016 Login to the account that has been previously deleted


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

4. Test case TC029 Entering personal information  for the travelers in the trip booking process

5. Test case TC030 Selecting additional services in the trip booking process

6. Test case TC031 Entering personal information of the accompanying person during the trip booking process

7. Test case TC032 Booking information summary 

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
### BUG REPORTS
|Id |Title                                                          |BUG REPORT|Screencast|Screenshot|
|:-:|:-------------------------------------------------------------:|:---------------:|:--------:|:--------:|
|1  |Lack of specific error message when assigning an already registered phone number in the user's account|[BUG REPORT 1](https://drive.google.com/file/d/1L78n-mFgrkqubkogBj0A4SDTm4GmnoQr/view?usp=drive_link)|[Screencast](https://drive.google.com/file/d/135PgzW-qDmwhW3mNqcWnTi11GH8VdOEK/view?usp=drive_link)|[Screenshot](https://drive.google.com/file/d/1vITccxw4ntYXsqrQTProijPS9OJxOgbe/view?usp=drive_link)|
|2  |The map is not displayed in the section ‘Czartery’|[BUG REPORT 2](https://drive.google.com/file/d/11ZzQRParFVf94yYw48ZQw8_pYS37g00M/view?usp=drive_link)|[Screencast](https://drive.google.com/file/d/1TUZbp7DQ32ldvBizKv2SYqRgrv9IZ6-8/view?usp=drive_link)|[Screenshot](https://drive.google.com/file/d/1EKn9TI95rMF7yNiINNB-QhGahgqlnPH8/view?usp=drive_link)|
|3  |The misleading statement 'Pan na dokwaterowanie' appears during the booking process|[BUG REPORT 3](https://drive.google.com/file/d/1VPsYBZet6nNFrEnjP-KPDMLaG5d3Uy3t/view?usp=drive_link)|[Screencast](https://drive.google.com/file/d/1V_MQlQYDYCjtuNxnMySpSCCeMmvgGZZ6/view?usp=drive_link)|[Screenshot](https://drive.google.com/file/d/1Qw2E5LTbTtlKFyNdMXE_fk8_XnBZhD1H/view?usp=drive_link)|
|4  |The button redirecting to the out-of-date information is displayed|[BUG REPORT 4](https://drive.google.com/file/d/1khynDQKgeciJVcnOYJRh2aVnKCl-YPqL/view?usp=drive_link)|[Screencast](https://drive.google.com/file/d/14H3L3SpLz3C6o1Sq-oQZhuyW7qH-Z4MI/view?usp=drive_link)|[Screenshot 1](https://drive.google.com/file/d/1paQwceW3R401jO8TE8JYRoRVRnRtSCHK/view?usp=drive_link) [Screenshot 2](https://drive.google.com/file/d/10JRfTpI6Jkcn0OEQShZCX_9qpvJkReQ7/view?usp=drive_link)|
|5  |Missing hyperlink for 'Vallnord' destination|[BUG REPORT 5](https://drive.google.com/file/d/1-nbqNg89QiwWGyhs0q7b_pVzrUIAhI0r/view?usp=drive_link)|[Screencast](https://drive.google.com/file/d/1GA0uftmu8KyeJqKHP8fe9livugnt-2DU/view?usp=drive_link)|[Screenshot](https://drive.google.com/file/d/1DaBBqwwGQc6RhQr20D-F8N-B_9nc6jbd/view?usp=drive_link)|
|6  |Account is not blocked after multiple incorrect login attempts|[BUG REPORT 6](https://drive.google.com/file/d/1_kpxtrk9iEuyWOz1bG4Ii9CbhYeuHSgF/view?usp=drive_link)|[Screencast](https://drive.google.com/file/d/1Dy0e7RLAlG_FL6YoAw5PIpzfIpCjIqbN/view?usp=drive_link)|-|
