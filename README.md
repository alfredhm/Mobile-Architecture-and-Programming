# CS-360 Mobile App Portfolio Artifact – Project Three

## App Overview and User Needs
The requirements of this project was the creation of an android inventory management application coded in Android Studio IDE that could be functionally used to track inventory objects added to it. Features required by users are basic application functions such as adding inventory, updating quantities, deleting items, and sending notifications. Other requirements of the users were for this information to be easy to read, the ability to save information between sessions, and having the application be intuitive to use.

## Screens, Features, and User-Centered UI Design
Functionalities added to this application to meet these requirements were a login screen, screens to view/add inventory, delete inventory, as well as the capability to send notifications. Considerations for UI/UX were made with grouping related information together on the screen, and limiting unnecessary buttons and text. Activities were broken up to simplify common user actions, allowing the user to achieve their goals with as few interactions as possible. Decisions regarding the UI/UX were effective because they allowed for simple viewing of information as well as simplified actions that did not overburden the user with complex navigation or understanding of the app.

## Development Approach and Strategies
The app was developed using an incremental approach by breaking requirements into smaller, manageable tasks and implementing features step by step. Code was structured to remain modular and readable, with clear separation between UI logic and data handling. This strategy reduced errors, simplified debugging, and improved overall maintainability. These techniques can be applied to future projects to support scalability and collaborative development.

## Testing and Validation
Testing of this application was done throughout the development process by using Android Emulator, printing to logs, and repeated usage. I confirmed correct use of the database, button listeners, activity redirects, proper permission requests, and information persisting after restarting the application all using these methods. I feel that this testing process was effective because the emulator and repeated usage simulate actual use of the application. Using the logs allowed me to catch errors in functionality that may have been difficult to find while manually testing. One bug I found was associated with information not persisting between sessions, as well as another related to sending notifications after deleting an inventory item.

## Innovation and Problem Solving
One challenge I faced was having the inventory actually save between sessions. In order to resolve this, I had to rework some of my database handling as well as the activity lifecycle in order to properly save and utilize information.

## Areas of Strength and Demonstrated Skills
The inventory database implementation and its integration with the user interface represent a strong demonstration of my skills. This component highlights my understanding of mobile architecture, data persistence, user interaction handling, and Android development best practices. Overall, the project demonstrates my ability to plan, design, develop, test, and refine a complete mobile application.
