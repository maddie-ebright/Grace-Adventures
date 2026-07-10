# Grace-Adventures

## Live Demo

🔗 **Live Website:** https://grace-wander-quest.lovable.app

**Note:** This demonstration does **not** contain real Grace Adventures data.
>
> To protect the organization's privacy and security, all names, donor records, participant information, financial data, reservation details, and other sensitive information have been replaced with fictional sample data created solely for demonstration purposes.
>
> The website accurately represents the functionality, workflow, user interface, and analytics capabilities of the application, but none of the data shown belongs to Grace Adventures or any real individual.

## Project Overview

This project was developed for Grace Adventures, a nonprofit organization operating multiple campuses and serving thousands of participants each year. The goal was to improve how the organization identifies and manages VIP guests and donors by bringing information together from multiple systems into one centralized platform.

I developed a web-based analytics platform using **Lovable** that allows staff to more efficiently identify VIPs, review important engagement information, and support relationship management through a simple, user-friendly interface.

---

## Business Problem

Grace Adventures stores information across multiple systems, including:

- Virtuous CRM
- Circuitree
- ResNexus

Because data existed across separate platforms, identifying highly engaged donors or participants required manually searching multiple systems and comparing records.

The organization needed a faster, more consistent way to identify VIPs and access important information.

---

## What I Developed

I developed a web-based VIP identification and analytics platform using **Lovable** and implemented an authenticated API integration to connect the application with an external data source.

The platform was designed to:

- Centralize important information from three different data platforms into one website
- Identify individuals who meet defined VIP criteria
- Retrieve authorized data through an authenticated API connection
- Present data through an intuitive dashboard
- Reduce manual searching across multiple systems
- Support faster and more consistent decision-making
---

## API Integration

To power the application, I obtained an API key from the external platform and implemented it within the website to securely authenticate requests and retrieve authorized data.

The API integration included:

- Configuring API authentication using a private API key
- Connecting the API to the Lovable web application
- Retrieving authorized data from the external platform
- Structuring API responses for use within the dashboard
- Protecting credentials by excluding API keys from the public GitHub repository

The API key functions as a secure credential and is **not included** in this repository to protect organizational security and prevent unauthorized access.

---

## VIP Identification Logic

The dashboard identifies VIPs using predefined business rules, including:

- Donors with more than three years of giving history
- Recurring donors with at least four gifts per year
- Individuals who donated at least $1,000 during any of the previous three years
- Individuals who donated at least $1,500 cumulatively over the previous three years

These rules created a consistent, repeatable process for identifying important relationships.

---

## Tools & Technologies

- Lovable
- Python
- API Integration
- Business Analytics
- Data Cleaning
- Data Matching
- GitHub

---

## What the Project Accomplished

This project transformed fragmented organizational data into a centralized decision-support tool.

The platform:

- Reduced manual searching across multiple systems
- Standardized the organization's VIP identification process
- Improved access to important donor and participant information
- Demonstrated how API integrations can automate data retrieval
- Created a scalable foundation for future analytics and automation
- Enabled staff to spend more time building relationships and less time searching for information

Rather than simply creating a website, this project demonstrated how web development, API integration, and business analytics can be combined to solve a real operational challenge.

---

## Data Privacy

Because this project uses private organizational information, this public repository does **not** include:

- API keys
- Authentication credentials
- Donor information
- Participant records
- Organizational databases
- Sensitive business data

Screenshots included in this repository use blurred or sample data to protect privacy while demonstrating the application's functionality.

---

## Skills Demonstrated

- Web Application Development
- API Integration & Authentication
- Business Analytics
- Dashboard Development
- Data Cleaning
- Data Matching
- Data Privacy & Security
