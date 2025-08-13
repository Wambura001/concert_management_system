# concert_management_system    
 CONCERT MANAGEMENT SYSTEM  
 Enhancing Event Organization and Stakeholder Engagement
BACHALOR’S OF SMART COMPUTING (BSC)
DATA BASE MANAGEMNT AND SYSTEM
FINAL PROJECT 
BY  
SIRINCHA MESHACK WAMBURA (2317422)
ROKA GANGA (2317404) 
KHAMIS ABDULKARIM ALI (2317437) 
AKTER SAMIA (2317455)
CHERUIYOT LEON KIPKORIR (2317435) 
SHIHABUR RAHMAN (2317255)
PROFESSOR ABSI
Table of Contents
1. Introduction ............................................................................................................4
2. Team Overview & Gantt Chart..................................................................................4
3. Data Collection Methods.........................................................................................5
4. Problem Analysis ....................................................................................................5
5. Feasibility Analysis .................................................................................................6
Technical Feasibility: .........................................................................................................6
Economic Feasibility:.........................................................................................................6
Operational Feasibility:......................................................................................................6
6. System Design ........................................................................................................7
6.1 Database Design ..........................................................................................................7
6.2 Entity-Relationship Diagram (ERD) ..............................................................................11
6.3 Use Case Diagram ......................................................................................................12
7. Demonstration...................................................................................................... 13
8. Conclusion............................................................................................................ 15
9. References............................................................................................................ 15
Table Of Figures
Figure 1.Sytem Design ..................................................................................................7
Figure 2.Event Table......................................................................................................7
Figure 3.Venue Table .....................................................................................................8
Figure 4.Artist Table ......................................................................................................8
Figure 5.Ticket Tabl .......................................................................................................9
Figure 6.Attendane Table...............................................................................................9
Figure 7.Sponsors Table ................................................................................................9
Figure 8.Merchandise Table......................................................................................... 10
Figure 9.Feedback Table ............................................................................................. 10
Figure 10.ERD Diagram ............................................................................................... 11
Figure 11.Use Case Diagram ....................................................................................... 12
Figure 12.Event Page List............................................................................................. 13
Figure 13.Event Details And Payment Page ................................................................... 14
Figure 14.Feedback Page ............................................................................................ 14
1. Introduction
The Concert and Event Management System is a web-based platform developed to
improve the organization and delivery of music events. It supports event organizers in
planning and promoting events, simplifies ticket purchasing for attendees, and facilitates
collaboration among artists, sponsors, and the audience.
2. Team Overview
Tasks Progress
Here’s what we need to get done:
1. Requirements Gathering: We need to figure out exactly what the client wants.
2. Data Collection: Grab all the data we need to build the system.
3. System Design: This is where we plan out how the system will look and work (like
creating
diagrams).
4. Feasibility Analysis: Can we actually build this thing within the time and budget?
5. System Testing: Let’s make sure everything works as it should.
6. Final Report: Put together a report that sums up everything.
7. Presentation: Get ready to show it off!
Who’s Doing What
Here’s who’s handling each task:
T1: Doing Requirements Gathering and System Design (Data Models, ERD)
T2: Collecting Data and working on Problem Analysis
T3: Checking if the project is feasible and doing Unit Testing
T4: Doing the integration tests and putting together the Final Report
T5: Helping with System Design (DFD, UI) and Final Report
T6: Preparing the Presentation
3. Data Collection Methods
Methods Used:
o Interviews: Discussions with event organizers, artists, and sponsors to gather
needs.
o Surveys: Feedback from past event attendees about ticketing, feedback, and
general experience.
o System Analysis: Studied existing event management platforms.
Sample Interview Questions:
o What challenges do you face when organizing concerts?
o How are tickets currently sold and managed?
o How is artist and sponsor communication handled?
o What kind of attendee feedback is collected, if any?
4. Problem Analysis
Current Issues Identified:
o Manual event and ticket management causes inefficiencies.
o Poor communication channels between organizers, artists, and sponsors.
o Lack of structured attendee feedback collection.
Opportunities for Improvement:
o Centralized system for event and user management.
o Online ticket sales with real-time tracking.
o Streamlined artist and sponsor coordination.
o Structured post-event feedback collection and analysis.
Project Objectives:
o Enable efficient event creation and management.
o Allow attendees to purchase tickets and provide feedback online.
o Create direct communication channels among stakeholders.
5. Feasibility Analysis
Technical Feasibility:
o Database: SQLite with normalized schema and relational integrity
o Backend: Django
o Frontend: React with dynamic components
o Integration: Axios used for API calls
Economic Feasibility:
o Low Development Cost: Open-source tools used throughout
o High ROI: Automation will save time and reduce manual labor
o Deployment: Hosted on Heroku and Netlify (cost-effective)
Operational Feasibility:
o System is user-friendly and requires minimal training
o Can be integrated easily into existing workflows
o Scalable and adaptable for large events
6. System Design
6.1 Database Design
Figure 1.Sytem Design
Tables & Key Attributes:
1. Events:
EventID, Name, Date, Time, VenueID, Price
Figure 2.Event Table
2. Venues:
VenueID, Location, Capacity
Figure 3.Venue Table
3. Artists:
ArtistID, Name, Genre, Biography
Figure 4.Artist Table
4. Tickets:
TicketID, EventID, AttendeeID
Figure 5.Ticket Tabl
5. Attendees:
AttendeeID, Name, Email, Phone
Figure 6.Attendane Table
6. Sponsors:
SponsorID, Name, ContactInfo, Amount
Figure 7.Sponsors Table
7. Merchandise:
ItemID, EventID, ItemName, Price
Figure 8.Merchandise Table
8. Feedback:
FeedbackID, EventID, AttendeeID, Rating, Comments
Figure 9.Feedback Table
6.2 Entity-Relationship Diagram (ERD)
Figure 10.ERD Diagram
Key Relationships:
o One Venue hosts many Events
o One Artist can perform in multiple Events
o One Event has many Tickets, Feedbacks, and Merchandise
o One Attendee can buy multiple Tickets and leave Feedback
6.3 Use Case Diagram
Figure 11.Use Case Diagram
Actors & Use Cases:
o Organizer: Create/manage events, manage users, view analytics
o Attendee: View events, buy tickets, give feedback
o Artist: Update profile, view event schedule
o Sponsor: View sponsorship deals, ROI metrics
7. Demonstration
Frontend Pages:
o Event List Page: Lists all upcoming concerts with ticket options
Figure 12.Event Page List
o Event Details Page: Shows artist info, venue, price
Figure 13.Event Details And Payment Page
o Feedback Form: Submits attendee feedback after the event
Figure 14.Feedback Page
System Integration:
o React frontend integrated with Node.js backend using REST API
o Secure login/authentication for different roles
o Responsive design for desktop and mobile
8. Conclusion
The Concert and Event Management System effectively addresses the needs of modern
event organizers, performers, and audiences. It streamlines event logistics, enhances
communication, and centralizes data handling. The system is technically sound, scalable,
and ready to evolve with future needs such as mobile integration and advanced analytics.
9. References
1. Node.js Foundation, "Node.js Documentation,"
2. Meta Platforms, Inc., "React Documentation," [Online]. Available:
https://reactjs.org/docs/. [Accessed: 13-Jun-2025].
3. Eventbrite, "Event Management Guide," [Online]. Available: Provide full URL if
available. [Accessed: 13-Jun-2025].
4. G. Shelly and H. J. Cashman, Systems Analysis and Design, 9th ed., Boston, MA:
Cengage Learning, 2012.

