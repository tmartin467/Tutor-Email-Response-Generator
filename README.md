# Tutor-Email-Response-Generator
Email response generator to assist and streamline responses for students who seek one-on-one tutoring at the Learning Resource Center (LRC). Built with the assistance of ChatGPT, this system enables Student Assistants to quickly create accurate messages regarding tutor availability and alternate support options.

---

## Description
A passion project created to increase efficiency and send timely responses regarding to one-on-one tutoring requests for the LRC. This system reduces human errors by generating an appropriate email in relation to the student's request.

---

## Technical Stack
  - Front-end: HTML5, JavaScript (Vanilla JS)

  - Styling: Custom CSS (responsive, modern layout)

  - Data: JSON (tutor schedules, supported courses) / (course to instructor mapping)

---

## Installation
This project is a static web application and runs entirely in the browser.

NOTE: Because the application loads local JSON files, it must be run using a local server. 

### For end-users:
1. Clone the repository: `git clone https://github.com/your-username/lrc-email-generator.git`
2. Navigate to the directory:  `cd lrc-email-generator`
3. Open the project in VS Code
4. Right-click email_generator.html
5. Select “Open with Live Server”

### For contributors:
1. Follow steps 1–3 above.
2. Open the project folder in your preferred code editor.
3. Modify:
  - email_generator.html (HTML, CSS, JavaScript)
  - tutorData_email.json (tutor schedules & supported courses)
  - EPE_instructors.json (course–instructor mapping)
4. Save changes and refresh the browser to see updates instantly.

---

## Usage
For Student Assistants:
Quickly generate accurate, professional emails for student tutoring requests.

Steps:
1. Select an Email Template Type:
  - Confirmation (In-Person)
  - Confirmation (Online)
  - Seek Alternate Tutor/Time
  - Tutor Already Booked
2. Select a Tutor
  - Supported courses and schedule populate automatically
3. Select a Course
  - Instructors list filters dynamically
  - Alternate tutors populate if applicable
4. Enter remaining details:
  - Student's name
  - Appointment date and time
  - Location or Zoom link
  - Your name
5. Click "Generate Email"
6. Click "Copy Email" and paste

---

## Known Limitations
- Static JSON data (no database or backend)
- Requires manual updates each term
- Not optimized for mobile devices
- Must be run via Live Server to load data correctly
