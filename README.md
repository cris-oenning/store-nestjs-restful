# Study Project in Nest.Js - Registration of Users and Products for a Marketplace

This project is a simple application developed in Nest.Js, created as part of a study on building Restful APIs. The main objective is to allow the registration of users and products for an imaginary "Marketplace", where users will be able to register their login information and register their products available for sale. It is important to highlight that the project was developed without using a database, focusing on learning the fundamental concepts of Nest.Js.

# Main Functionalities

The project has the following features:

* User Registration: The system allows new users to register, providing basic login and identification information.

* Product Registration: Users who are already registered can register the products they wish to make available on the Marketplace, providing information about the products that are for sale.

* Data Receipt and Validation: The system is capable of receiving data sent by users during user and product registration. In addition, custom validations were implemented using decorators to ensure data integrity and avoid possible errors during the process.

* Registration Flow: The project follows a well-defined flow for the registration of users and products, making the process more intuitive and organized.

# Technologies Used

* Nest.Js: The Node.Js framework was chosen due to its efficiency and ease of building APIs.

* Restful API: The application follows the principles of a Restful API, ensuring a consistent design and standardized interactions.

* Data Validation with Decorators: Using custom decorators for data validation makes code more readable and maintenance simpler.

# How to Run the Project

1 - Make sure you have Node.Js installed on your machine.
2 - Clone this repository and access the project directory.
3 - Install the dependencies using the command in the terminal "npm i".
4 - Run the project in the terminal with the command "npm run start:dev".
5 - Access the Restful API through the local address and configured port (by default, http://localhost:3000).

# Conclusion

This project is an excellent opportunity to familiarize yourself with the Nest.Js framework, as well as understand important concepts of building Restful APIs. Through the use of custom decorators for data validation, it is possible to avoid errors and ensure the consistency of information provided by users.

Keep in mind that this is a study project, and for production scenarios it is recommended to use a database to store user and product information. We hope this application is useful for your journey of learning Nest.Js and developing robust and efficient APIs...