# CS_255
SNHU_CS_255_System_Analysis and Design 


# Driver Pass System

The Driver Pass System is a comprehensive role-based platform designed to streamline the registration, verification, and approval process for drivers within an organization that also includes students, instructors, and administrators. Each role plays a distinct part in the system's workflow, ensuring accountability, transparency, and security.



At the core of the system is the driver onboarding process, which begins with a registration form where drivers submit essential information along with required documentation, such as their license and identification. Once submitted, the application enters a verification workflow managed primarily by administrators, who have full authority to approve, reject, or request additional information. Throughout this process, drivers can log in to a dedicated dashboard to track the real-time status of their applications and receive updates through both email and in-app notifications.



The admin dashboard serves as the control center for managing all driver-related activities. Administrators can review submitted documents, assign review tasks, and oversee application statuses. The system also supports multi-factor authentication to enhance login security and imposes a three-attempt limit on password entry to protect against brute-force attacks.



Instructors have limited access to driver information and may be involved in recommending drivers based on training or assessment data. Students, while having minimal interaction with the driver pass system, may view assigned driver details if relevant to their use case (e.g., for transport coordination).



Technologically, the system is built with a modern stack that includes Next.js for the frontend, Redux Toolkit for state management, and either Rust, Go, or Node.js on the backend. PostgreSQL serves as the primary database. All services are containerized using Docker and deployed via Render, ensuring scalable and isolated environments. The platform emphasizes security through JWT-based authentication, role-based access controls, and secure file handling for sensitive documents.


# Client Requirements

## Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?
Sam and Jennifer, the clients of the Driver Pass System, require a secure and streamlined platform to manage the end-to-end process of driver onboarding and verification. The system should support four key user roles—Admin, Driver, Instructor, and Student—with clearly defined permissions. Drivers must be able to apply, upload necessary documents, and track their application status. Admins need the ability to review and approve these applications, while Instructors may support the process with evaluations. Students may also interact with the system in a limited capacity. The platform must enforce strong authentication, support scalable deployment, and maintain a user-friendly experience across all roles.

# Functional Requirement Overview
## What did you do particularly well?
After engaging with key stakeholders including Sam and Jennifer.
I gathered and translated all business needs into clearly defined functional requirements for the DriverPass application. The platform supports multiple roles—Admin, Student, Instructor, and Driver—and is designed primarily to help students take online driving classes, schedule lessons, and track progress. These requirements guide the development process in building a system that aligns closely with both user needs and business goals.

## If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

If I were to revise one part of the work on this document, I would refine the "Functional Requiremnets" section to be more visual and modular--perhaps breaking it down with flowcharts or use case diagrams.

## How did you interpret the user’s needs and implement them into your system design? Why is it so important to consider the user’s needs when designing?

Considering the user's needs is crucial because it ensures the system is practical and solves real problems. A user's design leads to higher satisfaction, better adoption for later revisions.

## How did you interpret the user’s needs and implement them into your system design? Why is it so important to consider the user’s needs when designing?

I use techniques like stakeholder interviews, requiremnt gathering, and user journey to get a cllear picture of the system's purpose.

In the future, I would continue using agile methodologies, iterative prototyping, and feedback loops to refine the design early and often.