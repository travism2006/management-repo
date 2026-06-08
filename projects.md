<h1 align="center">Personal + Non-personal Projects</h1>

## Projects (non-personal)
&nbsp;

### Custom Document Digital Layout (personal, 2026):
Developed a strict HTML and CSS layout system optimized for physical print assets and media and PDF generation via browser rendering engines. Managed absolute unit positioning to eliminate browser-specific rendering artifacts and prevent accidental pagination errors under nonnegotiable spatial constraints. Designed three modular layout variations using tabular data structures to guarantee cross-browser compatibility and cross-platform fidelity across Windows and Linux environments. This system architecture directly mimics enterprise client-side document generation workflows used for invoices, audit reports, and safety data sheets.


&nbsp;


### Senior Capstone Project (2019):
This was a year-long group project with the objective of providing a secure portal system for a real-world client (ASAP Firewatch), to use for shift management.  This resulted in saving the executives time spent on calling employees to see who could take a shift, to spending that same time towards marketing and sales.  The web application used Python 3 for Django, HTML and CSS, jQuery, Bootstrap 4, and a MySQL Database.  From a security standpoint, the web app used Django’s default SHA256 encryption for password storing, and the team added a Role-Based Permissions using Django Administration to further harden the system boundaries between portals.  Furthermore, to prevent security breaches from SQL Injection, XSS, Cross Site Request Forgery and others, each portal containing forms requiring user input was tested and validated for proper encryption.


&nbsp;



### Risk Assessment and System Security Plan (2017):
A course group project that involved creating a system security plan (SSP) for a mock organization.  As a group we decided to use the Facilitated Risk Assessment Process (FRAP) that focused on the mock organization’s overall IT infrastructure. Organizational standards and federal government standardized guidelines, especially NIST Publication 800-53 and FIPS 140-2, were used in part to generate an SSP plan. Justifications for risk levels and IT security policies were based on the business requirements provided.  The project further analyzed various security concerns and technology issues.  In our analysis, we presented to the mock CEO our rationale behind why there should be on-site IT staff.

&nbsp;

### VMS Pro (2017):
This was a group school project that involved a software development lifecycle to include:  Project definition; Solution design & development; Implementation; Testing; and Evolution/Maintenance.  The objective of this project was to create an application for managing daily IT operations for a vehicle dealership.  Based on requirements, the application would support managing various data types in future installments and support role-based accounts such as administrators and salesfloor employees.  This involved a presentation to the client.  The code utilized Java 8 with Google’s JSON package from Github.  Design patterns used in the application include Builder and Strategy to keep the codebase clean, maintainable, and easy to adapt for potential needs of the client.

&nbsp;


### HungryRobots (2015):
This was a school project with the objective of making a basic website with Dreamweaver, HTML and CSS. I decided to make one for those interested in making healthy fast food decisions by making comparisons across various food chains and franchises (e.g. Starbucks, Panera).  Instead of using the CSS and Dreamweaver version used in coursework, I opted for CSS3, jQuery, AngularJS and using DevTools for UI design work and UI testing. Acknowledging what industry was using, using AngularJS and CSS3 enabled a dynamic website, with an implementation of two-way data binding and integrating a JS framework with that demonstrated MVC fundamentals. My rationale for selecting AngularJS was a proactive choice to realign my learning with the reality of production environments and industry-standard design patterns; implementing its custom directives allowed for reusable UI components, while its built-in dependency injection and basic client-side routing provided hands-on experience with how professional, enterprise systems scale and manage state.

&nbsp;
## Personal Projects
&nbsp;
### Batch Image Scraper (personal, 2021-2024):
This project consists of a decoupled two-part automation pipeline developed and iteratively refactored between 2021 and 2024 to cleanly initialize directories and programmatically fetch sequential media assets. Initially engineered in 2021 as a data retrieval script leveraging Python’s urllib.request and shutil for robust stream-copy file writing, I later modularized it in 2022 by creating a script for environment provisioning. In 2024, I reviewed and adjusted the data workflow, emulating a very lightweight ETL pattern with a light transform before final data loading in the provisioned target directory. This ETL transform focused on handling the dynamic nature of sequential media URLs sometimes having ‘1’ vs ‘01’, requiring a normalizing function and dynamically updating zero-padding (zfill).

&nbsp;

### Digital Image Processing (personal project):
Built an object-identification application with OpenCV and Python for smartphone images. Applied image processing techniques including grayscale filtering, feature extraction, and Canny edge detection to identify and isolate features/objects. Tuned edge detection parameters to improve feature recognition across different image qualities and backgrounds. 
On a larger scale, this project would be relevant to identifying features/objects on the ground from satellite images.

