Project Name: SitSmart
Team:Ayanna Garrett-Parent Logan Castelloe-Babysitter
Course: CSC 340
Version: 1.0
Date: 2026-02-11  

1. Overview
SitSmart is a mobile app designed to connect parents with trusted babysitters in the area.The main issue is that parents struggle to find safe and trustworthy service to watch their children. SitSmart provides a secure platform for searching, booking, messaging, and paying babysitters.

Glossary Terms used in the project

Parent: A registered user seeking babysitting service 
Babysitter: A registered user providing childcare.
Bookign: proccess of booking a babysitter.
Verification: Proccess of confiriming user idenity.

Primary Users / Roles.

Customer (Parent) — Create a profile, Find, book, and pay babysitters safely and efficiently 
Provider (Babysitter) — Create a profile, manage availability, accept bookings, recieve payment.

Scope (this semester).

<- Create and manage user accounts (Parent/Babysitter)>
<- Babysitter onboarding; create/edit profile with bio, hourly rate, availability, and experience>
<- Browse and search babysitters with filtering/sorting(location, rate, rating, availability)>
<- Send, accept, and decline booking requests.>
<- Manage bookings (view upcomming, cancel booking)>
<- In-app messaging between parents and babysitters.>
<-Reviews(parents write reviews; babysitter can respond)

Out of scope (deferred).

<-Background check services>
<-Live GPS tracking>
<-Video calling>
<-Advanced dashboard>



2. Functional Requirements (User Stories)


2.1 Customer Stories
US‑CUST‑001 —
Story: As a parent, I want to create a account so that I can book babysitters.
Acceptance:

Scenario: <Register with vaild information>
  Given <I am a new user>
  When  <I provide vaild email and password>
  Then  <my account is created and I can log in>

US‑CUST‑002 —
Story: As a parent, I want to search for babysitters so that I can find available providers.
Acceptance:

Scenario: <Search babysitters by availability>
  Given <babysitters in the area>
  When  <I sort by availability>
  Then  <babysitters with open bookings appear first>

US‑CUST‑003 —
Story: As a parent, I want to book a babysitter so that I can secure childcare.
Acceptance:

Scenario: <Booking the babysitter>
  Given <I have chosen the sitter>
  When  <I submit a booking request>
  Then  <the babysitter receives the request>

US‑CUST‑004 —
Story: As a parent, I want to leave a review so that I can share my experience.
Acceptance:

Scenario: <Search babysitters by availability>
  Given <the job was finished>
  When  <I submit a rating and comment>
  Then  <the review appears on the sitter's profile>

US‑CUST‑005 —
Story: As a parent, I want to send messages to the babysitter so that we can discuss booking details before confirming 
Acceptance:

Scenario: <Communicating with the sitter>
  Given <I am logged in as a parent>
  And   <I am viewing a babysitter's profile>
  When  <I type a message and press "Send">
  Then  <the babysitter receives the message>
  And   <the message is saved in the conversation history>

2.2 Provider Stories
US‑PROV‑001 —
Story: As a provider, I want … so that …
Acceptance:

Scenario: <happy path>
  Given <preconditions>
  When  <action>
  Then  <observable outcome>
US‑PROV‑002 —
Story: As a provider, I want … so that …
Acceptance:

Scenario: <happy path>
  Given <preconditions>
  When  <action>
  Then  <observable outcome>

3. Non‑Functional Requirements (make them measurable)
Performance: 
-The system will load user dashboards within 3 seconds.
-Booking requests will proccess within 2 seconds.

Availability/Reliability: 
-System uptime will be at least 99%.
-User data will be backed up daily.

Security/Privacy: 
-All passwords are encrypted 
-Payment proccessing will comply with PCI-DSS standards.
-Users must verify email before having full access.

Usability: 
-The application will follow standard accessibility guidelines.

4. Assumptions, Constraints, and Policies
-Modern browsers (latest Chrome/Firefox/Edge/Safari); stable connectivity.
-user has internet access
-comply with child safety laws 
-Policies: content guidelines(no harrassment); cancellation no later than 2 weeks before booking date; sitters have the right to decline bookings to maintain their schedule.

3. Non‑Functional Requirements (make them measurable)
Performance: description
Availability/Reliability: description
Security/Privacy: description
Usability: description
4. Assumptions, Constraints, and Policies
list any rules, policies, assumptions, etc.
5. Milestones (course‑aligned)
M2 Requirements — this file + stories opened as issues.
M3 High‑fidelity prototype — core customer/provider flows fully interactive.
M4 Design — architecture, schema, API outline.
M5 Backend API — key endpoints + tests.
M6 Increment — ≥2 use cases end‑to‑end.
M7 Final — complete system & documentation.
6. Change Management
Stories are living artifacts; changes are tracked via repository issues and linked pull requests.
Major changes should update this SRS.
