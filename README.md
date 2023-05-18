# Career Check - App
## Problem Statement: 
As Bangladesh is a populous country. It is plagued with many 
problems. A large portion of its population is unemployed or not even self employed. Also, many young graduates have no job. They are unable to turn
themselves into self-employed to support their families. Adding about one million 
new graduates every year to our existing unemployed population is further 
complicating the situation. The Bangladesh Institute of development studies made 
the observations over a survey and has revealed alarming information. As of 2017, 
about 66 percent of graduates remain unemployed, including those who have 
completed honors courses and postgraduates from 2154 public and private colleges 
affiliated with the national university (NU). [1] There are some factors of not getting 
job in job market. Recruiters often fail to find proper candidate for their role. 
Students tend to lack industry level practical knowledge. Students lack a proper 
career guidance. To solve this issue, we have proposed a solution. An app where 
students can seek career guidance from founders, CEOs, entrepreneurs of related 
field. Student can attend mock interviews which will help themselves to know about 
the level of their skill are enough to get a fresher job or not.
## Effect on Society: 
In recent times, university degree holders do not meet the demand 
of the job market. The situation is such that when hiring, employees have to be 
trained from the beginning. Business entrepreneurs are not getting skilled people 
from our country for management positions. [1] The survey was conducted with a 
view to finding out how much of the graduates from the National University are 
contributing to the national workforce. However, 97% of students who graduated 
from the National University complained that they did not receive any assistance 
from teachers or educational institutions when looking for a job after graduation. [2]
As a result, huge numbers of private sector manpower are being recruited from India, 
Sri Lanka, and other countries for management positions. A large part of our foreign 
exchange is being spent behind them. Statistics show that each 3 to 5 billion dollars 
is spent on foreign manpower. It would have been better if these students had been 
given the opportunity to pursue vocational and technical education, equivalent to 
building a suitable career in various industries and services. [1]

## Our Proposed Solution:

Career Check is an app where students can seek career guidance from founders, 
CEOs, entrepreneurs of related field. Student can attend mock interviews which will 
help themselves to know about the level of their skill are enough to get a fresher job 
or not. Here is our proposed solution:

![Untitled Diagram (1)](https://user-images.githubusercontent.com/97898902/183295800-8b10bb95-c9ed-4495-8f55-edf499184131.jpg)

### Fig: 1.0. Our Proposed Solution Diagram

There are two panels student and Tech leader. Student will sign up and login from 
app. Students can add personal information’s like name, date of birth, NID 
verification, phone, email and address. Students can add their educational 
background information, projects, skills and previous work experience information.
Tech Leaders will also follow the same procedure of registration and after admin 
approval they will be able to login and use the service.

### Use Case Diagram of Career Check Application
![Picture8](https://github.com/codewithkhurshed/CareerCheck/assets/97898902/58f9d719-7a1e-4f21-8352-ce59cd71e3b5)

### Functional Requirement of Career Check Application

•	User Registration: The application should allow applicants to register by providing their personal details, such as name, email, and password.
•	User Login: The application should allow registered users to log in by entering their email and password.
•	Mock Interview Selection: The application should provide a list of available mock interviews for applicants to choose from.
•	Career Mentorship Selection: The application should provide a list of available career mentorship options for applicants to choose from.
•	Online Payment: The application should allow applicants to make online payments using Bkash, Nagad, Upay, or card.
•	Appointment Scheduling: The application should allow applicants to schedule appointments with career mentors after making payments.
•	Appointment Rescheduling: The application should allow career mentors to reschedule appointments if necessary.
•	Online Meeting: The application should provide an online meeting platform for career mentors to host meetings with applicants.
•	Course Recommendation: The application should allow career mentors to recommend courses to applicants.
•	Course Content Upload: The application should allow educators to upload course contents.
•	User Management: The application should allow the admin to add, remove, or edit career mentors and educators.

### Non-Functional Requirement of Career Check Application

Security: The application should be secure and protect the privacy of the users' personal and payment information.
Usability: The application should be user-friendly and easy to navigate.
Availability: The application should be available 24/7 without any downtime.
Scalability: The application should be able to handle many users and appointments simultaneously.
Performance: The application should have a fast response time and low latency.
Compatibility: The application should be responsive and work on different devices and platforms.
Reliability: The application should be reliable and have a backup and recovery mechanism in case of any failures.
Compliance: The application should comply with local laws and regulations regarding online payments and data privacy.

### Server Architecture of Career Check Application
For this project, I am choosing Client-Server Architecture type. Here is the implementation of Client-Server Architecture for Career Check Application:
Client Side:
The Client Side of this project is the Android application installed on the user's device (smartphone, tablet, etc.). It is responsible for providing a user-friendly interface for the applicant to access the features of the application. The client-side will communicate with the Web Server through APIs to access data, information, and perform various functions.
Web Server:
The Web Server is the first point of contact between the Client and the Application Server. It hosts the application and acts as a mediator between the client-side application and the backend servers. It will receive the request from the client-side, perform initial authentication, and forward the request to the Application Server.
Application Server:
The Application Server is responsible for managing the business logic and core functionalities of the Career Check application. It will receive the request from the Web Server, process the request, communicate with the Database Server to retrieve the necessary data, and provide a response back to the Web Server.
Database Server:
The Database Server stores all the data and information required by the Career Check application, including user information, appointments, course details, etc. The Application Server communicates with the Database Server to retrieve and update the data as required.
Payment Gateway:
The Payment Gateway is responsible for processing online payments made by the Applicants using Bkash, Nagad, Upay, or Card. The Payment Gateway will receive the payment request from the Application Server and communicate with the relevant payment processors to process the payment transaction securely. The Payment Gateway will then provide the status of the transaction back to the Application Server, which will update the user's account accordingly.

### Quality Management System (QMS) for Career Check App

Career Check is committed to providing a high-quality application that delivers exceptional career mentorship, mock interviews, and course recommendations to its applicants. The purpose of this Quality Management System (QMS) is to outline the policies, procedures, and controls that Career Check will implement to achieve its quality objectives.
**•	Quality Policy**
Career Check's quality policy is to provide a user-friendly and reliable application that delivers high-quality career mentorship, mock interviews, and course recommendations to the applicants. Career Check will achieve this by:
1.	Hiring qualified and experienced career mentors and educators who have a proven track record of delivering high-quality mentorship and course content.
2.	Developing a user-friendly and reliable application that meets the needs and expectations of our users.
3.	Conducting regular reviews of the course content to ensure that it is up-to-date, accurate, and relevant.
4.	Regularly monitoring and measuring the performance of our application, mentorship, and course content to identify areas for improvement.
**•	Quality Objectives**
Career Check's quality objectives are to:
1.	Achieve a customer satisfaction rating of at least 90%.
2.	Ensure that 100% of the appointments are managed and rescheduled promptly.
3.	Ensure that 100% of the online meetings are hosted successfully.
4.	Ensure that 100% of the course content is up-to-date, accurate, and relevant.
5.	Ensure that 100% of the payments are processed correctly.
**•	Quality Procedures**
Career Check will implement the following quality procedures to achieve its quality objectives:
1.	Hiring Process: Career Check will follow a rigorous hiring process to ensure that all career mentors and educators are qualified and experienced.
2.	Application Development Process: Career Check will follow a structured development process that includes regular testing and reviews to ensure that the application meets the needs and expectations of our users.
3.	Course Content Review Process: Career Check will conduct regular reviews of the course content to ensure that it is up-to-date, accurate, and relevant.
4.	Appointment Management Process: Career Check will ensure that all appointments are managed and rescheduled promptly.
5.	Online Meeting Hosting Process: Career Check will ensure that all online meetings are hosted successfully.
6.	Payment Processing Process: Career Check will ensure that all payments are processed correctly.
**•	Quality Controls**
Career Check will implement the following quality controls to ensure that its quality procedures are being followed:
1.	Process Audits: Career Check will conduct regular process audits to ensure that its quality procedures are being followed.
2.	Inspections and Testing: Career Check will conduct regular inspections and testing of the application, mentorship, and course content to ensure that they meet our quality objectives and policies.
•	Performance Monitoring and Measurement
Career Check will monitor and measure the performance of its QMS using the following quality metrics:
1.	Customer Satisfaction: Career Check will regularly collect feedback from its applicants to ensure that they are satisfied with the mentorship and course content they receive.
2.	Application Performance: Career Check will regularly monitor and measure the performance of its application to identify areas for improvement.
3.	Mentorship Performance: Career Check will regularly monitor and measure the performance of its mentors to ensure that they are delivering high-quality mentorship.
4.	Course Content Performance: Career Check will regularly review the course content to ensure that it is up-to-date, accurate, and relevant.
**•	Continuous Improvement**
Career Check will continuously improve its QMS by using the data collected during performance monitoring to identify areas for improvement and make changes to its quality procedures and controls accordingly. Career Check will also regularly review its quality policies and objectives to ensure that they remain relevant and aligned with the needs of its applicants.

### User Interface

![Splash Screen (1)](https://github.com/codewithkhurshed/CareerCheck/assets/97898902/31c24194-4fd8-477a-b7fa-d9c8679fa01b)
![Login Activity (2)](https://github.com/codewithkhurshed/CareerCheck/assets/97898902/0a10a703-823d-4a31-97e7-6a70f45cfad5)
![User Profile](https://github.com/codewithkhurshed/CareerCheck/assets/97898902/0f2f406a-385b-4a02-860c-ac8d6944abc9)
![Search For Career Advice or Mock Interview](https://github.com/codewithkhurshed/CareerCheck/assets/97898902/c35e8fe1-e983-4256-8817-8917efdad42a)
![Company Overview](https://github.com/codewithkhurshed/CareerCheck/assets/97898902/d3410523-4bed-4eea-9101-9610c94707fa)
![Tech Leader Appointment View](https://github.com/codewithkhurshed/CareerCheck/assets/97898902/8464f495-359e-40a4-a606-53ce07af3546)
![Appointment OverView](https://github.com/codewithkhurshed/CareerCheck/assets/97898902/2eeaf5cf-3b18-4a0e-b07b-5ea22ae90ac3)
![Course Recommendation](https://github.com/codewithkhurshed/CareerCheck/assets/97898902/80ef30dd-c26e-4495-85c9-51249e34f183)
![Career Check](https://github.com/codewithkhurshed/CareerCheck/assets/97898902/3981f1e3-9540-4744-9941-8fa969a2f78d)


# References
[1] B. Z. Rahman, "Graduate unemployment challenges in Bangladesh," risingbd.com, 2022.

[2] Dhaka Tribune, "66% National University graduates are unemployed," Dhaka Tribune, Dhaka, 2021.

