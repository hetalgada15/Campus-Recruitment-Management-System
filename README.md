# Campus Recruitment Management System

The **Campus Recruitment Management System** is a database-driven application designed to streamline the recruitment process between students and companies on a campus. This project was developed to efficiently handle job postings, applications, and eligibility matching, providing a centralized portal for students to explore opportunities and for organizations to manage listings. 

## Course

DAMG 6210: Database Management and Database Design

---

## Problem Statement

The recruitment process on campus can often be complex, involving numerous steps to match students with the right opportunities. This system aims to simplify and enhance the recruitment experience by automating job listings, student applications, and eligibility checks, creating a streamlined, user-friendly portal.

## Proposed Solution

The **Campus Recruitment Management System** provides a comprehensive portal for:

1. **User Registration**: All participants, including students and organizations, must create IDs via a login portal.
2. **Student Applications**: Students can apply to multiple placement listings available on the platform.
3. **Organization Listings**: Organizations are required to post at least one placement listing, ensuring students have ample options to explore.
4. **Eligibility Matching**: The system evaluates student eligibility based on predefined criteria, such as skills and academic qualifications, to match students with suitable job postings.

## Key Features

- **Database Design**: Designed with a clear ER Diagram to model relationships between students, organizations, and placements.
- **Data Manipulation**: Includes SQL-based implementations for table creation, value insertion, and various stored procedures.
- **Custom Views**: Provides views for eligibility checks, allowing quick assessment of student qualifications for specific roles.
- **Triggers**: Implements triggers to update organization names dynamically.
- **User-Defined Functions**: Custom functions were created to support business rules and enhance data handling.
- **Data Visualization**: Visual reports were generated to summarize placement and application data.

## Entities and Business Rules

- **Entities**:
  - Students
  - Organizations
  - Placement Listings

- **Business Rules**:
  - Each participant must register via the login portal.
  - Students can apply to multiple placements.
  - Each organization must have at least one active listing.
  - Students may or may not have prior work experience.

## Implementation Details

1. **Database Structure**:
   - **Tables**: Created tables for each primary entity (Students, Organizations, Placements).
   - **ER Diagram**: Defined relationships between entities, establishing a clear data model.

2. **Stored Procedures**: Procedures to manage data efficiently, including functions to insert and update records.

3. **Custom Views**: Predefined views to streamline eligibility checking for students applying to placements.

4. **Triggers**: Automated triggers to maintain consistency, such as updating organization names when necessary.

5. **User-Defined Functions**: Functions to calculate and validate data points according to the project’s business logic.

6. **Visualizations**: Generated insights using visualization tools, illustrating key metrics such as application success rates and placement availability.

## Future Enhancements

Potential future features include enhancing the eligibility matching process with machine learning models, adding a notification system for updates, and implementing analytics for both students and organizations to track engagement and performance.

## License

This project is licensed under the MIT License.
