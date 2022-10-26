# Cinema application
*This application is a simplified version of the cinema service. It allows user registration, creating shopping cart, ordering tickets and scrolling necessary information for administrators*
## :large_orange_diamond: Project description
### Features:
- Registration, authentication and authorization;<br />
  *It is possible to register a new user, log in to an existing account, and operate the service from that account depending on the role given.*
- Scrolling through the information;<br />
  *The user has the ability to view the available movies, as well as orders. The administrator can also view detailed information about cinema halls and the user database.*
- Information handling;<br />
  *The user has an opportunity to buy tickets (selectively add it to a shopping cart with further purchase). The administrator is given the opportunity to change the hall information, availability of movies and its sessions.*
## :large_orange_diamond: Project structure
##### *This project has N-tier architecture. It consists of:*
- Controller - accept http requests from users and display information.
- Service - all business-logic is located here.
- DAO - all interaction with DataBase is located here
## :large_orange_diamond: Instructions for launching the project
- Fork this repository
- Clone the repository to PC
- Edit ***db.properties*** class - set needed parameters to establish connection to your own DataBase
- Install Apache Tomcat.\
  *Apache Tomcat 9.0.50 you can download [here](https://archive.apache.org/dist/tomcat/tomcat-9/v9.0.50/bin/)*
- Configure the Tomcat server in your IDEA and Run the project.<br />
## :large_orange_diamond: Used technologies
- Java
- Spring Web
- Spring Security
- Hibernate
- MySQL
- Apache Maven 3.8.1
- Apache Tomcat 9.0.50
