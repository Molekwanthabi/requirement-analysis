# requirement-analysis
## What is Requirement Analysis?

**Requirement Analysis** is the process of identifying, gathering, and defining the needs or conditions required for a new or modified software product. It ensures that the development team fully understands what the users and stakeholders expect from the system before design and implementation begin.

During this phase, business analysts, project managers, and developers work together to document functional and non-functional requirements. The process often involves activities such as stakeholder interviews, surveys, document analysis, and creating use cases or user stories.

### Importance in the Software Development Lifecycle (SDLC)

Requirement Analysis is a **critical phase** in the SDLC because it lays the foundation for all subsequent stages. Its importance includes:

1. **Clarity of Objectives:** Helps all stakeholders understand what the software should achieve.
2. **Prevents Miscommunication:** Ensures developers and clients share the same expectations.
3. **Saves Time and Cost:** Identifying requirements early reduces errors and rework later in the project.
4. **Guides Design and Development:** Acts as a blueprint for developers and designers to build the system correctly.
5. **Improves Quality:** Leads to a product that meets user needs and business goals effectively.

In short, effective requirement analysis transforms vague ideas into clear, actionable, and testable specifications that guide successful software development.

## Why is Requirement Analysis Important?

Requirement Analysis plays a vital role in the Software Development Lifecycle (SDLC) because it ensures that the final product meets both user expectations and business goals. Without this step, the project risks failure due to unclear or misunderstood requirements.

Here are some key reasons why Requirement Analysis is important:

### 1. Prevents Miscommunication and Errors
By clearly defining what the system should do, Requirement Analysis minimizes misunderstandings between stakeholders, developers, and testers. This reduces costly mistakes and rework later in the project.

### 2. Saves Time and Cost
Properly analyzed and documented requirements help identify potential risks, dependencies, and challenges early in the process. This early insight allows the team to plan better and avoid unnecessary delays and budget overruns.

### 3. Improves Product Quality
When requirements are well understood and validated, the development team can build a system that accurately addresses user needs and performs as expected. This results in a high-quality, reliable, and user-friendly software product.

### 4. Provides a Clear Project Roadmap
Requirement Analysis produces detailed documentation that guides every stage of development — from design to testing. It serves as a reference point for measuring project progress and success.

---

> In summary, Requirement Analysis ensures al

## Key Activities in Requirement Analysis

Requirement Analysis involves several structured activities that help ensure the final system meets user and business needs. The five key activities are:

- **1. Requirement Gathering:**  
  This is the initial step where information about the project’s goals, user needs, and system expectations is collected. It often involves discussions with stakeholders, clients, and end-users to understand what the software must accomplish.

- **2. Requirement Elicitation:**  
  Elicitation goes deeper than gathering — it focuses on uncovering hidden, implicit, or unclear needs through methods like interviews, surveys, workshops, brainstorming, and observatio

## Types of Requirements

In software engineering, requirements are generally divided into two main categories: **Functional Requirements** and **Non-functional Requirements.**  
Both types are essential to ensure the system performs as expected and meets user needs effectively.

---

### 🔹 Functional Requirements

**Definition:**  
Functional requirements describe **what the system should do** — the specific behaviors, features, and operations of the software. They define the system’s functionality from the user’s perspective.

**Examples for a Booking Management Project:**
- The system should allow users to **create, update, and cancel bookings**.
- Users should be able to **search for available rooms or services** by date and location.
- The system must **send booking confirmations and reminders** via email or SMS.
- Administrators should be able to **view, ed**

## Use Case Diagrams

### What is a Use Case Diagram?

A **Use Case Diagram** is a visual representation of the interactions between **users (actors)** and a **system**.  
It helps describe **what the system does** from the user’s perspective — showing the main functions (use cases) and how different users interact with them.

Use case diagrams are part of **Unified Modeling Language (UML)** and are widely used in the **Requirement Analysis** phase to clarify functional requirements.

---

### Benefits of Use Case Diagrams

- **Simplifies communication** between stakeholders and developers.  
- **Clarifies system scope** by showing what is inside and outside the system boundary.  
- **Identifies user roles and goals**, ensuring the software meets actual user needs.  
- **Serves as a foundation** for creating detailed functional requirements and test cases.

---

### Example: Booking Management System Use Case Diagram

The diagram below shows the relationship between the main users (actors) and the core functions (use cases) of a booking management system.

#### **Actors:**
- **Customer:** Books, views, and cancels bookings.  
- **Administrator:** Manages bookings, users, and reports.  
- **System:** Sends notifications and stores booking data.

#### **Use Cases:**
- Create Booking  
- View Booking Details  
- Cancel Booking  
- Manage Users and Reports  
- Send Confirmation Notifications

---

### 📊 Use Case Diagram

![Booking Management System Use Case Diagram](./alx-booking-uc.png)

---

> The diagram visually demonstrates how customers and administrators interact with the booking system, clarifying system functionality during requirement analysis.

Diagram (alx-booking-uc.png)
Use https://draw.io
 (or Lucidchart, Figma, or any UML tool)

Go to https://app.diagrams.net/

Choose "Blank Diagram"

Add elements:

Actors (stick figures):

Customer

Administrator

System boundary box labeled “Booking Management System”

Use Cases (ovals):

Create Booking

View Booking Details

Cancel Booking

Manage Users and Reports

Send Confirmation Notification

Draw lines to show connections:

Customer → Create Booking, View Booking Details, Cancel Booking

Administrator → Manage Users and Reports

System → Send Confirmation Notification

Export your diagram:

Go to File → Export As → PNG

Name it alx-booking-uc.png

## Acceptance Criteria

The project will be considered complete when all the following are met:

- All sections of the README are present and clearly explained:
  - What is Requirement Analysis?
  - Why is Requirement Analysis Important?
  - Key Activities in Requirement Analysis
  - Types of Requirements (Functional & Non-functional)
  - Use Case Diagrams
- The `alx-booking-uc.png` diagram is included and correctly linked.
- GitHub repository is properly set up with remote origin.
- All commits are pushed to the `main` branch.
- The README is well-formatted and easy to read.






Save it in your project folder (requirement-analysis/)
