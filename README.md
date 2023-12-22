𝐎𝐯𝐞𝐫𝐯𝐢𝐞𝐰
A comprehensive web service for managing a cyber cafe, facilitating user registration, computer details, and seamless assignment management. It efficiently assign and remove computers for users, ensuring a smooth cyber cafe experience.

𝐅𝐞𝐚𝐭𝐮𝐫𝐞𝐬
1.User Management: Add, view user details.
2.Computer Management: Add, view computer details.
3.Assignment: User can send request for assign a available computers if any free computers are there it will assigned to requested user.
4.Unassignment: User can send request for unassigning assigned computers.

𝐓𝐞𝐜𝐡𝐧𝐨𝐥𝐨𝐠𝐢𝐞𝐬 𝐔𝐬𝐞𝐝
-> Java
-> Spring Boot
-> Hibernate (JPA)
-> RESTful APIs
-> MySQL
𝐆𝐞𝐭𝐭𝐢𝐧𝐠 𝐒𝐭𝐚𝐫𝐭𝐞𝐝
-> Clone the Repository using below command:
git clone https://github.com/saurabhxo/cybercafeCRUD.git
->Database Configuration:
Configure your database details in "application.properties".
Build and Run:
./mvnw clean install
./mvnw spring-boot:run

The application will be accessible at http://localhost:8080.

𝐀𝐏𝐈 𝐄𝐧𝐝𝐩𝐨𝐢𝐧𝐭𝐬:
1.User-related APIs: "/users".
2.Computer-related APIs: "/computers".
3.User with Computer Assignment APIs: "/usersWithComputer".
𝐒𝐚𝐦𝐩𝐥𝐞 𝐑𝐞𝐪𝐮𝐞𝐬𝐭𝐬:
Use tools like Postman to interact with the APIs.
