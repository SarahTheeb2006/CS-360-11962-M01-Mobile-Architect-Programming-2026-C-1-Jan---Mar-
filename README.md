# CS-360-11962-M01-Mobile-Architect-Programming-2026-C-1-Jan---Mar-

CS 360 - Mobile App Development Portfolio Artifact

Project Three: 

WeightTracker Mobile Application Overview

The WeightTracker mobile application was created to assist people monitor and control their weight in a straightforward, systematic, and consistent manner. The app's major purpose is to give users with a secure and simple platform for logging daily weight entries, reviewing previous data, updating or deleting records, and receiving SMS reminders to keep on track. This software was created to meet the requirement for accountability and long-term health monitoring while without overwhelming users with needless functionality. WeightTracker is an effective tool for individuals who want to measure their progress and maintain healthy behaviors.

Screens and User Centered Design

The application features a secure login screen, a data entry screen for tracking weight, and the ability to change and delete prior entries. SQLite is used for permanent local data storage, which means that information is saved even after the app is closed. The interface was purposefully meant to be clean and simple, with clear labeling, well-organized layouts, and easy navigation between activities. Input validation guarantees that users cannot input empty or wrong data, increasing reliability and user trust. The general design keeps users in mind by eliminating complexity and emphasizing ease of use, making the software accessible to beginners while still allowing for constant tracking.

Coding Approach and Development Strategy

I addressed development in stages, first completing the UI design from Project Two and then connecting the layouts to Java code in Android Studio. I created a DatabaseHelper class to manage SQLite database interactions, ensuring that concerns are separated and the code is orderly. CRUD capability was carefully implemented to allow users to easily create, read, update, and delete weight entries. I also included SMS reminder feature, which requires proper Android permissions management and safe user interaction. Throughout development, I prioritized modular code principles and step-by-step implementation to reduce errors and increase maintainability. This systematic method can be used for future mobile applications, stressing planning, organized architecture, and continuous testing.

Testing & Debugging

I tested the app repeatedly in the Android emulator to ensure that it worked properly. I validated that login validation worked properly, saved and retrieved weight records from the SQLite database, and tested update and delete actions. I also ensured that SMS permissions were properly handled and that navigating between activities was seamless. Android Studio's Logcat was used to detect runtime faults and debug database management and activity transitions. This testing method was crucial because it validated the app's stability, dependability, and usability prior to final submission.

Innovation & Challenges

One of the most difficult challenges I faced was ensuring sufficient database persistence while maintaining seamless transitions between operations. I improved the DatabaseHelper implementation to prevent data loss and ensure that entries are correctly retrieved. Another problem was handling Android permissions for SMS functionality while keeping the user experience consistent. Overcoming these obstacles necessitated study, debugging, and iterative testing. This experience helped me improve my problem-solving skills and understanding of Android app architecture.

Demonstrated Knowledge and Skills.

The seamless integration of SQLite database capability with a user-centered interface exemplifies my knowledge and talents in this project the most. Implementing comprehensive CRUD operations, secure login validation, SMS reminder integration, and organized navigation displays my knowledge of mobile app architecture, data persistence, object-oriented programming, and user interface design. This project demonstrates my progression from writing basic functional code to creating a full, organized, and user-friendly mobile application that is ready for deployment.
