![Group 23](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/52442e4071c47a48fe24047c9be670615c528b83/static/img/cms_long.png)

### The world’s most high-end designed, lightweight, and feature-rich learning management system.

# College management system

Learning management system using Django web framework. You might want to develop a learning management system (also known as a school/college management system) for a school/college organization, or simply for the purpose of learning the tech stack and enhancing your portfolio. In either case, this project would be a great way to get started. The aim is to create the world's most lightweight yet feature-rich learning management system. However, this is not possible without your support, so please give it a star ⭐️.

_Documentation is under development_

Let's enhance the project by contributing! 👩‍💻👩‍💻

<img width="1440" alt="screenshot" src="https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/e22cd1b496ad113e001b118c81f8854bddbf1856/ss/Screenshot%202025-04-17%20200510.png">

## Current features

- Dashboard: School demographics and analytics. Restricted to only admins
- News And Events: All users can access this page
- Admin manages students(Add, Update, Delete)
- Admin manages lecturers(Add, Update, Delete)
- Students can Add and Drop courses
- Lecturers submit students' scores: _Attendance, Mid exam, Final exam, assignment_
- The system calculates students' _Total, average, point, and grades automatically_
- Grade comment for each student with a **pass**, **fail**, or **pass with a warning**
- Assessment result page for students
- Grade result page for students
- Session/year and semester management
- Assessments and grades will be grouped by semester
- Upload video and documentation for each course
- PDF generator for students' registration slip and grade result
- Page access restriction
- Storing of quiz results under each user
- Question order randomization
- Previous quiz scores can be viewed on the category page
- Correct answers can be shown after each question or all at once at the end
- Logged-in users can return to an incomplete quiz to finish it and non-logged-in users can complete a quiz if their session persists
- The quiz can be limited to one attempt per user
- Questions can be given a category
- Success rate for each category can be monitored on a progress page
- Explanation for each question result can be given
- Pass marks can be set
- Multiple choice question type
- True/False question type
- Essay question type................._Coming soon_
- Custom message displayed for those that pass or fail a quiz
- Custom permission (view_sittings) added, allowing users with that permission to view quiz results from users
- A marking page which lists completed quizzes, can be filtered by quiz or user, and is used to mark essay questions

# Quick note for future contributors

If you would like to contribute, simply begin by implementing one from the list in the `TODO.md` file.

# Requirements:

> The following program(s) are required to run the project

- [Python3.8+](https://www.python.org/downloads/)

# Installation

- Clone the repo with

```bash
git clone https://github.com/SkyCascade/SkyLearn.git
```

- Create and activate a python virtual environment

```bash
pip install -r requirements.txt
```

- Create `.env` file inside the root directory

- Copy and paste everything in the `.env.example` file into the `.env` file. Don't forget to customize the variable values

```bash
python manage.py migrate
```

```bash
python manage.py createsuperuser
```

```bash
python manage.py runserver
```

Last but not least, go to this address http://127.0.0.1:8000

## Admin UI
Admin Login
- username: admin_username
- Password: admin_password
![login (65)](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/e22cd1b496ad113e001b118c81f8854bddbf1856/ss/Screenshot%202025-04-17%20200416.png)

Admin Dashboard
![login (65)](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/e22cd1b496ad113e001b118c81f8854bddbf1856/ss/Screenshot%202025-04-17%20200510.png)

Admin Profile
![login (65)](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/4107ae7ce7afcd27119e0139a3bf171a42316031/ss/Screenshot%202025-04-19%20194859.png)

Profile Edit
![Edit](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/4107ae7ce7afcd27119e0139a3bf171a42316031/ss/Screenshot%202025-04-19%20194944.png)

![Confirm](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/4107ae7ce7afcd27119e0139a3bf171a42316031/ss/Screenshot%202025-04-19%20194957.png)

Admin Panel

![panel](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/5fe5d6560a1fcffbe25b9a3c9e06b46245b1a320/ss/Screenshot%202025-04-19%20195011.png)

Lecturer List

![Lecturer](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/9b7feab9ef50d6ab019484f98ddd5a7ac2405429/ss/Screenshot%202025-04-19%20195023.png)

Add Lecturers

![add](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/9b7feab9ef50d6ab019484f98ddd5a7ac2405429/ss/Screenshot%202025-04-19%20195124.png)

![Added](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/9b7feab9ef50d6ab019484f98ddd5a7ac2405429/ss/Screenshot%202025-04-19%20195310.png)

Add Program and Course

![add](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/befaff1ab752c6483a2e122e017f4ecd36687625/ss/Screenshot%202025-04-20%20205517.png)

![list](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/befaff1ab752c6483a2e122e017f4ecd36687625/ss/Screenshot%202025-04-20%20205552.png)

![addCourse](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/8b610ec2d8961ac4b9bc5cf681c42df8c316614c/ss/Screenshot%202025-04-20%20205606.png)

![courseForm](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/8b610ec2d8961ac4b9bc5cf681c42df8c316614c/ss/Screenshot%202025-04-20%20205849.png)

![Confirm](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/8db18ed25abddb6e02f40c17f197ae88af224ada/ss/Screenshot%202025-04-20%20205954.png)

Add Student

![list](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/df1f88ecd673b2bce378b564bb5f33f5d19dde9c/ss/Screenshot%202025-04-20%20204642.png)

![addStudent](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/38355cd26878cff456061c72ad529f8b8fa6b221/ss/Screenshot%202025-04-20%20210158736.png)

![Confirm](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/38355cd26878cff456061c72ad529f8b8fa6b221/ss/Screenshot%202025-04-20%202102736.png)

![studentProfile](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/38355cd26878cff456061c72ad529f8b8fa6b221/ss/Screenshot%202025-04-20%202109378.png)

## Lecturer UI

Create/Forgot/Reset Password

![reset](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/dced687617d265c22ff532fc82b2a3379781ec00/ss/Screenshot%202025-04-19%20195344.png)

![forget](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/dced687617d265c22ff532fc82b2a3379781ec00/ss/Screenshot%202025-04-19%20195410.png)

![EmailReset](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/dced687617d265c22ff532fc82b2a3379781ec00/ss/Screenshot%202025-04-19%20195426.png)

![mail](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/dced687617d265c22ff532fc82b2a3379781ec00/ss/Screenshot%202025-04-19%20195453.png)

![ConfirmPass](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/dced687617d265c22ff532fc82b2a3379781ec00/ss/Screenshot%202025-04-19%20195527.png)

![Confirmation](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/9dcc4f625626a2981d3789556d731be2dec8749d/ss/Screenshot%202025-04-19%20195551.png)

Lecturer Login

![login](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/9dcc4f625626a2981d3789556d731be2dec8749d/ss/Screenshot%202025-04-19%20195648.png)

lecturer Home

![home](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/f0a27cf3161dd71f4a531883df6ad5e370f8e6f8/ss/Screenshot%202025-04-19%20195701.png)

Profile

![profile](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/f0a27cf3161dd71f4a531883df6ad5e370f8e6f8/ss/Screenshot%202025-04-19%20195725.png)


## Student UI

Student Login

![reset](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/7c4e996287f68542533734f232b1fab8df6ab9ba/ss/Screenshot%202025-04-19%20195410.png)

![mail](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/7c4e996287f68542533734f232b1fab8df6ab9ba/ss/Screenshot%202025-04-20%20225047.png)

![password](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/7c4e996287f68542533734f232b1fab8df6ab9ba/ss/Screenshot%202025-04-19%20195527.png)

![resetsuccess](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/7c4e996287f68542533734f232b1fab8df6ab9ba/ss/Screenshot%202025-04-19%20195551.png)

![login](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/7c4e996287f68542533734f232b1fab8df6ab9ba/ss/Screenshot%202025-04-20%20225525.png)

Student Home

![studentHome](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/7c4e996287f68542533734f232b1fab8df6ab9ba/ss/Screenshot%202025-04-20%20225911.png)

![studentProfile](https://github.com/KiranKumarMalik/College-Management-System-using-Django/blob/7c4e996287f68542533734f232b1fab8df6ab9ba/ss/Screenshot%202025-04-20%20230135.png)


# References

- Quiz part: https://github.com/tomwalker/django_quiz

#### Show your support by ⭐️ this project!
