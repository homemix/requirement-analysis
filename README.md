# Requirement Analysis in Software Development

This repository explores the **requirement analysis phase** in software development — one of the most critical steps in ensuring that a project aligns with user needs and business goals.

It covers:
- Understanding user and stakeholder requirements
- Defining functional and non-functional requirements
- Creating requirement documentation
- Tools and techniques used during requirement gathering and analysis

This project serves as a foundation for understanding how clear and accurate requirements drive successful software delivery.

## What is Requirement Analysis?

**Requirement Analysis** is the process of identifying, gathering, and defining what a software system should do. It focuses on understanding the needs and expectations of end users, stakeholders, and the business to ensure the final product solves the right problem.

During this phase, developers, analysts, and clients collaborate to answer key questions such as:
- What problem are we trying to solve?
- Who will use the system?
- What features and functionalities are required?
- What constraints or limitations exist?

### 🔹 Importance in the Software Development Lifecycle (SDLC)

Requirement Analysis is a **crucial foundation** of the SDLC because it directly influences the project’s success. Here’s why it matters:

1. **Clarity and Alignment:** It ensures all stakeholders have a shared understanding of the system’s goals and scope.
2. **Reduced Rework:** Well-defined requirements minimize costly changes and misunderstandings later in development.
3. **Accurate Planning:** Clear requirements help project managers estimate time, budget, and resources effectively.
4. **Quality Assurance:** It provides measurable criteria for testing and validation, ensuring the final product meets user needs.
5. **Better Communication:** Acts as a bridge between clients, developers, and testers, promoting transparency throughout the project.

## Why is Requirement Analysis Important?

Requirement Analysis is one of the most **crucial stages** in the Software Development Lifecycle (SDLC). It determines how well the final product will meet user expectations and business objectives. Below are key reasons why this phase is so important:

### 1. Ensures a Clear Understanding of Project Goals
By thoroughly analyzing requirements, all stakeholders — including developers, clients, and users — gain a shared understanding of what the system should achieve. This clarity prevents confusion and keeps the project aligned with its intended purpose.

### 2. Reduces Development Costs and Rework
Identifying and resolving issues during the requirement phase is far less costly than fixing them later in development. Well-defined requirements help avoid misunderstandings, unnecessary features, and scope creep.

### 3. Improves Project Planning and Estimation
Accurate requirements enable teams to estimate time, budget, and resources effectively. This leads to better scheduling, smoother workflows, and predictable project outcomes.

### 4. Enhances Software Quality
When requirements are specific and testable, developers can create systems that meet user needs more precisely. It also helps testers validate the software against clearly defined acceptance criteria.

---

**Requirement Analysis** acts as the foundation of a successful software project. A clear and detailed understanding of what needs to be built ensures that the final product is both functional and valuable to its users.

## Key Activities in Requirement Analysis

The Requirement Analysis phase involves several important activities that help ensure the system meets user and business needs effectively. Below are the five key activities involved:

- ### **1. Requirement Gathering**
    - This is the initial step where information about the project’s goals, features, and constraints is collected.
    - Stakeholders, end-users, and clients are interviewed to understand their expectations and needs.
    - Techniques such as questionnaires, surveys, and document analysis are often used.

- ### **2. Requirement Elicitation**
    - Focuses on extracting detailed information from stakeholders through discussions, workshops, and brainstorming sessions.
    - Helps uncover hidden needs or assumptions that may not have been expressed during gathering.
    - Encourages collaboration and communication between clients and the development team.

- ### **3. Requirement Documentation**
    - Involves recording and organizing all gathered and elicited requirements in a structured format.
    - Common documents include the Software Requirement Specification (SRS).
    - Documentation ensures that all stakeholders have a clear, consistent understanding of the requirements.

- ### **4. Requirement Analysis and Modeling**
    - At this stage, requirements are analyzed for feasibility, clarity, and completeness.
    - Modeling tools such as data flow diagrams (DFD), use case diagrams, or entity-relationship diagrams (ERD) may be used.
    - The goal is to represent system functionality and interactions visually for better understanding.

- ### **5. Requirement Validation**
    - Ensures that all documented requirements accurately reflect user needs and are achievable within project constraints.
    - Activities include reviews, walkthroughs, and prototyping.
    - Helps identify inconsistencies, ambiguities, or missing requirements early in the process.

---

These activities together ensure that the final software product aligns with user expectations, is technically feasible, and supports business objectives effectively.

## Types of Requirements

In software development, requirements are generally classified into **Functional** and **Non-functional** requirements. Both are essential for ensuring that the system performs as intended and meets user expectations.

---

### **1. Functional Requirements**

Functional requirements define **what the system should do** — the specific behavior, features, and interactions of the system.  
They describe how the system responds to user inputs, processes data, and delivers expected outputs.

**Examples (from the Booking Management Project):**
- The system should allow users to create, update, and cancel bookings.
- The admin should be able to view all active and completed bookings.
- The system should send email or SMS notifications when a booking is confirmed or canceled.
- The platform should allow users to make payments securely using integrated payment gateways (e.g., M-Pesa, PayPal).
- The system should generate a report of daily and monthly bookings.

---

### **2. Non-functional Requirements**

Non-functional requirements define **how the system should perform** rather than what it does.  
They describe the quality attributes, performance, usability, and reliability of the system.

**Examples:**
- The system should handle up to **500 concurrent users** without performance degradation.
- The response time for loading booking details should be **less than 3 seconds**.
- The platform should be available **99.9% of the time** to ensure high reliability.
- All user data should be stored securely with **encryption and regular backups**.
- The user interface should be **mobile-responsive and easy to navigate**.

---

While **functional requirements** define the system’s core capabilities, **non-functional requirements** ensure the system’s efficiency, reliability, and user satisfaction.

## Use Case Diagrams

### **What is a Use Case Diagram?**
A **Use Case Diagram** is a visual representation of the interactions between users (**actors**) and the system.  
It helps to capture the **functional requirements** by illustrating what the system does (use cases) and who interacts with it.

### **Benefits of Use Case Diagrams**
- **Simplifies understanding:** Provides a clear and visual way to represent system behavior.
- **Improves communication:** Bridges the gap between technical teams and non-technical stakeholders.
- **Identifies system boundaries:** Clearly defines what is inside or outside the scope of the system.
- **Assists in validation:** Helps confirm that all user interactions and system functions are captured correctly.

---

### **Use Case Diagram for Booking Management System**

The diagram below represents the main actors and use cases for the **Booking Management System**.

**Actors:**
- **Customer:** Makes, modifies, and cancels bookings.
- **Admin:** Manages users, bookings, and system reports.
- **Payment Gateway:** Processes payments for confirmed bookings.

**Use Cases:**
- Create Booking
- Update Booking
- Cancel Booking
- Make Payment
- Generate Report
- Manage Users

---



