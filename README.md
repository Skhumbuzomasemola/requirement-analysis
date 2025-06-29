# requirement-analysis
What is Requirement Analysis?
Requirement prioritization is based on their importance and impact on the project.
feasibility analysis is assessing the feasibility of requirements in terms of technical, financial and time constraints.
modeling is creating models ( e.g , data flow diagrams, entity relationship diagrams) to visualize and analyze requirements.
Why is Requirement Analysis Important?
Clarity and understanding: it helps in understanding what the stakeholders expect from the software reducing ambiguity.
Scope definition: clearly defines the scope of the project, which helps in preventing scope creep.
Basis for design and development: provides a solid foundation for designing and developing the system.
Key Activities in Requirement Analysis.
- Requirement Gathering: Interviews: Conducting interviews with stakeholders to gather detailed information about their needs and expectations.
Surveys/Questionnaires: Distributing surveys to collect requirements from a larger audience.
Workshops: Organizing workshops with stakeholders to discuss and gather requirements.
Observation: Observing end-users in their working environment to understand their needs.
Document Analysis: Reviewing existing documentation and systems to understand current functionalities and requirements.
-Requirement Elicitation: Brainstorming: Conducting brainstorming sessions to generate ideas and gather requirements.
Focus Groups: Holding focus group discussions with selected stakeholders to gather detailed requirements.
Prototyping: Creating prototypes to help stakeholders visualize the system and refine their requirements.
-Requirement Documentation: Requirement Specification Document: Creating a detailed document that lists all functional and non-functional requirements.
User Stories: Writing user stories to describe functionalities from the user’s perspective.
Use Cases: Creating use case diagrams to show interactions between users and the system.
-Requirement Analysis and Modeling: Requirement Prioritization: Prioritizing requirements based on their importance and impact on the project.
Feasibility Analysis: Assessing the feasibility of requirements in terms of technical, financial, and time constraints.
Modeling: Creating models (e.g., data flow diagrams, entity-relationship diagrams) to visualize and analyze requirements.
-Requirement Validation: Review and Approval: Reviewing the documented requirements with stakeholders to ensure accuracy and completeness.
Acceptance Criteria: Defining clear acceptance criteria for each requirement to ensure they meet the expected standards.
Traceability: Establishing traceability matrices to ensure all requirements are addressed during development and testing.
Types of Requirements
Functional Requirements
Search Properties: Users should be able to search for properties based on various criteria such as location, price, and availability.
Booking System: Users should be able to book properties, view booking details, and manage their bookings.
Non-functional Requirements
Usability: The application should have an intuitive UI/UX, making it easy for users to navigate and perform tasks.
## Use Case Diagrams

Use Case Diagrams are a fundamental tool in requirement analysis that visually represent the interactions between users (actors) and a system. They illustrate the system's functionality from an end-user perspective, showing who can use the system and what they can do with it.

### Benefits of Use Case Diagrams
- Provides clear visualization of system requirements from a user's perspective
- Helps identify system actors and their interactions
- Facilitates communication between stakeholders
- Serves as a foundation for system design and testing
- Identifies system boundaries and scope

### Booking System Use Case Diagram

Below is a use case diagram illustrating the key functionalities of our booking system:

![Booking System Use Case Diagram](alx-booking-uc.png "Use case diagram showing actors (Customer, Admin) interacting with booking system through various use cases including Search Rooms, Book Room, Cancel Booking, Manage Bookings, and Generate Reports")

### Diagram Components Explained
1. Actors:
   - Customer: Primary user who interacts with the booking system
   - Admin: System administrator who manages bookings and reports

2. Use Cases:
   - Search Rooms: Allows customers to find available rooms based on criteria
   - Book Room: Enables customers to reserve selected rooms
   - Cancel Booking: Permits cancellation of existing reservations
   - Manage Bookings: Admin functionality to view and modify bookings
   - Generate Reports: Admin feature to create booking statistics and revenue reports

3. Relationships:
   - Arrows show which actor can perform which use case
   - Connections between use cases show functional dependencies



