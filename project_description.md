Build a daycare software that can track attendance, and build profiles of children within the program.
The software should be able to process an application with roughly the following data:
guardians names
address
contact numbers
authorized pickups
work phone and address
etc
Student
name
nickname
interests
address
guardian
school
age
ethnicity
country of origin
languages
grade
teacher
learning concerns
health concerns / food allergies / family issues / mental health concerns
emergency contact info
medical release forms
custody forms (if necessary)
Should be associated with guardians and family
weight
height
physical description
Software should provide system of assigning children to groups(pods), special coursework to ensure success, or special groups based on interests
Software needs a form for Counselor applications and placements
attendance and performance tracking for counselors.
*Provide an interface for counselors to:
facilitate attendance and snack recording
facilitate day to day operations - provide homework
provide time fillers / games
provide status updates on students
provide interface for taking notes on students
provide ability to make commendations / hand out demerits

Plan has become more refined by the MVP

The MVP uses ocr to create and process a standardized paper system that can
easily integrate with existing paper systems.

Post Daily Report is the goal.

STAGE ONE: APPLICATION, ATTENDANCE, READ STUDENT RECORD
  1) Build terminal program to intake new applicants.
    import application.json to use as template for questions
    create new file for each new applicant
  1a) Add functionality for retrieving and viewing the student data
  1b) Add counselor object
  1c) Add functionality for dividing students into pods based on grade lvl assign counselor
  1d) Create letters to applicants and their guardians with contracts to sign
  1e) Add functionality to update the student files with signed contracts
  2) build simple web form with all the placeholders for the other app
  3) merge and debug
  4) build
STAGE TWO WILL BE BUILDING INTERNAL PROGRAM TO FACILITATE PHYSICAL ASSESSMENT FOR THE DEPARTMENT OF HEALTH AS WELL KEEP RECORDS, BUILD STATISTICAL ANALYSIS REPORTS
STAGE THREE WILL BE IMPLEMENTING CURRICULUM AUTOMATION TO
