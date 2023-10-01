# SmartHome Web Application

SmartHome is your comprehensive web application designed to be the ultimate dashboard for controlling microcontrollers in your home.

## Overview

SmartHome is a state-of-the-art platform that provides a seamless interface for managing and controlling various microcontroller-based devices in your home. It’s designed with simplicity and efficiency in mind, ensuring that you have complete control over your home automation systems at your fingertips.

## Features

With SmartHome, you can monitor and control a wide range of devices such as:

- Lighting systems
- Heating and cooling units
- Security systems
- Kitchen appliances

The dashboard provides real-time data and allows you to adjust settings, schedule operations, and automate tasks with just a few clicks.

## Compatibility

SmartHome is compatible with a variety of microcontrollers, making it a versatile tool for any smart home setup. It’s designed to provide a user-friendly experience, regardless of your technical expertise. With its intuitive design and easy-to-navigate interface, managing your home has never been easier.

Experience the future of home automation with SmartHome - your personal command center for a smarter, more efficient home.

## Technologies Used

- **Mosquitto MQTT Broker:** A lightweight, open-source message broker that enables IoT devices to communicate with each other efficiently and reliably.
- **Entity Framework Core:** Microsoft's modern object-database mapper for .NET, which allows for interacting with databases using .NET objects.
- **Blazor Web App:** A web UI framework where components run on the server, with UI updates, event handling, and JavaScript calls being handled over SignalR connections.
- **SignalR:** A library for ASP.NET developers that simplifies the process of adding real-time functionality to applications via websockets.
- **HTML, CSS, and JavaScript:** Core technologies for building the structure, design, and functionality of web pages and web applications.
- **Cloudinary:** A cloud service that offers solutions for image and video management, including uploads, storage, transformations, optimizations, and delivery.

## Prerequisites

Before running the project, ensure you have the following prerequisites installed:

- [.NET Core SDK](https://dotnet.microsoft.com/download) (v8 or later)
- [Visual Studio](https://visualstudio.microsoft.com/downloads/) or [Visual Studio Code](https://code.visualstudio.com/download)
- A compatible database server (e.g., SQL Server, PostgreSQL)

## Getting Started

1. Clone the repository:
```command
git clone https://gitlab.com/unrealbg/SmartHome.git
````
2. Open the project in your preferred IDE (e.g., Visual Studio or Visual Studio Code).

3. Configure the Database:

- Open the appsettings.json file.
- Update the ConnectionStrings section with the connection string for your database server.

Here is an image of the database schema for reference:
![Database Schema](https://drive.google.com/uc?id=12z4iXl9P9Ud5XxjybpCln-INAl4jV2tT1_)

And here's the SQL script for database generation:

[View the Database Generation Script here](https://drive.google.com/uc?id=134r7LQHFS33aA5rsIYHePAPPETD9pHfa1w1)

4. Apply Database Migrations:

- Open the terminal or command prompt.
- Navigate to the project directory.
- Run the following commands:

```commands
dotnet restore
dotnet ef database update
```
5. Build and Run:

- Build and run the Blazro Web App project.
- Navigate to the Client directory.
- Run the following commands:
```commands
dotnet restore
dotnet build
dotnet run
```
### Usage
Open your web browser and navigate to https://localhost:5001 to start using the SmartHome application.

### Help
If you encounter any problems or issues, please open an issue on this GitHub repository.

## Contributing
#### Contributions to the SmartHome project are welcome! Here are a few ways you can contribute:

- Report bugs or issues by submitting GitHub issues.
- Suggest new features or enhancements.
- Submit pull requests with bug fixes or code improvements.

### Authors
[Zhelyazko Zhelyazkov](https://github.com/UnrealBG) 

### Version History
* 0.1
- Initial Release
### License
#### This project is licensed under the [MIT License](https://github.com/unrealbg/smarthome/-/blob/main/LICENSE).
