# Jordan Franke

## Computer Science ePortfolio

Welcome to my computer science ePortfolio. This portfolio highlights projects I completed and enhanced throughout my Bachelor of Science in Computer Science program. These projects demonstrate my experience with software design and engineering, algorithms and data structures, databases, application security, and full-stack development.

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
