📄 T LEVEL OS – ACTIVITY B (i)

Full Design & Algorithm Document Template (Thorough Version)

(Visual / Interface Designs + Algorithms + Data + Testing + Security)

0. Candidate & Project Information

Candidate Name:

Candidate Number:

Centre Name:

System / Project Title:

Date:

1. Visual / Interface Designs Checklist

This section covers everything about how your system looks and behaves for the user.

1.1 Visual / Interface Designs – User Interface Screens
1.1.1 Checklist (Tick as you complete)

 I created a UI design for every required screen.

 I showed a clear user journey between screens.

1.1.2 List of Screens

List each screen and its purpose.

Sentence starters:

“This screen allows the user to…”

“The main purpose of this screen is to…”

“From this screen, the user can move to…”

Template:

Screen 1: Home Page

Purpose:
“The main purpose of the Home page is to…”

Key features:
“This screen allows the user to…”

Links to:
“From this page, the user can move to the Login page, Register page, and Booking page using…”

Screen 2: Login Page

Purpose:

Key features:

Links to:

Screen 3: Register Page

Purpose:

Key features:

Links to:

Screen 4: Booking Page

Purpose:

Key features:

Links to:

Screen 5: Confirmation Page

Purpose:

Key features:

Links to:

(Add more screens if needed.)

1.2 Navigation Flow / User Journey

You must clearly show how users move through the system.

Sentence starters:

“The user journey begins when the user…”

“Next, the user is taken to…”

“If the user chooses…, they are directed to…”

“The journey ends when…”

Example paragraph:
The user journey begins when the user opens the Home page and chooses either Login or Register. If they already have an account, they select Login and enter their details to reach the Dashboard. New users select Register, create an account, and are then redirected to the Login page. Once logged in, users can go to the Booking page to create a new booking. The journey ends on the Confirmation page where the user can see their booking details.

Add a small flow diagram here if you can.

1.3 Colour / Typography / Layout Justification

You must explain why your design choices are suitable and accessible.

1.3.1 Colour Choices

Sentence starters:

“I chose this colour scheme because…”

“This background and text colour support accessibility by…”

“The contrast between the text and background is suitable because…”

Template paragraph:
I chose a blue and white colour scheme because it is clean and professional. The dark blue text on a white background provides high contrast, which supports readability and follows W3C contrast guidelines. Important buttons, such as ‘Submit’ and ‘Login’, use a stronger accent colour to stand out clearly.

1.3.2 Typography (Fonts & Sizes)

Sentence starters:

“I selected a sans-serif font such as…”

“This font improves readability because…”

“Headings use a larger font size to…”

Template paragraph:
I selected a sans-serif font such as Arial because it is simple and easy to read on screens. Headings use a larger font size to make the structure of the page clearer. Body text uses a consistent size that can be easily scaled by the browser if the user zooms in. This supports users with visual difficulties.

1.3.3 Layout Choices

Sentence starters:

“My layout follows a consistent structure by…”

“I placed the navigation bar in the same position on every page so that…”

“I used spacing and grouping to…”

Template paragraph:
My layout follows a consistent structure across all pages. The navigation bar is placed at the top of each screen so users always know where to find it. Content is grouped into sections with clear headings and spacing, which helps users focus on one area at a time. This improves usability and reduces confusion.

1.4 W3C Accessibility Compliance

You must mention how your design supports accessibility standards.

1.4.1 Accessibility Features Checklist

 Alt text for images

 High contrast options

 Logical reading order

 Keyboard navigation

 Scalable fonts

 Consistent layout conventions

1.4.2 Accessibility Explanation

Sentence starters:

“To support users with visual impairments, I…”

“All images include alt text such as…”

“The reading order is logical because…”

“Keyboard users can navigate by…”

Template paragraph:
To support accessibility, all images include meaningful alt text, for example “alt='Logo of the website'”. The reading order is logical, from top to bottom and left to right, which helps screen readers interpret the content correctly. Keyboard users can move between links and form fields using the tab key in a sensible order. Font sizes can be increased without breaking the layout, supporting users who need larger text.

1.5 Front-End Requirements

Describe what the front-end must include.

1.5.1 Checklist

 Pages needed (list)

 Buttons / links defined

 Forms defined

 Input validation rules

 Navigation bar behaviour

 Mobile responsive layout

 Media used (images, icons, videos)

1.5.2 Explanation

Sentence starters:

“The front-end of the system will include the following pages…”

“Users interact with the system through…”

“Forms will include validation to ensure…”

“The layout is mobile responsive because…”

Template paragraph:
The front-end of the system will include the Home, Login, Register, Booking, and Confirmation pages. Users interact with the system through buttons, navigation links, and form inputs. Forms will include validation to ensure that required fields are not left empty and that email addresses follow a correct format. The layout is designed to be responsive so that it adjusts to different screen sizes, including mobile phones.

1.6 Back-End Requirements

Explain what the back-end needs to do.

1.6.1 Checklist

 Server processes (what the server does)

 Database operations required

 Login / authentication flow

 Booking logic

 Data validation rules

 API endpoints (if any)

 Error handling

 Security controls (hashing, HTTPS, permissions)

1.6.2 Explanation

Sentence starters:

“The back-end will handle tasks such as…”

“The system will store data including…”

“The login process works by…”

“Bookings are processed by…”

“Error handling will be implemented by…”

Template paragraph:
The back-end will handle tasks such as user authentication, booking processing, and database communication. The system will store data including user details, hashed passwords, and booking information. The login process works by checking the username, retrieving the stored password hash, and comparing it with the user’s input. Bookings are processed by checking availability, calculating the cost, and saving the booking to the database. Error handling will be implemented through clear error messages and logging.

1.7 Security Evaluation (High-Level)

You must explain security in plain English, not code.

1.7.1 Security Topics

Encryption

Validation

Sanitisation

Permission checks

Preventing SQL injection

Protecting user data

1.7.2 Explanation

Sentence starters:

“Security in this system is managed by…”

“User data is protected by…”

“Input is validated and sanitised to…”

“SQL injection is prevented by…”

“Access to certain features is restricted to…”

Template paragraph:
Security in this system is managed by the developers and system administrators. User data is protected by encrypting connections using HTTPS and hashing passwords before storing them in the database. Input is validated and sanitised to remove harmful characters, which reduces the risk of attacks. SQL injection is prevented by using parameterised queries instead of building SQL strings directly. Access to admin pages is restricted to users with the correct permissions.

2. Algorithms Checklist & Design

You must provide algorithms in pseudocode or flowcharts, plus justifications.

2.1 Login Algorithm
2.1.1 Requirements Checklist

 Inputs: username and password

 Check account exists

 Validate credentials

 Handle errors (incorrect / blank)

 Output success or failure

 Justification written

2.1.2 Description

Sentence starters:

“The purpose of this algorithm is to…”

“The inputs for this algorithm are…”

“If the details are correct…”

“If the details are incorrect…”

Add your pseudocode or flowchart here.

2.2 Register New User Algorithm
2.2.1 Requirements Checklist

 Inputs: name, email, username, password

 Validate each field

 Check if username/email already exists

 Hash password

 Store user in database

 Output success message

 Justification written

2.2.2 Description

Sentence starters:

“This algorithm collects the following inputs…”

“Validation is carried out by…”

“If the username or email already exists…”

“Finally, the user is stored by…”

Add pseudocode or flowchart here.

2.3 Booking Algorithm (Ticket or Hotel)
2.3.1 Requirements Checklist

 Inputs: date, number of guests / rooms

 Check availability

 Calculate price

 Apply loyalty points (if used)

 Save booking

 Return confirmation or error

 Justification written

2.3.2 Description

Sentence starters:

“The booking algorithm starts by collecting…”

“The system checks availability by…”

“The price is calculated based on…”

“The booking is confirmed when…”

Add pseudocode or flowchart here.

2.4 Algorithm Justification (For Each)

For each algorithm (Login, Register, Booking):

Sentence starters:

“I chose this structure because…”

“This algorithm solves the functional requirement by…”

“Errors are handled by…”

“The flow of input → process → output is…”

“The algorithm is efficient because…”

Add a short paragraph under each algorithm.

3. Error Handling & Validation
3.1 Error Table (Optional but Recommended)
Error Description	Cause	How System Handles It	Expected Outcome
Invalid password	User typed wrong password	Show error message and allow retry	User attempts login again
Blank field	User left input field empty	Display validation message	User fills in all required fields
Date unavailable	Room already booked on that date	Show message and offer alternative	User chooses another date

Sentence starters:

“This error occurs when…”

“The system responds by…”

“The expected outcome is…”

4. Data Requirements
4.1 Data Table
Data Item Name	Type	Function / Purpose	Reason for Inclusion
userID	Integer	Identify user uniquely	Needed as primary key
username	String	Used to login and identify user	Required for login system
passwordHash	String	Store secure version of password	Security requirement
email	String	Contact user and for login recovery	Communication and account recovery
bookingID	Integer	Identify booking	Needed as primary key for bookings
bookingDate	Date	Date of booking	Needed to check availability

You can add more rows for your system.

4.2 Data Model Diagrams
4.2.1 Conceptual Model

List entities only (no attributes):

User

Booking

Room

(Add others if needed)

4.2.2 Logical Model

Entities with attributes and relationships.

Example (you can draw this):

User (UserID, Name, Email, Username, PasswordHash)

Booking (BookingID, UserID, RoomID, Date, Price)

Room (RoomID, RoomType, Capacity)

Relationships:

One User → Many Bookings

One Room → Many Bookings

4.2.3 Physical Model

Show exact tables and data types, plus keys.

Sentence starters:

“The User table will include…”

“The primary key of this table is…”

“The foreign key links…”

Example:

User Table

userID (INT, PK)

name (VARCHAR)

email (VARCHAR, UNIQUE)

username (VARCHAR, UNIQUE)

passwordHash (VARCHAR)

(Add Booking and Room tables similarly.)

5. Testing Plan
5.1 Test Strategy

Sentence starters:

“The purpose of testing is to ensure…”

“This system will be tested using…”

“Normal, extreme, and invalid data will be used to…”

“Users will be involved in testing by…”

5.2 Test Cases Table
Test ID	Feature Tested	Input Data	Test Type (N/E/I)	Expected Outcome	Actual Outcome	Pass/Fail
T1	Login	Valid username & password	Normal	User is logged in and goes to Dashboard		
T2	Login	Wrong password	Invalid	Error message shown, no login		
T3	Register	Blank username	Invalid	Validation message shown		
T4	Booking	Valid date & guest number	Normal	Booking confirmed and stored		
T5	Booking	Fully booked date	Extreme/Invalid	Booking rejected with clear message		
6. Final Submission Checklist

Before you submit, make sure you have:

Visual / Interface Designs

 All UI screens designed

 Navigation flow / user journey described

 Colour and typography justification written

 W3C accessibility features explained

 Front-end requirements listed

 Back-end requirements listed

 Security evaluation written

Algorithms & Data

 Login algorithm (with justification)

 Register algorithm (with justification)

 Booking algorithm (with justification)

 Error-handling explanation or table

 Data table completed

 Conceptual, logical, and physical data models

 Testing explanation and test cases table
