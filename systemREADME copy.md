# Asphalt Gold-E
 ## SEN 201 PROJECT
 ## Team members
   |Team Member| Matric no.| What they did|
   |:-----------|:------------:|------------:|
   |SAM-OKORO CHISOM RUBY|23/0217|GANTT CHART|
   |SAMUEL OLUKOREMIWA SIMON|23/0040|SOFTWARE PROPOSAL, IMPLEMENTAION OF THE LANDING PAGE|
   |SAMUEL PHILIP ANUOLUWAPO|23/0148|PAPER PROTOTYPE|
   |SHOLAJA EMIILLIA OLUFUMNILAYO|23/0162|FUNCTIONAL AND NON-FUNCTIONAL REQUIREMENTS, PROCESS MODEL, USE CASE DIAGRAM AND SCENARIO ANALYSIS|
   |SIMEON-AKWUOBU DUKE CHUKWUKA|23/0260|RISK ANALYSIS|



 # Requirement Document 

  ## Introduction 

### Project purpose  

This document outlines the functional and non-functional requirements for a mobile app that provides the students with emergency contacts, campus security updates, and a real-time safety map. 

 

### Project scope 

This app aims to enhance campus safety by providing quick access to security services and emergency response. 

 

### Glossary and reference 

#### Glossary 
1. API: Application Programming Interface, a set of defined rules that enable different applications to communicate with each other. 

2. Campus Security System: The university's security system, which includes emergency response protocols, surveillance cameras, and alarm systems. 

3. Emergency Services: Local authorities, such as the police or the ambulance, that respond to emergency situations. 

4. Geolocation: The process of determining the physical location of a device or user. 

5. GPS: Global Positioning System, a network of satellites that provide location information to devices. 

6. HTTPS: Hypertext Transfer Protocol Secure, a secure communication protocol used for transmitting data over the internet. 

7. JWT: JSON Web Token, a secure token used for authentication and authorization. 

8. OAuth: An open standard for authorization, used to authenticate users and external systems. 

9. Panic Button: A feature that allows users to quickly alert campus security or emergency services in case of an emergency. 

10. Push Notification: A message sent to a user's device, typically used to alert them of important information or updates. 

11. RESTful API: A type of API that uses HTTP requests to interact with resources. 

12. SFTP: Secure File Transfer Protocol, a secure protocol used for transferring files over the internet. 

13. University Database: The university's central database, which stores information about students, faculty, and staff. 

#### References 
1. University Policies and Procedures: The university's official policies and procedures for campus safety and emergency response. 

2. National Institute of Justice (NIJ) Guidelines: Guidelines for campus safety and security, published by the NIJ. 

3. Clery Act: A federal law that requires universities to disclose crime statistics and security policies. 

4. Federal Communications Commission (FCC) Regulations: Regulations governing emergency communications and response. 

5. International Organization for Standardization (ISO) 27001: A standard for information security management. 

6. National Institute of Standards and Technology (NIST) Special Publication 800-53: A publication outlining security and privacy controls for federal information systems. 

7. OWASP Mobile Security Project: A project providing guidelines and resources for mobile app security. 

8. PCI-DSS: Payment Card Industry Data Security Standard, a standard for secure payment processing. 

9. University Campus Safety and Security Handbook: A handbook providing guidance on campus safety and security best practices. 

10. Local and State Laws: Relevant laws and regulations governing campus safety and security in the university's jurisdiction. 

  

By including these references, the mobile campus safety app can ensure compliance with relevant laws, regulations, and industry standards, and provide a secure and effective safety solution for the university community. 

 
  ## Overall description 

### User needs 

The end users of the mobile campus safety app are:	 

**Students:** Students are the primary end users of the app. They will use the app to access emergency contacts, report safety incidents, view real-time safety updates and maps, trigger the panic button, share their location, and receive push notifications. 

 

**Campus Security Personnel:** Campus security personnel will use the app to receive and respond to emergency reports and panic button triggers, send real-time safety updates and notifications to students, view student locations, and communicate with students through live chat. 

 

**University Administrators:** University administrators will use the app to monitor safety incidents and updates, view app usage and analytics, manage user accounts and access, and receive notifications about system issues or outages. 

 

### Assumptions and Dependencies 

1. The university will provide access to their database for user verification. 

2. Campus security will provide real-time updates and support for the app. 

3. The app will integrate with existing university systems, such as student information systems. 

4. The app will require internet connectivity to function. 

5. The app will require location services to be enabled on the user's device. 

 
  ## Features & Requirements 

   ### Functional & Non-functional Requirements 

|Functional Requirements|Non-functional Requirements|
|:---------------------------|--------------------------------:|
|   **User  login**||
|The app shall allow students to login using their university credentials. |*Performance:* The registration process shall take no more than 30 seconds to complete.|
|The app shall verify user credentials with the university database.|*Security:* The app shall use secure protocols to transmit and store user credentials.|
||*Usability:* The registration process shall be intuitive and easy to follow. |
||*Availability:* The registration feature shall be available 24/7.|
|||
| **Emergency Contacts**||
|The app shall provide a list of emergency contacts, including campus security and local authorities.|*Response Time:* The app shall display emergency contact information within 2 seconds of the user accessing the feature.|
|The app shall allow users to quickly call or message these contacts in case of an emergency.|*Accuracy:* The app shall display accurate and up-to-date emergency contact information.|
||*Security:* The app shall use secure protocols to transmit and store emergency contact information. |
||*Usability:* The emergency contact feature shall be easily accessible and usable.|
|||
|**Campus Security Updates**||
|The app shall receive real-time updates from campus security about safety incidents or concerns.|*Timeliness:* The app shall receive and display real-time updates from campus security.|
|The app shall display these updates on a dashboard and send push notifications to users.|*Accuracy:* The app shall display accurate and up-to-date information about safety incidents and concerns.|
||*Security:* The app shall use secure protocols to transmit and store campus security updates.|
||*Usability:* The updates shall be displayed in a clear and concise manner.|
|||
|**Real-time Safety Map**||
|The app shall display a map of the campus with safety information, such as crime hotspots or areas with high foot traffic.|*Map Load Time:* The safety map shall load within 3 seconds of the user accessing the feature.|
|The app shall allow users to view their current location on the map and navigate to safe areas.|*Map Accuracy:* The safety map shall display accurate and up-to-date information about safety incidents and crime hotspots.|
||*Geolocation Accuracy:* The app shall provide accurate geolocation information, with a margin of error of no more than 10 meters.|
||*Usability:* The map shall be interactive and allow users to zoom in and out.|
|||
|**Panic Button** ||
|The app shall have a panic button feature that can be triggered by a discreet gesture, such as triple tapping the phone's screen.|*Response Time:* The panic button feature shall respond to the user's gesture within 1 second.|
|When the panic button is triggered, the app shall send the user's location to campus security or local authorities and trigger a call to campus security or local authorities.|*Accuracy:* The panic button feature shall accurately detect the user's gesture 99.9% of the time.|
||*Security:* The panic button feature shall use end-to-end encryption to protect the user's location and identity.|
||*Reliability:* The panic button feature shall be available 24/7, with a minimum uptime of 99.9%.|
|||
|**Live Chat with Campus Security**||
|The app shall provide a live chat feature for users to initiate conversations with campus security personnel. |*Response Time:* Campus security personnel shall respond to live chat messages within 2 minutes.|
|The chat shall be encrypted and secure.|*Chat Availability:* The live chat feature shall be available 24/7, with a minimum uptime of 99.9%.| 
||*Encryption:* The live chat feature shall use end-to-end encryption to protect user conversations.|
||*Usability:* The live chat feature shall be easily accessible and usable.|
|**Geolocation Sharing**||
|The app shall allow users to share their location with campus security or friends/family in case of an emergency.|*Location Accuracy:* The app shall provide accurate geolocation information, with a margin of error of no more than 10 meters.|
|The app shall provide an estimated time of arrival for help to reach the user's location.|*Security:* The app shall use secure protocols to transmit and store geolocation information.|
||*Usability:* The geolocation sharing feature shall be easily accessible and usable. |
||*Availability:* The geolocation sharing feature shall be available 24/7.|
|||
|**Push Notifications**||
|The app shall send push notifications to users about safety incidents, updates, or emergencies.|*Timeliness:* The app shall send push notifications in real-time.|
|The app should allow users to customize notification preferences.|*Accuracy:* The app shall send accurate and up-to-date information about safety incidents and updates.|
||*Security:* The app shall use secure protocols to transmit and store push notification information.|
||*Usability:* The push notifications shall be clear and concise.|
|||


   ### External Interface Requirements 

**University Database Interface:** 
* The app shall integrate with the university's database to verify user credentials. 

* The app shall receive real-time updates from the university's database about safety incidents and concerns. 

* The interface shall use secure protocols to transmit and store data. 

**Campus Security System Interface:**
* The app shall integrate with the campus security system to receive real-time updates about safety incidents and concerns. 

* The app shall send panic button triggers and emergency reports to the campus security system. 

* The interface shall use secure protocols to transmit and store data. 

**GPS and Mapping Interface:**
* The app shall integrate with GPS and mapping services to provide accurate geolocation information. 

* The app shall display safety information and crime hotspots on the map. 

* The interface shall use secure protocols to transmit and store data. 

**Push Notification Service Interface:**

* The app shall integrate with a push notification service to send real-time notifications to users. 

* The interface shall use secure protocols to transmit and store data. 

**Emergency Services Interface:**

* The app shall integrate with emergency services, such as 911 or local authorities. 

* The app shall send emergency reports and panic button triggers to emergency services. 

* The interface shall use secure protocols to transmit and store data. 

**Social Media Interface (optional):**

* The app shall integrate with social media platforms to allow users to share safety information and concerns. 

* The interface shall use secure protocols to transmit and store data. 

**University Website Interface (optional):** 

* The app shall integrate with the university's website to provide safety information and resources. 

* The interface shall use secure protocols to transmit and store data. 

  

#### Interface Protocols and Standards 

* APIs: The app shall use RESTful APIs to integrate with external systems. 

* Data Formats: The app shall use JSON or XML data formats to transmit and store data. 

* Security Protocols: The app shall use HTTPS or SFTP to transmit and store data securely. 

* Authentication: The app shall use OAuth or JWT to authenticate users and external systems. 

  

   ### Interface Requirements for Specific Functionalities 

**Panic Button:**

* The app shall send panic button triggers to the campus security system and emergency services. 

* The interface shall use secure protocols to transmit and store data. 

**Live Chat:** 

* The app shall integrate with a live chat service to provide real-time communication with campus security personnel. 

* The interface shall use secure protocols to transmit and store data. 

**Geolocation Sharing:**

* The app shall integrate with GPS and mapping services to provide accurate geolocation information. 

* The interface shall use secure protocols to transmit and store data. 

  

By defining these external interface requirements, the app can ensure seamless integration with external systems and provide a comprehensive safety solution for the university community. 



  ## Approval

The following stakeholders have reviewed and approved the Requirement Document:

- University Administration: Dr. Maria Rodriguez, Vice President of Student Affairs
- Campus Security Personnel: Chief James Johnson, Director of Campus Security
- IT Department: Raj Patel, Chief Information Officer
- Student Representative: Emily Chen, Student Body President
- Faculty Representative: Dr. David Lee, Professor of Computer Science
- Local Authorities Representative: Sheriff John Smith, County Sheriff's Department
- Software Project

Approval Date: November 17, 2024

 # Process Model Document
## Development Process Model: Spiral Model 

 

Based on the requirements of the mobile campus safety app, We recommend the Spiral Development Process Model. Here's why: 

### Why Spiral Model? 

1. **Risk Management:** The Spiral Model is ideal for projects with high-risk requirements, such as the panic button feature, which requires precise and reliable functionality. The model's iterative approach allows for continuous risk assessment and mitigation. 

2. **Complexity:** The app's integration with multiple external systems (e.g., university database, campus security system, GPS, and emergency services) and its requirement for high security and reliability make it a complex project. The Spiral Model's iterative and incremental approach helps manage complexity. 

3. **Changing Requirements:** The university's policies, procedures, and security protocols may change during the development process. The Spiral Model accommodates changing requirements through its iterative approach, ensuring the app remains aligned with the university's needs. 

4. **High Priority on Security:** The Spiral Model's emphasis on risk management and continuous testing ensures that security concerns are addressed throughout the development process, which is critical for an app that handles sensitive information and emergency situations. 

5. **User Involvement:** The Spiral Model involves users throughout the development process, which is essential for an app that requires user feedback and testing to ensure its effectiveness in emergency situations. 

  

### How the Spiral Model will be applied 

1. **Initialization:** Define project goals, objectives, and scope. 

2. **Risk Analysis:** Identify and assess risks associated with the panic button feature, integration with external systems, and security requirements. 

3. **Requirements Gathering:** Gather and document functional and non-functional requirements. 

4. **Design:** Create a detailed design for the app, including architecture, user interface, and system integration. 

5. **Implementation:** Develop the app in iterations, with each iteration focusing on a specific feature or set of features. 

6. **Testing:** Conduct unit testing, integration testing, and user acceptance testing (UAT) for each iteration. 

7. **Evaluation:** Evaluate the app's performance, security, and usability after each iteration, and gather feedback from users. 

8. **Next Iteration:** Refine the app based on feedback and lessons learned and plan the next iteration. 

  

### Justification for using Spiral Process Model

The Spiral Model is well-suited for the mobile campus safety app because it: 

1. **Manages risk:** The model's iterative approach and continuous risk assessment ensure that potential risks are identified and mitigated. 

2. **Accommodates complexity:** The Spiral Model's incremental approach helps manage the app's complexity and multiple integrations. 

3. **Ensures security:** The model's emphasis on security and continuous testing ensures the app meets high security standards. 

4. **Involves users:** The Spiral Model's iterative approach ensures users are involved throughout the development process, providing valuable feedback and input. 

5. **Allows for flexibility:** The model accommodates changing requirements and ensures the app remains aligned with the university's evolving needs. 

6. **Facilitates iterative development:** The Spiral Model allows for iterative development, which is essential for an app that requires continuous testing and refinement. 

7. **Encourages continuous improvement:** The model's emphasis on evaluation and feedback ensures that the app is continuously improved and refined throughout the development process. 



 

  

  



### Spiral Model Advantages 

The Spiral Model offers several advantages: 

1. **Risk management:** The model's iterative approach and continuous risk assessment ensure that potential risks are identified and mitigated. 

2. **Flexibility:** The Spiral Model accommodates changing requirements and ensures the app remains aligned with the university's evolving needs. 

3. **User involvement:** The model's iterative approach ensures users are involved throughout the development process, providing valuable feedback and input. 

4. **Continuous improvement:** The model's emphasis on evaluation and feedback ensures that the app is continuously improved and refined throughout the development process. 

  

### Spiral Model Disadvantages 

The Spiral Model also has some disadvantages: 

1. **Complexity:** The model's iterative approach can lead to complexity and increased project duration. 

2. **Resource-intensive:** The model requires significant resources, including personnel and equipment. 

3. **Difficulty in estimation:** Estimating project duration and costs can be challenging due to the iterative nature of the model. 

  

### Conclusion 

The Spiral Development Process Model is well-suited for the mobile campus safety app due to its emphasis on risk management, flexibility, user involvement, and continuous improvement. While the model has some disadvantages, its advantages make it an ideal choice for this project. By using the Spiral Model, the development team can ensure the app is developed with a focus on security, reliability, and user needs, resulting in a effective safety solution for the university community. 

 # Use Case Diagram And Scenario Analysis
 ## Use Case Diagram
 ![Use Case Diagram](</Asphalt Gold-E useCase.drawio.png> "Use Case Diagram")
 

 ## Scenario Analysis 
 Here's the scenario analysis for the campus safety app:

### Scenario 1: Emergency Situation - Panic Button Triggered

Primary Actor: Student
Goal: To quickly alert campus security and emergency contacts in an emergency situation
Trigger: Student triggers the panic button on the app
Description: The student triggers the panic button, and the app automatically shares their location with campus security and sends a call or message to emergency contacts.
Assumptions:
+ The student has already logged in to the app.
+ The student's location services are enabled.
+ Campus security and emergency contacts are available and responsive.
Exceptions:
+ The student's phone is out of battery or has no signal.
+ Campus security or emergency contacts are unavailable or unresponsive.

### Scenario 2: Non-Emergency Situation - Reporting an Incident

Primary Actor: Student
Goal: To report a non-emergency incident to campus security
Trigger: Student reports an incident using the app
Description: The student reports an incident using the app, providing details and any relevant photos or videos. Campus security receives the report and responds accordingly.
Assumptions:
+ The student has already logged in to the app.
+ The student provides accurate and complete information about the incident.
+ Campus security is available and responsive.
Exceptions:
+ The student provides incomplete or inaccurate information.
+ Campus security is unavailable or unresponsive.

### Scenario 3: Customizing Notification Preferences

Primary Actor: Student
Goal: To customize notification preferences for the app
Trigger: Student accesses the app's settings to customize notification preferences
Description: The student accesses the app's settings and customizes their notification preferences, choosing which types of notifications they want to receive and how they want to receive them.
Assumptions:
+ The student has already logged in to the app.
+ The student understands the different notification options and their implications.
Exceptions:
+ The student is unsure about which notification options to choose.
+ The app's notification settings are unclear or difficult to understand.

### Scenario 4: Viewing Safety Information

Primary Actor: Student
Goal: To view safety information and resources using the app
Trigger: Student accesses the app's safety information section
Description: The student accesses the app's safety information section and views available resources, such as safety tips, emergency contact information, and campus maps.
Assumptions:
+ The student has already logged in to the app.
+ The app's safety information section is up-to-date and accurate.
Exceptions:
+ The app's safety information section is outdated or inaccurate.
+ The student is unable to find the information they need.

### Scenario 5: Receiving Campus Security Updates

Primary Actor: Student
Goal: To receive updates from campus security using the app
Trigger: Campus security sends an update using the app
Description: Campus security sends an update using the app, and the student receives the update in real-time.
Assumptions:
+ The student has already logged in to the app.
+ Campus security has the necessary information and resources to send updates.
Exceptions:
+ Campus security is unable to send updates due to technical issues.
+ The student is unable to receive updates due to technical issues.

 # Risk Analysis

## Risk Table
|Risk ID |Risk Identification |Risk Category |Risk Component |Risk Probability |Risk Impact |Action Plan|Risk Monitoring Strategy|
|:-------|:------------:|:------------:|:----------:|:------------:|:------------:|:----------:|------------------------:|
| 1 |Weak security protocols| Technical| Performance| Medium (40%)| High (8)|- Strengthen encryption. - Implement access controls- Schedule security audits.| - Perform quarterly penetration tests. - Regularly update security frameworks|
| 2 | System downtime or errors| Technical |Performance| High(60%)| Medium (6)| - Conduct proactive testing. - Schedule regular maintenance|- Use real-time monitoring. - Maintain backup and recovery systems|
| 3 | Development delays| Project (Development)| Schedule|Medium(%0%)| High (7)| - Create detailed timelines. - Set achievable milestones|- Review project progress bi-weekly. - Monitor timelines closely|
| 4 | Budget overruns| Business| Cost| Medium (30%)| Medium (6)| - Allocate contingency funds. - Perform budget reviews|- Track expenses monthly. - Adjust budgets based on trends|
| 5 | Insufficient user support| Business| Support|Low (20%)|Medium (4)| - Develop user training materials. - Create a robust support system|- Analyze user feedback. - Conduct bi-annual satisfaction surveys|
| 6 | Cyber-attacks targeting data| Technical| Performance| High (70%)| High (9)|- Implement real-time monitoring. - Regularly update firewalls|- Conduct semi-annual threat assessments. - Monitor system for unusual activities|
| 7 | Market requirement shifts| Business| Performance| Medium(40%)| High (7)| - Engage stakeholders. - Conduct market trend analysis| - Hold quarterly strategy reviews. - Adjust based on user and market feedback|
| 8 | Integration challenges| Technical| Performance| Medium (50%)| Medium (6)|- Develop an integration blueprint. - Collaborate with vendors|- Monitor integration status monthly. - Resolve issues promptly|
| 9 | Testing and QA delays| Project (Development)| Schedule| Medium (40%)| Medium (6)| - Define detailed testing protocols. - Create checkpoints for testing milestones| - Track QA progress bi-weekly. - Address bottlenecks proactively|
| 10 | Limited resources for maintenance| Business| Support| Medium (30%)| Medium (5)|- Prepare a maintenance roadmap. - Build partnerships with reliable vendors|- Track resource usage quarterly. - Reassess budgets regularly|


### Risk Category: 
* Project (Development): risks related to the development process 
* Technical: risks related to the technical aspects of the project 
* Business: risks related to the business aspects of the project 

  

### Risk Component: 

* Performance: risks related to the system's performance 
* Cost: risks related to the project's budget 
* Schedule: risks related to the project's timeline 
* Support: risks related to the support and maintenance of the system 

  

### Risk Probability: 
* 0%-20%: Low 
* 30%-50%: Medium 
* 60%-80%: High 
* 90%-100%: Very High 

  

### Risk Impact: 
*  1-3: Low 
* 4-6: Medium 
* 7-9: High 
  
 # Gantt Chart
  [Gantt Chart](https://1drv.ms/x/c/60312dfd7f3fdfa0/EV1F4z0Wu_NFsgxRvyLSvYQB4Naomh2Tv4jpEBuiLg3feQ "Gantt Chart")


 # Software Proposal
  **Software Proposal for Asphalt Gold –E: A Campus Safety App**
  **Prepared for:**
   Babcock University

  **Prepared by:**
   Asphalt-Gold-E

  **Date:**
   September 17, 2024

  **Title of Project:**
   Campus Safety App



  ## Executive Summary

  This proposal outlines the development and implementation of a Campus Safety App to enhance the safety and security of Babcock University. The app will address critical gaps in current safety measures by providing streamlined incident reporting, real-time emergency notifications, and accessible safety resources. It aims to reduce response times, improve user engagement, and integrate seamlessly with the university’s existing systems.
  Key objectives include the delivery of a fully operational app by April 30, 2025, following a phased timeline that ensures comprehensive development, testing, and deployment. The app’s user-friendly design, coupled with robust technical infrastructure, will deliver measurable benefits to the university community.




   ### Introduction

   Babcock University has demonstrated a commitment to ensuring the safety and well-being of its students, faculty, and staff. However, recent incidents have revealed inefficiencies in the current manual safety systems, which can result in delays and inadequate responses during emergencies.
   The Campus Safety App presents an opportunity to address these challenges by leveraging modern technology to provide an efficient, reliable, and user-friendly solution. This project aims to enhance campus security measures, empower users with real-time information, and streamline communication between the university’s community and its security personnel.


   ### Project Overview

   The Campus Safety App is a transformative tool designed to strengthen the safety infrastructure of Babcock University. By offering features like real-time emergency notifications, incident reporting, and access to safety resources, the app will become an indispensable tool for students, faculty, and staff. Integration with existing campus security systems ensures streamlined operations and quick response capabilities. The app’s design emphasizes accessibility, ensuring users of all backgrounds can engage with its features effectively.



  ## Scope of Work

   ### Detailed Breakdown of Work to Be Performed

   #### Requirements Gathering and Analysis:
   - Conduct interviews and workshops with key stakeholders.
   - Document functional and non-functional requirements.

   #### Design and Development:
   - Create prototypes and wireframes for stakeholder review.
   - Develop the app’s frontend and backend systems.
   - Ensure integration with the university’s existing security systems.

  #### Testing and Quality Assurance:
 - Conduct unit, integration, and system testing.
 - Implement user acceptance testing with stakeholders.

  #### Deployment and Implementation:
- Deploy the app to university servers and app stores.
- Conduct training sessions for users and administrators.


  #### Maintenance and Support:
 - Provide one year of post-launch technical support.
 - Address bug fixes and system updates as needed.



  ### Inclusions
 - Development and deployment of the Campus Safety App, including mobile and web interfaces.
 - Integration with the university’s existing security systems and infrastructure.
 - Development of training materials and hosting user training sessions.
 - One year of post-launch maintenance and support.

 ### Exclusions
 - Hardware procurement and maintenance (e.g., servers, networking equipment).
 - Upgrades and updates beyond the first year of maintenance.



 ## Technical Approach

 ### Frontend Development
 - A responsive and intuitive user interface ensuring seamless navigation across mobile and desktop platforms.
 - Accessibility compliance to meet the needs of users with disabilities.

 ### Backend Development
 - A scalable architecture using cloud-based services to manage high volumes of data securely and efficiently.
 - Implementation of robust authentication and data encryption protocols.

 ### Integration
 - APIs to connect with existing security systems, ensuring real-time data sharing and operational synchronization.
 - GPS-enabled functionality to support location-based services for rapid emergency responses.

 ### Testing and Quality Assurance
 - Conducting unit, integration, and system testing at each development phase.
 - User acceptance testing involving diverse stakeholder groups to gather actionable feedback.



 ## Project Timeline 

  #### Planning Phase (Sep 3 – Sep 17, 2024)

  - Kick-off meeting and stakeholder alignment.
  - Comprehensive requirements gathering and analysis.

 #### Design Phase (Sep 18 – Oct 1, 2024)

   - Development of UI/UX designs and prototypes.
   - Stakeholder reviews and finalization of design specifications.

 #### Development Phase (Oct 2, 2024 – Jan 28, 2025)

  - Backend development with integration-ready modules.
  - Frontend interface implementation and optimization.
  - Mobile app development with cross-platform compatibility.



#### Testing and QA Phase (Jan 29 – Feb 28, 2025)

   - Comprehensive testing cycles to ensure app reliability and performance.
   - Addressing feedback from stakeholders during acceptance testing.

#### Deployment and Post-Launch Phase (Mar 1 – Apr 30, 2025)

   - Deployment to university systems and app stores.
   - Post-launch performance review and user training sessions.



 ## Pricing and Cost Structure

 ### Overall Project Cost

 Total: ₦136,600,000



 ### Developmental Costs

 #### Personnel Costs
- Project Manager: ₦38,000,000
 - Backend Developer: ₦28,000,000
 - Frontend Developer: ₦20,000,000
 - Mobile App Developer: ₦20,000,000
 - UI/UX Designer: ₦16,000,000
 - QA Tester: ₦4,000,000
 Total Personnel Costs: ₦126,000,000

 #### Software and Licensing Costs
 - PostgreSQL: ₦1,500,000/year
 - AWS Lambda: ₦600,000/year
 - Development Tools: ₦500,000 (one-time)
 Total Software Costs: ₦4,500,000

 #### Testing and Quality Assurance Costs

 -  QA team salaries included in personnel costs
 -  Testing tools and infrastructure: Included in development costs

 #### Deployment and Implementation Costs

 * Deployment to app stores and university servers: Included in development costs.
 * Training and onboarding materials: ₦500,000

 #### Maintenance and Support Costs
 - One year of post-launch support: ₦3,000,000.



 The project will follow a fixed-price model, ensuring clarity and predictability for the university. Optional subscription-based models for extended support beyond the first year can be discussed.




  ## Assumptions and Dependencies

 - The university will provide required infrastructure such as servers and network connectivity.
 - Stakeholder participation will be consistent and timely during review cycles.
 - Security policies of the university will support the app’s integration requirements.
 - Adequate resources for user training sessions will be allocated.




 ## Risks and Mitigation Strategies

 Since the Spiral Process Model will be used for this project, risk management will be iterative and incorporated at the end of each development cycle. Each cycle will conclude with a risk assessment to identify potential issues early. This ensures that:

 - Technical risks such as system integration challenges are identified and resolved before progressing to the next phase.
 - Operational risks such as user adoption challenges are mitigated through continuous feedback and stakeholder engagement.
 - Financial risks are managed by adhering to a phased budget allocation.

 Key mitigation strategies include:
 - Continuous stakeholder involvement to ensure alignment with university requirements.
 - Iterative testing and prototyping to identify and resolve issues at each phase.
 - Flexible resource allocation to address unexpected challenges.



 ## Team and Resources
 * Project Manager: Oversees project execution, resource allocation, and stakeholder communication.
 * Backend Developer: Implements server-side functionality, ensuring robust data processing.
 * Frontend Developer: Designs and develops user interfaces for web and mobile platforms.
 * Mobile App Developer: Builds optimized mobile applications for Android and iOS.
 * UI/UX Designer: Crafts engaging and user-friendly designs, focusing on accessibility.
 * QA Tester: Executes rigorous testing to identify and resolve application bugs.




 ## Conclusion

 The proposed Campus Safety App represents a significant step forward in ensuring the security and well-being of Babcock University’s community. This proposal highlights the key features and benefits of the app, including improved emergency response times, streamlined incident reporting, and enhanced user engagement. By adopting modern technologies and a structured implementation strategy, the university will establish a safer and more secure campus environment.
 To proceed, we recommend approval of the detailed development plan to allow immediate commencement of the next phase. For further details or to discuss the next steps, please contact:
 Samuel Olukoremiwa Simon
 Project Manager
 olukoremiwasamuel@gmail.com
 We look forward to collaborating with Babcock University to achieve its safety objectives.



 ## Appendices

 1. Detailed Budget Breakdown
 2. Project Plan and Gantt Chart
 3. Technical Specifications
 4. Stakeholder Engagement Plan
 5. Training and Onboarding Materials


# Live link to website
[Website](https://campus-safety-app-asphalt-gold-e.onrender.com "Website")
