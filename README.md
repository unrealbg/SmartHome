# SmartHome Web Application

## Description

SmartHome is a comprehensive web application designed to be the ultimate dashboard for controlling microcontrollers in your home. Developed using Blazor, Postgres database, Entity Framework Core, HTML, CSS, and JavaScript, it provides a seamless interface for managing and controlling various microcontroller-based devices in your home.

## Getting Started

### Dependencies

* .NET 5.0 or later
* PostgreSQL
* A modern web browser that supports WebAssembly

### Installing

* Clone the repository
```bash
git clone https://github.com/YourUsername/SmartHome.git
```
* Navigate to the project directory and install the dependencies
```
cd SmartHome
dotnet restore
```
* Update the database connection string in appsettings.json
* Run the database migrations
```
dotnet ef database update
```
* Start the application
```
dotnet run
```
### Usage
Open your web browser and navigate to https://localhost:5001 to start using the SmartHome application.

### Help
If you encounter any problems or issues, please open an issue on this GitHub repository.

### Authors
@unrealbg

### Version History
* 0.1
- Initial Release
### License
This project is licensed under the MIT License - see the LICENSE.md file for details
