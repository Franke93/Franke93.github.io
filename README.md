# Jordan Franke

## Computer Science ePortfolio

Welcome to my computer science ePortfolio. This portfolio highlights projects I completed and enhanced throughout my Bachelor of Science in Computer Science program. These projects demonstrate my experience with software design and engineering, algorithms and data structures, databases, application security, and full-stack development.

---

## Professional Self-Assessment

Looking back at my time in the Computer Science program at Southern New Hampshire University, I can see how much my understanding of software development has changed. When I started, I was mostly focused on learning programming languages and getting my code to work. As I progressed through the program, I started paying more attention to how applications are designed, how data is managed, and how security and performance affect the overall system. Putting together this ePortfolio gave me a chance to revisit some of my earlier projects and see how much my skills have improved. It also helped me recognize areas where I still want to continue learning.

Before pursuing my degree, I served in the United States Coast Guard and spent nearly eight years working in project management. Both experiences taught me the importance of communication, teamwork, and solving problems when things do not go as planned. I have worked with different people, managed expectations, and dealt with situations where decisions needed to be made quickly. While software development is a different field, I think those experiences have helped prepare me for it. Having that background along with my computer science education gives me experience in both technical problem-solving and working with people to accomplish a common goal.

Communication and collaboration are skills that I have continued developing throughout my coursework. Class discussions gave me opportunities to exchange ideas with other students, consider different perspectives, and explain technical concepts. I also gained experience documenting my work and explaining the decisions behind my projects. In CS 499, recording my code review required me to walk through my applications, identify problems, and explain the improvements I wanted to make. This helped me practice communicating technical information in a way that someone else could understand. My project management experience also taught me how important it is to listen to stakeholders and understand what they need before deciding how to approach a project.

Working on larger applications changed how I think about software engineering. Earlier in the program, I was mainly concerned with making individual parts of a program work correctly. As my projects became more complex, I realized how important it was to consider the overall structure of an application. Courses involving Java, C++, Python, and JavaScript gave me experience with object-oriented programming, debugging, testing, and organizing code. In CS 230 Operating Platforms, I learned more about application architecture and how software requirements influence design decisions. CS 465 Full Stack Development I gave me experience connecting frontend and backend components through REST APIs. These projects showed me that changes to one part of an application can affect other components, which is why planning and testing are so important.

One of the more interesting parts of the program for me was learning how algorithms could be used to solve different problems. I started by learning how to organize data and write algorithms that could process information efficiently. Later, I was able to apply those concepts to more advanced projects. In CS 370 Current and Emerging Trends in Computer Science, I developed an intelligent agent that used deep Q-learning to navigate a treasure hunt environment. Instead of following a fixed set of instructions, the agent learned from its experiences to make better decisions. I enjoyed that project because it introduced me to a different way of approaching programming problems and strengthened my interest in artificial intelligence and machine learning.

Before working with databases, I did not fully understand how much an application's functionality depends on how its data is organized and retrieved. Throughout the program, I worked with SQL, SQLite, and MongoDB, which gave me experience with both relational and nonrelational databases. I learned how to create and manage records, structure queries, and connect databases to applications. I also started to understand how database design can affect performance and reliability. These experiences showed me that even if an application has a good interface, it still needs a properly designed database to handle information correctly.

My understanding of software security has also changed quite a bit. Earlier in my coursework, I was mainly concerned with whether an application worked the way it was supposed to. I did not always think about what could happen if someone entered unexpected information or tried to access something they should not. CS 305 Software Security helped change that perspective by introducing me to vulnerability analysis, secure coding practices, and protecting application data. Since then, I have become more aware of the importance of input validation, authentication, authorization, and keeping sensitive information secure. I now understand that security needs to be considered throughout development rather than added after an application is finished.

As I worked through the program, my career interests also became more focused. I enjoy software development, but artificial intelligence is the area that interests me the most. Working with neural networks, reinforcement learning, and intelligent agents showed me how AI could be combined with traditional applications to create more useful and interactive experiences. I would eventually like to develop my own AI-powered applications and explore how AI can be used in video games. I am also interested in application development and UI/UX design because I think the way people interact with software is just as important as the technology behind it. My goal is to find a position where I can continue building my technical skills while gaining experience working on real-world applications.

For my capstone, I selected three projects that represent different areas of computer science. Each project gave me an opportunity to return to something I had previously developed and improve it using the knowledge I gained later in the program. I wanted my ePortfolio to show more than just completed assignments. I wanted it to demonstrate how I approach problems, make improvements, and apply what I have learned.

The first artifact is Travlr Getaways, which represents software design and engineering. This is a full-stack MEAN application that includes a customer-facing travel website and an administrative interface. For my enhancement, I added role-based access control, improved server-side validation, and protected administrative functionality. One of the biggest improvements was separating authentication from authorization so that being logged in did not automatically give someone permission to modify trip information. This project shows my ability to work with multiple technologies and improve an application's design and security.

My second artifact is the Weight Tracker Android application, which focuses on algorithms and data structures. The original application allowed users to record and manage weight entries, but it did not provide much analysis of that information. I added a structured data class and algorithms to calculate averages, weekly weight changes, trends, possible plateaus, and estimated goal dates. I also improved how the application handles dates and displays the results. This enhancement gave me an opportunity to use algorithms to turn stored data into information that could actually help someone track their progress.

The final artifact is my Animal Shelter Dashboard, which represents database development. I originally created this project using Python and MongoDB to filter and display animal shelter records. For the enhancement, I added aggregation pipelines, improved validation and error handling, and moved database connection settings into environment variables. I also converted the original Jupyter Notebook dashboard into a standalone Dash application. One of the more interesting parts of this enhancement was testing a compound index. Before adding the index, MongoDB examined 10,000 documents to return 25 matching records. After adding it, the query examined only 25 documents. Although the execution time did not improve in that test, it showed me how indexing can reduce unnecessary database scans and why performance needs to be evaluated using more than one measurement.

Together, these three projects demonstrate my experience with software engineering, algorithms, databases, and security. They also show how those areas connect. An application needs a good design, a reliable way to manage data, and algorithms that can process information effectively. Security is important across all of those areas. Looking back at these projects helped me recognize mistakes I made earlier in the program and understand how I could approach similar problems differently today. I think being able to review my own work and find ways to improve it is an important skill to carry into my career.

Finishing this degree has given me a stronger foundation in computer science and a better understanding of the direction I want to take professionally. I know I still have a lot to learn, especially when it comes to artificial intelligence and machine learning, but I feel more prepared to take on new challenges. My goal is to continue improving as a developer, gain professional experience, and eventually build my own AI-powered applications and video games. I am proud of the progress I have made, and I think these projects give potential employers a better idea of what I can do beyond what they would see on my résumé.

---

## Code Review

As part of my CS 499 capstone, I recorded a code review of the three applications selected for my ePortfolio. During the review, I examined the original code, identified areas for improvement, and explained the enhancements I planned to make.

The review covers software design and engineering, algorithms and data structures, and databases.

[Watch My CS 499 Capstone Code Review](https://youtu.be/c76sqesBoCA)

---

## Software Design and Engineering

### Travlr Getaways

Travlr Getaways is a full-stack MEAN application that includes a customer-facing travel site and an administrative interface for managing trip information. I originally developed the application as part of my computer science coursework and selected it for my capstone because it gave me an opportunity to improve the application's security and authorization design.

For my enhancement, I added role-based access control with admin and viewer roles. I also added server-side authorization for protected operations, improved input validation, protected administrative routes, and updated the Angular interface so users only see controls appropriate for their permissions. These changes improved the application's security while demonstrating the difference between authentication and authorization.

### Enhancement Highlights

- Added role-based access control with admin and viewer roles.
- Applied server-side authorization to protected API operations.
- Assigned new users the least-privileged viewer role.
- Added server-side validation and duplicate trip-code checking.
- Protected administrative Angular routes with a route guard.
- Updated the interface so administrative controls are only shown to administrators.
- Tested backend authorization and validation directly with Postman.

### Course Outcomes

This enhancement demonstrates my ability to evaluate software design decisions, work across a full-stack application, and apply a security mindset. The enhancement particularly supports Course Outcomes 3, 4, and 5 through design trade-offs, integration of multiple technologies, role-based authorization, least privilege, and server-side validation.

### Project Files

[Download the Original and Enhanced Travlr Getaways Artifact](Travlr-Getaways-Artifact.zip)

[View the Software Design and Engineering Enhancement Narrative](Travlr-Getaways-Enhancement-Narrative.docx)

---

## Algorithms and Data Structures

### Weight Tracker

Weight Tracker is an Android application built with Kotlin and SQLite that allows users to create an account, record and manage weight entries, set a goal weight, and track their weight history. I originally developed the application as part of my computer science coursework and selected it for my capstone because the stored weight data provided an opportunity to add more meaningful analysis.

For my enhancement, I created a structured WeightEntry data class and added a WeightAnalyzer class to analyze the user's weight history. The application now calculates 7-day and 30-day averages, average weekly weight change, recent weight trends, possible plateaus, and an estimated goal date. I also improved date handling, chronological sorting, input validation, and added a Progress Analysis section to the Android interface.

### Enhancement Highlights

- Added a WeightEntry data class for structured weight records.
- Added 7-day and 30-day calendar-based weight averages.
- Calculated average weekly weight change.
- Added increasing, decreasing, and stable trend detection.
- Added plateau detection using recent weight measurements.
- Added estimated goal-date calculations.
- Sorted weight history chronologically using LocalDate values.
- Added validation for weight values, entry IDs, and dates.
- Added a Progress Analysis section to the user interface.

### Course Outcomes

This enhancement demonstrates my ability to design algorithms, organize data for analysis, and integrate new functionality into an existing application. The enhancement particularly supports Course Outcomes 3 and 4 through algorithm design, structured data processing, handling edge cases, and integrating Kotlin, SQLite, and the Android interface to provide more useful information to the user.

### Project Files

[Download the Original and Enhanced Weight Tracker Artifact](WeightTracker-Artifact.zip)

[Download the Full Algorithms and Data Structures Enhancement Narrative](WeightTracker-Enhancement-Narrative.docx)

---

## Databases

### Animal Shelter Dashboard

The Animal Shelter Dashboard is a Python application that uses MongoDB to manage and analyze animal shelter records. I originally developed this project in CS 340 Client/Server Development. The application allows users to filter animal records by rescue category, view breed information through charts, and display animal locations on an interactive map.

I selected this project for my capstone because I wanted to improve how the application interacts with its database. For my enhancement, I added MongoDB aggregation pipelines to handle breed analysis directly within the database and created a compound index to improve query performance. I also improved input validation, error handling, and database connection security by moving connection settings into environment variables. Another major change was converting the original Jupyter Notebook dashboard into a standalone Dash application while maintaining its filtering, charting, and mapping features.

These improvements helped make the application more efficient, secure, and easier to maintain.

### Enhancement Highlights

- Added MongoDB aggregation pipelines for breed analysis.
- Created a compound index to reduce the number of documents examined during database queries.
- Improved filtering efficiency by reducing unnecessary document scans.
- Moved database connection settings into environment variables.
- Added input validation for database operations.
- Improved exception handling and database error reporting.
- Converted the original Jupyter Notebook dashboard into a standalone Dash application.
- Maintained rescue category filtering, interactive charts, and location mapping.
- Added testing scripts to evaluate database operations and query performance.

### Course Outcomes

This enhancement demonstrates my ability to evaluate database design decisions, improve query performance, and integrate database functionality with an existing application. The enhancement particularly supports Course Outcomes 3, 4, and 5 through database optimization, MongoDB aggregation, Python application development, input validation, and secure database configuration.

### Project Files

[Download the Original and Enhanced Animal Shelter Dashboard Artifact](AnimalShelterEnhancedAndOriginal.zip)

[Download the Full Databases Enhancement Narrative](AnimalShelter-Enhancement-Narrative.docx)

