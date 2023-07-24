# Dylan Howell

## EDUCATION  
[Arkansas State University](https://www.astate.edu/), Jonesboro AR  
B.S in Electrical Engineering  

## PROFESSIONAL EXPERIENCE

### Software Development Engineer - Amazon, Nashville TN, 04/2020 - Present
Played an integral role in designing and delivering a platform for externalizing Amazon’s freight network to enterprise shippers. The solution allowed customer ERP systems to programmatically quote and book freight loads utilizing Amazon Logistics as a carrier. Key contributions included cloud architecture design, authentication / authorization mechanisms, and data modeling.  
(**Java, OAuth 2.0, AWS: ECS/Fargate, DynamoDB**)

Built a REST based push notification system for sending freight tracking updates to transportation visibility providers. Solution included SNS / SQS event processing and a custom transformation layer to conform to the data model and auth mechanism of each integration. Included secure storage + rotation of authentication secrets. Implemented a test implementation of a customer system to verify the AuthN/AuthZ, request transformation, and delivery mechanism prior to launch with real integrations / shippers.  
(**Java, OAuth 2.0, Apache Velocity, AWS: SNS, SQS, Lambda, Secrets Manager**)

Wrote a library that redacts sensitive / personally identifiable information(PII) from incoming JSON. Configurable pattern matching was used to detect + redact sensitive fields. Project was born as a DX / automation effort to replace manual PII redaction across several code-bases.  
(**Java**)

---

### Process Control Engineer - Nucor Corporation, Blytheville AR, 05/2017 - 04/2020
Specified hardware, installed/configured hypervisors, and deployed all virtual machines required to startup a $230MM production facility. Wrote automation scripts for server maintenance, backups, and preauthenticated VM remote consoles.  
(**VMware vSphere/ESXi, PowerShell, VEEAM**)

Adapted and extended a suite of services/GUIs bundled with a $65MM mechanical equipment package. Integrated steel production software with batch/ordering business systems. Enhanced data collection/analysis capabilities to ultimately boost product quality and yield. Improved software stability by fixing flaws in data access code and implementing database maintenance tasks.  
(**C#, MS SQL Server, WinForms**)

Composed standalone service that reads production line stops from a field controller via TCP/IP socket communication. Application logged plant downtime in an SQL database with time split amongst different production crews. Made the application highly configurable since we had different use-cases in each production area. Worked with UI team to intgrate with an existing web-app to present the logs in the operations UI.  
(**C#, MS SQL Server, TCP/IP sockets**)

Improved adaptation of steel pickling (acid treatment) math model to quickly converge on correct acid dosing for new steel grades. Deployed additional adaptor for grades high in Silicon. Verified model accuracy by analyzing the results of lab tests.  
(**C++, C#**)

---

### Owner - Qwerty LLC, Jonesboro AR, 01/2013 - 05/2017
Launched an IT consulting company that fulfilled > 200 contracts for fortune 500 customers and government agencies. Executed installation, configuration, and maintenance of various computer/network systems. Handled subcontracts from big players like IBM and Toshiba. Core competencies included Point-Of-Sale, Digital Signage, CCTV, local ISP support, and retail server rack/stack upgrades. Managed full life cycle of projects including site-surveys, negotiating price/SOW, contractor management, and generating as-built documents. 

---

### Energy Engineer - Arkansas State University, Jonesboro AR, 05/2015 - 05/2017
Developed software to interface building automation systems with embedded devices using a Modbus API. Built and integrated embedded HVAC controller that regulates air handlers based on building occupancy using computer vision.  
(**Python, REST APIs, Linux**)

Created embedded controller that reads building automation system alarm signals via digital inputs and sends alerts via email and SMS.  
(**Twilio API, Gmail API, SMTP**)

---

### Software Developer - Tech Friends Inc., 08/2015 - 08/2016
Remediated customer reported UI issues in corrections-facility inmate-accounting software. Implemented grid-view with search/filtering functionality for commissary inventory management.  
(**Visual Basic, WinForms**)

Wrote general purpose HTML-aware text parsing function for company’s internal library. Used in web-app to censor inmate/family messaging web-app without altering the underlying markup.  
(**C#, JavaScript, jQuery, ASP.NET**)

Implemented face tracking/censoring function for inmate video-visitation web-app.  
(**C#, JavasScript, ASP.NET, EmguCV, OpenCV**)

## INDEPENDENT PROJECTS

### Smart Car Seat System
Developed car seat add-on that sends a smart-phone alert when a child is left unattended in a vehicle. System used a microcontroller, load-cells to detect the child, and a Bluetooth module to handle the communication. Presented at “STEM Posters at the Capitol” in Little Rock, AR, and IEEE Future Technologies Conference 2017 in Vancouver, BC, Canada([see FTC 2017 site](https://saiconference.com/Conferences/FTC2017)). (C++, Java, Android, Atmega328P)

### CLI MenuLib
Wrote a small library for auto-generating CLI menus/submenus using function delegates and a user-friendly string for each option. Removes boiler-plate code required to present and evaluate a CLI menu. Inspiration came from writing dozens of CLI menus while testing individual components of a mathematical model application.  
(**C#, .NET Framework**)
