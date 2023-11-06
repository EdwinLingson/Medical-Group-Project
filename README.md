# Medical-Group-Project

This marked our inaugural team project, where we embarked on the development of an Angular Frontend paired with a Spring Boot Backend, all backed by a MySQL database.

The fundamental workflow involved patients inputting their data into the application, which, in turn, presented them with a list of suitable doctors. Patients could then select a doctor and an appointment time. Doctors had the ability to view and edit appointment times, while administrators were responsible for managing doctors. Users could also oversee their appointments using their unique Appointment ID and User ID.

On the backend, we implemented basic CRUD (Create, Read, Update, Delete) operations, with certain endpoints handling more intricate business logic. An interesting aspect of our approach was working on the frontend and backend concurrently. Instead of developing the backend first and then the frontend, we took a different path, and this method allowed us to better comprehend and seamlessly integrate the services.

Within the frontend, we established components that communicated with each other through services and route parameters. We used "For" and "If" directives to dynamically render pages and headers based on the logged-in user. One challenge we encountered was implementing these directives to secure available appointment times following responses from the backend.

Throughout this project, we also grappled with our initial experience of merging a deleted file branch. This taught us the importance of being cautious when adding and merging files in version control systems, especially when working as a team for the first time. These experiences fostered a sense of teamwork and collaboration.
