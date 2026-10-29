# RDS Student Portal

Course project for CSE 215 (Object-Oriented Programming Lab).

A JavaFX desktop application for managing student records, courses and academic information, with separate portals for admins and students.

## Team

- **Shishir Baidya** (24137) - [shishirbaidya](https://github.com/shishirbaidya)
- **MD. Konok-Uz-Zaman** (24121) - [konokuzzaman](https://github.com/konokuzzaman)

## Features

**Admin**
- Add and manage students and faculty
- Add courses, attendance and CGPA records
- Post updates and notifications for students

**Student**
- View attendance, CGPA and previous grades
- Browse course details and prerequisites, and select courses
- View fee information
- Submit faculty evaluations

**Login**
- Separate admin and student login with an image captcha

## Tech Stack

- Java 23
- JavaFX (FXML + CSS)
- Maven
- File-based storage (`Student_and_faculty_DATABASE/`)

## How to Run

Make sure JDK 23 is installed, then from the project folder run:

```
./mvnw clean javafx:run
```

On Windows:

```
mvnw.cmd clean javafx:run
```

Or open the project in IntelliJ IDEA and run `HelloApplication`.

Demo login details are in `src/Login_Info.md`.
