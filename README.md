# Hostel Student Room Allocation System

This is a web application specifically designed for allocating hostel rooms to students based on their reservation, academic marks, and distance from the hostel.

## Features

- **Reservation System**: The Hostel managing staff can reserve hostel rooms to studetns through the application.
- **Academic Marks Criteria**: Allocation of rooms can be influenced by the academic performance of students.
- **Distance Criteria**: Students living closer to the hostel may have less priority in room allocation.
- **Admin Dashboard**: An admin dashboard is provided for managing student data, room allocation, allotment process etc..
- **Automatic Allocation**: The system can automatically allocate rooms to the students based on the no of available seats in each semester as well as reserved seats for other categories.
- **Manual Override**: Admins can manually override automatic allocations if necessary.
- **Reporting**: The system generates reports on room occupancy, student distribution, and allocation statistics.

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/majid-2002/Hostel_Mangement_app.git
   ```

2. Install dependencies:

#### Frontend

   ```bash
   cd Frontend
   npm install
   npm run dev
   ```

#### Backend

   ```bash
   cd Backend
   npm install
   ```

4. Configure the environment:

    - Copy `.env.example` to `.env` and update the database configuration.
  
5. Start the application in backend:

    ```bash
    npm start
    ```

    The application should now be running on `http://localhost:3000`.

## Usage

1. Access the application through your web browser.
2. Staff can log in using their credentials and reserve hostel rooms.
3. Staff can access the dashboard to manage student data, view reports, and allocate rooms.
4. The system automatically allocates rooms based on predefined criteria, but admins can manually intervene if necessary.

