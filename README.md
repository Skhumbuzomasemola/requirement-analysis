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

Use Case Diagrams are part of the Unified Modeling Language (UML) used during the Requirement Analysis phase of software development. They visually represent how users (actors) interact with a system through specific functions (use cases).

### 📌 What They Show:
- **Actors**: Users or external systems that interact with the application
- **Use Cases**: The operations or services provided by the system
- **Relationships**: How actors are linked to each function

### 🎯 Benefits of Use Case Diagrams
- **Clear Communication**: Easy for both technical and non-technical stakeholders to understand
- **Requirement Validation**: Ensures all user goals are represented
- **Scope Definition**: Defines system boundaries and key functionalities
- **Planning Support**: Guides developers and testers on what features to build and validate

### 🧾 Booking System Use Case Diagram

The following diagram shows key interactions within the booking system, including customers, admins, and the payment processor.

![![Image](https://github.com/user-attachments/assets/de0d23d3-72f7-455b-9521-d4ae924b7749)](./alx-booking-uc.png)
Acceptance Criteria.
Write about the importance of Acceptance Criteria in Requirement Analysis.
1. Clarify Requirements
Acceptance criteria remove ambiguity by providing clear, testable statements about what a system should do. This helps both stakeholders and developers avoid misunderstandings and ensures everyone shares the same vision.

2. Guide Development
They serve as a checklist for developers, guiding implementation and ensuring all required features are built to meet user needs. It helps developers stay focused and avoid scope creep.

3. Support Testing and Validation
Acceptance criteria are the foundation for test case creation. QA teams use them to validate that the software behaves as expected and meets business needs. If a requirement meets its acceptance criteria, it passes the quality check.

4. Enable Agile Processes
In Agile methodologies, well-defined acceptance criteria allow for better estimation, sprint planning, and tracking progress. They help determine when a user story is "done," supporting iterative development.

5. Facilitate Communication
By involving all stakeholders in defining acceptance criteria, it promotes better collaboration and communication between product owners, developers, testers, and clients.

6. Reduce Rework
Clear expectations reduce the chances of delivering incomplete or incorrect functionality, thus minimizing costly rework and delays later in the development cycle.
Feature: Checkout Functionality
Acceptance Criteria
Successful Checkout Trigger

Given that the booking status is “active,”

When the user clicks the “Check Out” button,

Then the system should update the booking status to “completed”.

Final Bill Displayed

Given that the user initiates checkout,

When the checkout is processed,

Then the system should generate and display a final bill that includes all charges (e.g., room/service fees, taxes, and any extras).

Payment Verification

Given that the user has an outstanding balance,

When they attempt to check out,

Then the system should verify that payment is complete before allowing the checkout to finalize.

Confirmation Receipt

Given a successful checkout,

When the system confirms it,

Then a checkout confirmation email should be sent to the user with booking details and a receipt.

Prevent Early Checkout

Given the user attempts to check out before the allowed time (e.g., before 10:00 AM checkout time),

When the checkout button is clicked,

Then the system should prompt the user with a warning or restriction message (or additional charge notification if applicable).

Admin Notification

Given a user completes checkout,

When the status updates to “completed,”

Then the admin panel should reflect this change and notify the assigned staff








