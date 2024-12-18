<h1 align="left"># Planner Application - Personal and Group Travel Management Application</h1>

###

<p align="left">A website to plan and management your trips and some other related functionalities.</p>

###

<h2 align="left">## Deployed Demo on Vercel. Access it here:<br><br>https://planner-front-gold.vercel.app</h2>

###

<h2 align="left">I've coded this application with</h2>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" height="40" alt="java logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" height="40" alt="spring logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="40" alt="docker logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="40" alt="react logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="40" alt="typescript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="javascript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original-wordmark.svg" height="40" alt="tailwindcss logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-line-wordmark.svg" height="40" alt="amazonwebservices logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" height="40" alt="github logo"  />
</div>

###

<p align="left">## How to Use the Application<br><br>
### Steps<br><br>
#### Planner Application<br>1. Access: https://planner-front-gold.vercel.app<br>2. Register: Click "Sign Up" if you don’t already have an account.<br>3. Log in: Authenticate using the email and password created during registration.<br>4. Trips - Creating a Trip:<br>   https://planner-front-gold.vercel.app/trips/<br>   4.1 - Enter the destination.<br>   4.2 - Select the trip dates.<br>   4.3 - *Click Continue.*<br>   4.4 - Invite others to your trip (optional): Invite new participants to your trip. Click "Invited People," enter their email address, and click "Invite" to send them an email invitation to your trip. After inviting, close the modal and click *Confirm Trip.*<br>   *Note:* If no one else is added to the trip, the application owner (mirandax.gui13@gmail.com) will be automatically added and invited. You can remove this user after the trip is created!<br>   **Participant Confirmation:** Participants need to register and log in to confirm their participation in the trip. Once confirmed, they can co-manage the trip with the owner.<br>   4.5 - Trip Confirmation: Confirm the trip creation by entering your registered email and name.<br>5. Managing Your Trip: On the trip page (https://planner-front-gold.vercel.app/trips/"yourtrip"), you can access features that interact with the API endpoints:<br>   5.1 - Edit trip dates and destination: Modify the destination and dates of your trip anytime.<br>   5.2 - Create activities for your trip: Add activities planned for your trip by specifying a title, date, and time.<br>   5.3 - Register links: Add important links for your trip by providing a title and valid URL.<br>   5.4 - Guest management modal: Manage trip participants by adding or removing them. Enter the email and name of the guests, and we’ll send them an invitation email.<br><br>## For issues, bugs, or questions about the application, contact me:<br><br>- **Email**: mirandax.gui13@gmail.com<br>- **LinkedIn**: https://www.linkedin.com/in/mirandagui/</p>

###

<p align="left">## Project Structure<br><br>The project is divided into two main repositories:<br><br>1. **Frontend**: Contains the user interface, implemented with React and TypeScript. The frontend consumes REST services from the backend.<br><br>2. **Backend**: Contains the RESTful API supporting the application's features. It was developed with Java and Spring Boot and uses a PostgreSQL database for data storage.<br><br>## CI/CD<br><br>The *Planner* uses **GitHub Actions** to implement a continuous integration and delivery process, automating testing and deployment for both the frontend and backend.<br><br>- **Frontend**: Deployed automatically to Vercel after each merge into the main branch.<br>- **Backend**: Deployed to AWS EC2 using Docker images created during the GitHub Actions workflow.<br><br>## Technologies Used<br><br>
### Backend<br>- **Java 17**<br>- **Spring Boot**<br>- **Maven**<br>- **PostgreSQL** (database)<br>- **Docker** (for containerization)<br>- **AWS EC2** (hosting)<br><br>
### Frontend<br>- **React**<br>- **TypeScript**<br>- **JavaScript**<br>- **Vite**<br>- **Vercel** (hosting)<br><br>
### Integration and DevOps<br>- **GitHub Actions** (for CI/CD)</p>

###
