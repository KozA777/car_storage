# Car Management System

## Overview

The **Car Management System** is an Angular-based web application that allows users to store and manage information about cars and their services in the browser's localStorage. Users can add cars to the system and record detailed information about each car's services, including parts and costs. The application provides an intuitive interface for viewing, updating, and deleting cars and their associated service details.

## Features

- **Add Cars**: Users can add cars to the system with details like name, model, and registration.
- **Store Service Information**: For each car, users can add services, including part names and costs, which are displayed in the car's details view.
- **View Cars**: All cars stored in the system are listed with their details and the option to view, edit, or delete them.
- **LocalStorage Persistence**: All car and service data is stored in the browser’s localStorage, ensuring persistence between sessions.
- **Delete Car**: Users can delete a car and all its associated service records with a confirmation dialog.
- **CSV Export**: Users can export the list of cars, including their service details, to a CSV file.

## Installation

### Prerequisites

Before running the application, ensure you have the following installed:

- [Node.js](https://nodejs.org/)
- [Angular CLI](https://angular.io/cli)

### Steps

1. Clone the repository:

   ```
   git clone https://github.com/your-username/car-management-system.git
   cd car-management-system
   ```
2. Install the dependencies:
```
npm install
```
3. Run the application:
```
ng serve
```
4. Open the app in your browser:

```
http://localhost:4200
```
## Usage
- Add a Car: Click on the "Add Car" button, enter the car's name, model, and registration, and save the car.
- View Car List: The car list shows all added cars. Click on a car to view its details and services.
- Add Service: In the car details view, add services by specifying the part and cost, which will be displayed in the list.
- Delete Car: Use the delete button to remove a car. A confirmation dialog will ask for verification before deletion.
- CSV Export: Click the export button to download the list of cars and their services as a CSV file.

## Technologies Used
- Angular: Frontend framework for building the application.
- TypeScript: Primary language used for development.
- LocalStorage: Used to persist car and service data across sessions.
  
## Future Enhancements
- Edit Service Information: Allow users to edit existing service records for each car.
- Search Functionality: Implement a search feature to filter cars by name or model.
- Responsive Design: Optimize the application for mobile devices.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

