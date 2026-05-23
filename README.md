# Etiquette-
ExpenseMate is a Flutter-based Android expense tracker built by Team Etiquette that lets you log daily expenses, auto-detect UPI transactions via SMS, manage spending categories, and visualize your finances through an intuitive analytics dashboard — making personal finance tracking effortless and smart


ExpenseMate
Objective
The ExpenseMate project was developed to simplify personal finance management for students and individuals by creating an intuitive and efficient daily expense tracking application for Android. The application allows users to manually log daily expenses, automatically detect UPI and bank transactions through SMS parsing, categorize spending, and visualize financial patterns through a detailed analytics dashboard. The main objective was to provide a smart, all-in-one expense management tool that reduces the effort of manual bookkeeping while offering meaningful insights into spending behavior.
This project provided practical experience in mobile application development, database management, real-time notification handling, UI/UX design, and understanding how technology can be applied to solve everyday personal finance challenges.

Skills Learned

Hands-on experience in cross-platform mobile application development using Flutter and Dart.
Understanding of local database management using SQLite and Hive for persistent data storage.
Knowledge of Android SMS reading permissions, background services, and real-time notification handling.
Experience in designing clean, user-friendly interfaces with multi-screen navigation and dynamic components.
Improved problem-solving and teamwork skills through collaborative development under a project guide.
Understanding of data visualization techniques using chart libraries within Flutter.
Experience in creating structured project documentation, failure reports, and presentation assets.
Strengthened communication and collaboration skills while working as part of Team Etiquette.


Tools & Technologies Used

Flutter & Dart for cross-platform Android mobile application development.
SQLite / Hive for local database storage of expense records and categories.
Android SMS Listener API for background SMS reading and UPI transaction detection.
Flutter Local Notifications for real-time push notifications when transactions are detected.
Syncfusion / FL Chart for rendering bar charts, pie charts, and analytics visualizations.
Figma / Canva for UI design prototyping and presentation assets.
Git & GitHub for version control and team collaboration.
Android Studio / VS Code for development, emulation, and testing.
PowerPoint & PDF Tools for project documentation and presentation creation.


Steps
Below are the key steps involved in the development of ExpenseMate:
1. Problem Identification and Research
The first phase focused on identifying common challenges students and individuals face when managing daily expenses. Research was conducted to understand how people currently track spending, the limitations of existing apps, and how SMS-based UPI notifications could be leveraged to automate transaction detection.
Ref 1: Problem Analysis and Planning
This screenshot represents the planning phase where core features, user pain points, and the overall project workflow were identified and mapped out.

2. UI/UX Design
In this phase, the user interface of the application was designed to ensure a clean, intuitive, and user-friendly experience. Layouts were created for the Home screen, Analytics screen, Add Expense screen, Category Management screen, and the SMS detection notification system.
Ref 2: UI Design Prototype
This image shows the UI/UX prototype and screen flow designed for the ExpenseMate application prior to development.

3. Application Development
The development phase involved building all frontend and backend functionalities of the application. Key features implemented included manual expense logging with category tagging, a Floating Action Button (FAB) restricted to the Home screen, multi-chart Analytics dashboard with spending breakdowns and smart insights, SMS-based UPI transaction detection running as a background service, and real-time push notifications triggered upon detecting bank messages even when the app is closed.
Ref 3: Application Development
This screenshot showcases the core development and feature implementation phase of the ExpenseMate system, including navigation architecture and database integration.

4. Testing and Debugging
After development, the application was rigorously tested across multiple Android devices and emulators to ensure proper functionality. Test cases were designed for expense logging, category filtering, SMS detection accuracy, chart rendering, and notification delivery. Multiple bugs related to Flutter syntax corruption, FAB visibility logic, and chart data rendering were identified and resolved during this phase.
Ref 4: Testing Process
This image highlights the testing and debugging phase, including device-level permission checks and notification behavior validation.

5. Final Deployment and Presentation
The project was presented and demonstrated across all review stages. Presentation assets including a workflow diagram, PPTX slide deck, and a comprehensive PDF failure report were prepared. The system demonstrated how automation and smart design can work together to simplify daily financial tracking for Android users.
Ref 5: Final Project Presentation
This screenshot displays the final presentation and working demonstration of ExpenseMate, including its analytics dashboard and SMS detection workflow.

Challenges Faced During Development
Although the ExpenseMate project successfully passed the Zeroth Review, First Review, and Second Review stages with positive feedback, critical technical issues surfaced during the Final Review phase that could not be resolved within the available timeframe.
The project was developed using Flutter, which enabled rapid UI development and smooth cross-platform performance. However, during the final implementation phase, the core SMS-based transaction detection feature encountered a fundamental platform-level restriction that blocked its full functionality.
The major challenges included:

Android SMS Permission Restrictions — Android's evolving privacy policies placed strict limitations on third-party apps reading SMS content in the background, making it nearly impossible to reliably intercept UPI and bank transaction messages without device-level permissions that are not granted to standard user-installed apps.
UPI Notification Unreliability — Different banking apps and UPI platforms send notifications in inconsistent formats, making it difficult to build a universal SMS parser that worked accurately across all banks and payment providers.
Background Service Instability — The background listener service responsible for detecting incoming SMS was frequently killed by Android's battery optimization system, causing missed transaction detections during real-world usage.
Notification Delivery Failures — Push notifications triggered through Flutter Local Notifications behaved inconsistently across different Android versions and manufacturer-specific OS customizations.
Limited Time for Optimization — The compounding nature of these issues left insufficient time before the Final Review to implement alternative approaches such as Notification Listener Service or accessibility-based workarounds.

Due to these technical difficulties rooted in Android's SMS privacy architecture, the project could not be completed to its intended final working condition and development was temporarily halted. Despite this, the project delivered significant learning in mobile development, system design, debugging under constraints, and professional project documentation.

Conclusion
ExpenseMate was an innovative personal finance tracking application designed to automate and simplify daily expense management through smart SMS detection and visual analytics. Even though the project encountered fundamental Android-level permission restrictions during the Final Review stage that prevented the complete working of the SMS detection feature, it successfully demonstrated strong technical capability, creative problem-solving, and a deep understanding of real-world mobile development challenges. The project also provided hands-on exposure to Flutter development, database management, notification systems, UI design, and collaborative software engineering as Team Etiquette
