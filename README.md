
# 🎓 School CRM — Role-based Feature Plan

This School CRM system provides two main roles with distinct feature sets: **Admin** and **Student**.

---

## 🎓 Student Side (SkoolSync)

### Dashboard Overview
- Personalized welcome message
- Profile avatar and logout
- Global search bar (Courses, Exams, etc.)

### Features:
- **🕒 Time Table**  
  View the daily subject schedule with time slots.

- **📅 Attendance**  
  Track attendance with a color-coded calendar:
  - Green: Present
  - Red: Absent
  - Gray: Holiday
  - White: Not Updated

- **📘 Class Diary**  
  Daily subject-wise homework and notes uploaded by teachers.

- **🧪 Mock Tests**  
  Access and attempt mock tests. View scores and feedback.

- **📝 Assignments**  
  View subject-wise assignments with submission status and upload options.

- **📖 Exams**  
  View upcoming exam schedule, subjects, and dates.

- **📊 Results**  
  View performance reports for each assessment (e.g., FA-1, SA-1).

- **💰 Fees**  
  Check term-wise fee status and make online payments (optional).

---

## 🛠️ Admin Side

### Dashboard Overview
- Quick stats: Total students, teachers, fee status, attendance
- Notifications panel (optional)

### Features:
- **📅 Manage Timetable**  
  Create and update subject schedules for each class and section.

- **✅ Upload Attendance**  
  Mark daily attendance by selecting class, section, and date.

- **📓 Upload Class Diary**  
  Upload daily homework or notes for each subject.

- **🧪 Manage Mock Tests**  
  Create tests, upload questions, set durations, and track scores.

- **📄 Upload Assignments**  
  Post assignments by subject and due date. Track submissions.

- **📝 Upload Exam Schedule**  
  Add exam details (subject, date, time) per class and term.

- **📊 Update Results**  
  Input student marks, calculate performance, and publish results.

- **💰 Manage Fees**  
  Update payment status (Paid/Not Paid) for each student by term.

- **🔔 Push Notifications** *(optional)*  
  Send updates or alerts to students or parents.

---

## 🧭 UI & Navigation
- Left-side vertical nav panel for easy access
- Role-based access:
  - Students: View-only access to their own data
  - Admins: Full CRUD capabilities for managing all data

---

> 💡 This design ensures efficient school management while offering students a user-friendly dashboard to stay updated with their academic life.
