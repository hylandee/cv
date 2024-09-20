# Dylan Howell

## EDUCATION  
[Arkansas State University](https://www.astate.edu/), Jonesboro AR  
B.S. in Electrical Engineering  

## PROFESSIONAL EXPERIENCE

### Software Development Engineer - Amazon, Nashville TN
*L5 SDE: 07/2022 - Present*
*L4 SDE: 04/2020 - 07/2022*

Developed webhook integration with external load boards to allow Amazon to consume freight "**R**equests **f**or **Q**uote(RFQ)" and asynchronously respond with bid requests. Scope included exposing secure API access to third party companies, and validating, filtering, and transforming RFQ data. Addtionally implemented a hot-swappable configuration and persistence layer. Integrated with several Amazon-internal microservices for validation / freight pricing calculation. As our service was mostly I/O bound I took it as an opportunity to learn Kotlin coroutines.
(**Kotlin, OAuth 2.0, AWS: API Gateway, Cognito User Pools, ECS/Fargate, SQS, DynamoDB, AppConfig**)

Authored post-mortems on high severity production issues and drove action items to completion across sister teams. Example: Several interconnected microservcies faced data consistency issues resulting in duplicate orders being created. Delivered solution in away team codebases to make all affected services / APIs idempotent, raising the bar of API development across our organization.
(**Java, DynamoDB**)

Played an integral role in designing and delivering a platform for externalizing Amazon’s freight network to enterprise shippers. The solution allowed customer ERP systems to programmatically quote and book freight loads utilizing Amazon Logistics as a carrier. Key contributions included cloud architecture design, authentication / authorization mechanisms, and data modeling.  
(**Java, OAuth 2.0, AWS: ECS/Fargate, DynamoDB**)

Built a REST based push notification system for sending freight tracking updates to transportation visibility providers. Solution included AWS SNS / SQS event processing and a custom transformation layer to conform to the data model and auth mechanism of each integration. Included secure storage + rotation of authentication secrets. Implemented a test implementation of a customer system to verify the AuthN/AuthZ, request transformation, and delivery mechanism prior to launch with real integrations / shippers. Wrote Python scripts to help oncall engineers automate interactions with AWS APIs.
(**Java, Python, OAuth 2.0, Apache Velocity, AWS: SNS, SQS, Lambda, Secrets Manager**)

Wrote a library for redacting sensitive / personally identifiable information(PII) from incoming JSON. Configurable pattern matching was used to detect + redact sensitive fields. Project was born as a DX / automation effort to replace hard-code data redaction across several codebases.
(**Java**)

---

### Process Control Engineer - Nucor Corporation, Blytheville AR, 05/2017 - 04/2020
Adapted and extended a suite of services/GUIs bundled with a $65MM mechanical equipment package. Wrote middleware software to integrate steel production automation servers with batch/ordering business systems. Productionalized database code and reduced database faults to zero.
(**C#, MS SQL Server, WinForms**)

Composed standalone service that reads production line stops from a field controller via TCP/IP socket communication. Application logged plant downtime in an SQL database with time split amongst different production crews. Made the application configurable per production area. Worked with UI team to intgrate with an existing web-app to present the logs in the operations UI.
(**C#, MS SQL Server, TCP/IP sockets**)

Improved adaptation of steel pickling (acid treatment) math model to quickly converge on correct acid dosing for new steel grades. Deployed additional adaptor for grades high in Silicon. Verified model accuracy by analyzing the results of lab tests.  
(**C++, C#**)

---

### Owner - Qwerty LLC, Jonesboro AR, 01/2013 - 05/2017
Launched an IT consulting company that fulfilled > 200 contracts for fortune 500 customers and government agencies(I was moonlighting during college). Executed installation, configuration, and maintenance of various computer/network systems. Handled subcontracts from big players like IBM and Toshiba. Core competencies included Point-Of-Sale, Digital Signage, CCTV, local ISP support, and retail server rack/stack upgrades. Managed full life cycle of projects including site-surveys, negotiating price/SOW, contractor management, and generating as-built documents.

### Software Developer - Tech Friends Inc., 08/2015 - 08/2016
Remediated customer reported UI issues in corrections-facility inmate-accounting software. Implemented grid-view with search/filtering functionality for commissary inventory management.  
(**Visual Basic, WinForms**)

Wrote general purpose HTML-aware text parsing function for company’s internal library. Used in web-app to censor inmate/family messaging web-app without altering the underlying markup.  
(**C#, JavaScript, jQuery, ASP.NET**)

Implemented face tracking/censoring function for inmate video-visitation web-app.  
(**C#, JavasScript, ASP.NET, EmguCV, OpenCV**)
