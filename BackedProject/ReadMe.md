# Backend Project
___
For the backend module of Multiverse, we were tasked with demonstrating the skills learned throughout the course. Typically, this would involve building projects to showcase these skills. However, since I was already doing extensive backend work at Warner Music Group (WMG), I decided to focus my project on one of the tasks I completed for WMG.

# Users
___
WMG's accountants, auditors, and business employees.

# Key Features
___
Amending the existing ingestion format to accommodate evolving business needs.
Introducing unit tests for this specific ingestion format to prevent future production issues.
# Personal Contributions
___
**S** - Warner Music Group uses an internal application to document and maintain ownership of exploited works. There are multiple file formats that income providers can use to upload files for ingestion. One particular format encountered an issue due to changing business requirements. The file ingestion system was configured to expect a specific number of rows of data from a particular income provider. However, the provider eventually included more rows than the MusixMatch format was designed to handle. I was tasked with modifying MusixMatch to support both the old and new row formats.

**T** -For file ingestion, we use an ETL data pipeline to store information in an AWS S3 bucket. Uploaded files can be in various formats, such as ASCII, CSV, or Excel, with the expected output in JSON format. I used Hadoop, Apache, and Java to implement the necessary changes in the existing system. We utilized Jira for communication and collaboration, GitHub for repository management, and Jenkins for CI/CD. I also employed the JUnit framework to develop unit tests and ensure the robustness of the bug fix using Test-Driven Development.

**A** - My contributions allowed the business to seamlessly adapt to the changing file format requirements of income providers. By resolving this issue, my mentor was able to focus on other pressing matters related to the internal application. The solution I implemented saved the business at least 30 hours per month of manual data sanitization to ensure compatibility with the existing MusixMatch format. The primary challenge was becoming familiar with Java and the frameworks used at the enterprise level. This was my first task at WMG and one of my first experiences writing Java code. Despite being initially intimidated by technologies like Hadoop and Apache, I embraced the challenge and gained valuable knowledge.

**R** - I successfully completed the task within two weeks, saving the business approximately 40 hours per month of manual data sanitization. I also gained significant experience in handling big data at an enterprise level. I continued to work on ETL-related tasks for the internal application and eventually became the primary caretaker of its ETL pipelines. The project has proven to be effective and is still used in production by WMG's business units.

# Competencies
____
### JF 1.2: Can describe the roles and responsibilities within the software development lifecycle
Joining Warner Music Group and working with the team was an amazing experience. Observing how everyone handled their respective responsibilities within the internal application—whether it was QA engineers ensuring quality, DevOps engineers maintaining environments, or developers like myself working on improvements—felt like being part of a well-oiled machine.

### JF 1.4: Can distinguish between different software development methodologies
This was a particularly interesting area. Initially, we operated with two-week sprints for releases. Eventually, we transitioned to a more agile approach, breaking releases down into their respective functionalities (ETL, royalty processing, statement generation, etc.) and addressing them as needed. It was fascinating to see the leads make significant business decisions on the fly and weigh the pros and cons.

### JF 1.5: Can work effectively and contribute appropriately on a team to produce software
This is the competency I am most proud of. Being able to join a team, quickly learn the processes, and start contributing to actual business deliverables was an incredible experience. Throughout my apprenticeship, I became the primary caretaker of the ETL section within the internal app, and I take great pride in that!

### JF 1.6: Can follow software designs and functional specifications
This task was part of an existing software system, and I had to consider integration while developing the solution. The repository was designed to directly address business needs. Although I initially had reservations about coding in Java, I understood the importance of adhering to design and functionality specifications to meet business expectations.

### JF 4.3: Is able to build, manage, and deploy code into the relevant environment
This task provided practical experience in this competency. Coding, testing, and deploying in personal projects is one thing, but doing so within the structure of a production-level project is entirely different. We had multiple environments aside from production where we would deploy and test our code. However, before reaching that stage, we had to thoroughly test our code locally using unit tests.

### JF 4.5: Can explain relevant and up-to-date software testing frameworks and methodologies
This apprenticeship highlighted the importance of Test-Driven Development (TDD). In addition, I gained experience in load testing, stress testing, and regression testing, all of which are critical for maintaining the integrity of our internal application. I also participated in bug-busting events to further enhance my testing skills.

### JF 4.6: Can test code and analyze results to correct errors using unit testing
During my apprenticeship, unit tests were mandatory for every new ingestion format I created before it could be deployed to production. Testing is crucial, especially when working on an application that a business relies on to compensate its partners. Analyzing results has become a substantial part of my development process.

### JF 5.4: Understands and can identify and create test scenarios
For my ETL tasks, I had to write unit tests and design test cases to anticipate potential edge cases. When modifying MusixMatch to accept additional rows, I considered various scenarios, such as handling rows with null data, unexpected row structures, and different file formats (e.g., ASCII vs. CSV).

### JF 6.3: Able to communicate software solutions and ideas to technical and non-technical stakeholders
Throughout my apprenticeship, I conducted presentations and demo sessions on my completed tasks. This was to communicate the work I had been doing and to help non-technical stakeholders understand the thought process behind implementing new fixes and features.

### JF 6.6: Shows initiative in solving problems within their own remit, being resourceful when faced with a problem to solve
My golden rule throughout the apprenticeship was to exhaust all avenues of debugging, troubleshooting, and research before seeking help. There have been numerous instances where I reached out to my mentor for assistance, only to find a solution on my own before he could respond. This was often achieved by thinking more deeply about the problem or consulting Apache documentation to find additional tools at my disposal.