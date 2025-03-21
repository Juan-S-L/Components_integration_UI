# Components Integration UI

This repository contains the implementation of the evaluative event "Moment 1" for the course Desarrollo de sistemas distribuidos. The project focuses on integrating various UI components using PrimeFaces and Java EE (Jakarta EE) technologies.

---

## **Project Overview**

The goal of this project was to create a dynamic and interactive user interface using PrimeFaces, a popular JavaServer Faces (JSF) framework. The main feature implemented is a **Schedule Component**, which allows users to manage and visualize events in a calendar view. The configuration and customization of the schedule were inspired by the PrimeFaces Showcase example available at:

[PrimeFaces Schedule Configuration Example](https://www.primefaces.org/showcase/ui/data/schedule/configuration.xhtml?jfwid=e3903)

---

## **Technologies Used**

The following tools and technologies were used to develop this project:

- **Java EE (Jakarta EE):** The backend logic was implemented using Java EE, specifically CDI (Contexts and Dependency Injection) and JSF (JavaServer Faces).
- **PrimeFaces:** A powerful UI framework for JavaServer Faces that provides a rich set of components, including the Schedule component used in this project.
- **Maven:** For dependency management and project building.
- **Git & GitHub:** For version control and collaboration.
- **Eclipse IDE:** The primary development environment used for coding and debugging.
- **JBoss/WildFly:** The application server used to deploy and run the project.

---

## **Key Features Implemented**

1. **PrimeFaces Schedule Component:**
   - A fully functional calendar that allows users to view, add, edit, and delete events.
   - Customizable settings such as time format, slot duration, and event overlap.
   - Integration with AJAX for seamless updates without page reloads.

2. **Dynamic Configuration:**
   - The schedule component was configured using the PrimeFaces Showcase example as a reference.
   - Customizations include:
     - Setting the initial view (day, week, month).
     - Configuring time zones and locale settings.
     - Enabling drag-and-drop and resizing of events.

3. **Event Management:**
   - Users can create new events with titles, descriptions, and specific time slots.
   - Events can be edited or deleted dynamically using AJAX.

---

## **How to Run the Project**

To run this project locally, follow these steps:

1. **Prerequisites:**
   - Java Development Kit (JDK) 11 or higher.
   - Maven installed.
   - An application server like JBoss/WildFly.

2. **Clone the Repository:**
   ```bash
   git clone https://github.com/Juan-S-L/Components_integration_UI.git
