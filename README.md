# edu-ques
Introduction

EduQuest is an interactive, web-based learning platform designed to make self-paced education engaging, structured, and easy to track. With the growth of online education, learners often struggle to organize learning materials, monitor progress, and stay motivated. EduQuest addresses these challenges by providing a unified dashboard where learners can access lessons, track completed topics, visualize progress, and assess their understanding through quizzes.
The platform is developed using core web technologies such as HTML, CSS, and JavaScript, making it lightweight, accessible, and easy to deploy without the need for complex backend infrastructure.

Problem Statement

Learners using self-paced educational resources often face issues such as:
*Lack of structured learning paths
*Difficulty in tracking completed and pending lessons
*No visual feedback on learning progress
*Limited motivation due to absence of milestones or assessments
EduQuest aims to solve these problems by offering a clean, intuitive, and interactive learning dashboard.

Objectives of EduQuest

*To organize learning content into structured lessons and modules
*To allow users to track completed and pending lessons
*To visualize learning progress using progress bars
*To include quizzes for self-assessment
*To improve learner motivation through badges and milestones
*To provide a responsive and accessible user interface

Scope of the Project

The scope of EduQuest includes:
*Frontend-only implementation using HTML, CSS, and JavaScript
*Browser-based data storage using localStorage
*Responsive design suitable for desktop and mobile devices
*Support for future enhancements such as certificates and analytics
The project does not include backend servers, databases, or user authentication in its current version.

System Overview

EduQuest operates as a single-page web application. Users interact with lessons and quizzes, and their progress is saved locally in the browser. Upon revisiting the site, previously completed lessons and quiz scores are restored automatically.

Technology Stack

*HTML5: Structure and content of the website
*CSS3: Styling, layout, responsiveness, and dark mode
*JavaScript (ES6): Application logic, progress tracking, quiz functionality
*localStorage API: Client-side data persistence

Functional Requirements

*Display lessons organized by category or module
*Allow users to mark lessons as completed
*Track completed and pending lessons
*Visualize learning progress using a progress bar
*Provide quizzes for self-assessment
*Toggle dark mode for better usability
*Store user progress and quiz scores locally

Non-Functional Requirements

*Usability: Simple and intuitive interface
*Performance: Fast loading with minimal resources
*Scalability: Easy to add more lessons and quizzes
*Reliability: Consistent data storage using localStorage
*Accessibility: Readable fonts, contrast-friendly colors

System Architecture

EduQuest follows a client-side architecture:

*Presentation Layer: HTML & CSS
*Logic Layer: JavaScript
*Data Layer: Browser localStorage
There is no server-side processing involved.

Module Description

The system is divided into the following modules:
*Dashboard Module
*Lesson Management Module
*Progress Tracking Module
*Quiz Module
*Theme & Accessibility Module

User Interface Design

The UI is designed using minimalistic principles with soft colors and clear typography. Cards are used to separate different sections such as progress, lessons, and quizzes.

Lesson Management Module

This module displays lessons grouped into categories. Each lesson includes a checkbox to mark it as completed. JavaScript listens for changes and updates progress accordingly.

Progress Tracking Module

The progress module calculates completion percentage based on completed lessons and displays it using a progress bar. A completion badge is shown when all lessons are finished.

Quiz & Assessment Module

The quiz module presents multiple-choice questions. It dynamically loads questions and options, validates answers, and calculates the final score.

Dark Mode & Accessibility Features

EduQuest includes a dark mode toggle to reduce eye strain. CSS variables are used to switch themes dynamically.

Data Storage & localStorage Usage

User data such as lesson completion and quiz scores are stored using the browser’s localStorage API. This ensures persistence without requiring a backend database.

Challenges Faced
*Structuring modular lesson data
*Managing dynamic UI updates
*Ensuring responsiveness across devices
*Maintaining clean and readable code

Testing & Validation

The application was tested for:
*Lesson completion accuracy
*Progress calculation correctness
*Quiz navigation and scoring
*Data persistence after page reload

Future Enhancements

*User authentication system
*Certificate generation upon completion
*Advanced analytics and charts
*Backend integration
*Mobile application version

Conclusion

EduQuest successfully demonstrates how a simple yet powerful learning platform can be built using core web technologies. It provides structured learning, progress tracking, and self-assessment features in a clean and user-friendly manner. The project can be further expanded to support real-world educational use cases.
