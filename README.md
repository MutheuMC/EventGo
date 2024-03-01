# EventoGo - Event ticketing System

As a web application developer, you are required to develop a ticket booking system application. Here are the requirements.
- The administrator should be able to add/ edit or remove events.
- For each event, the admin should be able to specify the ticket price specifying ticket type (VIP and regular).
- Admin should also be able to specify the maximum number of attendees.
- Users should be able to view events details and reserve tickets (VIP or regular) NB: One user can reserve up to 5 tickets.
- The user should then be able to get an email notification for the successful reservation.




**Prerequisites**
* Node.js and npm installed
* MongoDB Database

**Instalaltion**
1. Clone the repository to your local machine.
2. Navigate to the project directory. use two terminal <br>
    **Cd Client** - For Frontend <br>
    **Cd api** - For Backend <br>
3. Install server dependenciesfor both frontend and backend.
4. Create a .env file in the root directory with the following content, and replace placeholders with your own values. <br>
     MONGODB_URI=mongodb://localhost/your-database-name
5. Start the server.<br>
     **ems/api:** nodemon start<br>
     if the command is not working use **PowerShell -ExecutionPolicy Bypass nodemon** this command.
7. Start the Client:<br>
      **ems/client:** npm run dev

**The application should now be running. You can access it at http://localhost:5173**<br>
**The Server is running on http://localhost:4000**

<h1>Thank You</h1>

