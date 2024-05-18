 # Event-Management-System
Event Management System
Documentation

INTRIDUCTION
The Event Management System is a software application designed to streamline the organization and coordination of events. It provides users with a platform to efficiently plan, manage, and execute various types of events, such as conferences, weddings, parties, and corporate gatherings. The system facilitates tasks such as event scheduling, venue selection, guest management, budget tracking, and resource allocation. By automating many aspects of event planning and execution, the Event Management System aims to enhance productivity, reduce manual effort, and ensure the smooth execution of events from start to finish.
PURPOSE
The purpose of the Event Management System is to simplify and optimize the process of planning, organizing, and executing events. Its key functionalities include:
Event Creation: Users can create new events by specifying details such as event type, date, time, venue, and expected number of guests.
Event Booking: The system allows users to book events, managing reservations, and keeping track of availability for different dates and venues.
Guest Management: Users can manage guest lists, send invitations, and track RSVPs, ensuring smooth communication and coordination with attendees.
Resource Management: The system helps in managing resources required for events, such as staff, equipment, catering services, and decorations.
Financial Management: It enables budget planning, expense tracking, invoicing, and payment processing, ensuring financial transparency and control throughout the event planning process.
User Authentication and Authorization: The system provides secure access controls, allowing only authorized users to perform specific actions based on their roles and permissions.
Reporting and Analytics: Users can generate reports and analyze event data to evaluate performance, identify trends, and make data-driven decisions for future events.
Communication Tools: The system may include communication tools such as messaging, notifications, and reminders to keep stakeholders informed and engaged throughout the event lifecycle.

SYSTEM OVERVIEW

Components:
1.	User Class
Attributes
•	name: string
•	address: string
•	id: string
•	phone: string
•	date: string
•	payment_advance: float
•	booking_id: int
2.	Event Class:
Attributes
•	time: int
•	stype: char
•	ven: string
•	gs: int
•	EventNumber: int
•	cost: int
•	info: int
•	usr: User (nested class)
3.	EventMen Class (inherits from Event):
Methods
•	checkIn()
•	getAvailEvent()
•	searchUser(char *)
•	checkOut(int)
•	GuestSummary(char *)
4.	Account Class:
Attributes
•	acc_no: int
•	amount: int
•	Methods:
•	Account(): constructor
•	deposit(int num)


Overview of Functionalities

•	Event Management:
Add, search, and delete events.
Check event availability and book events.
•	User Management:
Register users and manage their information.
Handle user bookings, including details like name, address, contact, and payment status.
•	Guest Management:
Manage guest lists and RSVPs.
Provide summaries of guests attending booked events.
•	Financial Management:
Handle event payments, including advance payments and deposits.
Manage account transactions and generate invoices.
•	Resource Management:
Manage resources required for events, such as staff, equipment, and venue details.
•	Reporting and Analytics:
Generate reports on event bookings, payments, and other relevant data.
Analyze event data to identify trends and make informed decisions.
•	Communication:
Facilitate communication between users and event organizers.
Send notifications, reminders, and updates to stakeholders.
•	Security and Authentication:
Ensure secure access to the system with user authentication and authorization mechanisms.
Protect sensitive data and enforce access controls based on user roles and permissions.




Functionality Description

Adding Events:
Allows users to add new events with details such as guest count, time, and venue.
Searching Events: Users can search for events using their unique event numbers.

Booking Events: 
Enables users to book events by providing personal information and making advance payments.

Viewing Available Events: 
Shows available events for booking.

Searching Users:
 Users can search for booked events using their names.

Calculating Event Costs: 
Computes the cost of events based on various factors like guest count, time, and additional services.

Guest Summary: 
Provides a summary of booked guests and information about the event management service.










System Workflow

Users interact with the Event Management System through a user-friendly interface, where they can perform various tasks seamlessly. Here's how they typically interact with the system to perform key actions:

Adding Events:
•	Users access the "Manage Events" section of the system.
•	They input relevant details such as event number, total guests, time, and venue name.
•	Upon submission, the system validates the input and adds the event to the database.
•	Users receive a confirmation message indicating successful event addition.

Booking Events:
•	Users navigate to the "Book Event" section of the system.
•	They search for available events based on criteria like date, venue, or event type.
•	After selecting a suitable event, users provide their details such as name, address, phone number, and date.
•	Users may also make advance payments if required.
•	Upon successful booking, the system updates the event status to "booked" and provides a booking ID for reference.

Viewing Event Details:
•	Users access the "Search Event" or "Available & Booked Event Info" section.
•	They input the event number or search criteria to find the desired event.
•	The system retrieves and displays detailed information about the event, including guest count, venue, date, and booking status.
•	Users can view event details such as user information, booking ID, and payment status.
•	Additionally, users can view available events and their details to make informed booking decisions.

Managing User Information:
•	Users navigate to the "Search User" section to manage user information.
•	They input the user's name or other identifying information to search for existing users.
•	Upon finding the user, they can view or update their details as needed, such as address, phone number, or booking history.
•	
Financial Transactions:
•	Users access the "Costings of Event" section to view event costs and payment details.
•	They input the event number to retrieve the relevant financial information.
•	The system calculates the total cost of the event, including staff, food, venue, and other expenses.
•	Users can make payments or deposits using the integrated payment system, with options like bank transfer or online payment gateways.
















About Us

The Event Management System offers a comprehensive service for organizing various events, ensuring a seamless experience for users. Here's an overview of the service, including contact details, payment methods, and working hours:

Contact Details:
•	Email: syedadilshah1219@gmail.com
•	Phone: 03420474180
•	Address: Gulberg II, Lahore

Payment Methods:
•	JazzCash/EasyPaisa: Users can conveniently make payments using popular mobile financial services like JazzCash and EasyPaisa.
•	Bank Transfer: Payments can also be made through bank transfer to the specified account number.

Working Hours:
•	Days: Saturday to Thursday
•	Opening & Closing Hours: 9:00 AM to 9:00 PM

Additional Information:
•	Customized Decor: The service offers the flexibility to customize event decorations according to the user's preferences, adding a personalized touch to every event.
•	Venue Flexibility: Events can be organized at any venue preferred by the user, providing flexibility and convenience.






KEY FEATURES

Key Features and Functionalities:

Event Booking: 
Users can add and book events, specifying details such as the number of guests, event duration, and venue preference.

Event Search: 
The system allows users to search for specific events by event number, providing details on availability and booking status.

User Management: 
Users can check in for booked events, providing personal details and making advance payments to confirm their bookings.

Event Availability: 
Users can view available events, enabling them to select suitable options for booking.

User Search: 
The system supports user search functionality, allowing users to search for specific events based on user names.

Cost Calculation: 
The system calculates the total cost of events based on factors like the number of guests, event duration, and additional services.

Payment Processing: 
Users can make payments for event bookings through various methods, including JazzCash, EasyPaisa, or bank transfer.

Guest Summary: 
Users can access a summary of booked events, including guest details, facilitating event management and coordination.
