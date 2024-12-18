# 🌍 Planner: Group Travel Management Application

*Planner* is an application designed for managing group trips. It simplifies the organization of events, activities, invitations, and more, fostering a collaborative experience for participants.

## 🚀 Deployed Demo on Vercel. Access it here:

🔗 https://planner-front-gold.vercel.app

## 🛠️ Technologies Used

### Backend
- **Java 17** ☕
- **Spring Boot** 🌱
- **Maven** 📦
- **PostgreSQL** (database) 🗄️
- **Docker** (for containerization) 🐳
- **AWS EC2** (hosting) ☁️

### Frontend
- **React** ⚛️
- **TypeScript** 📘
- **JavaScript** 🟨
- **Vite** ⚡
- **Vercel** (hosting) 🌐

### Integration and DevOps
- **GitHub Actions** (for CI/CD) 🤖

## 🏗️ Project Structure

The project is divided into two main repositories:

1. **Frontend**: Contains the user interface, implemented with React and TypeScript. The frontend consumes REST services from the backend.

2. **Backend**: Contains the RESTful API supporting the application's features. It was developed with Java and Spring Boot and uses a PostgreSQL database for data storage.

## 🔄 CI/CD

The *Planner* uses **GitHub Actions** to implement a continuous integration and delivery process, automating testing and deployment for both the frontend and backend.

- **Frontend**: Deployed automatically to Vercel after each merge into the main branch.
- **Backend**: Deployed to AWS EC2 using Docker images created during the GitHub Actions workflow.

## 📝 How to Use the Application

### 🧭 Steps

#### Planner Application
1. 🌐 Access: https://planner-front-gold.vercel.app
2. 🖊️ Register: Click "Sign Up" if you don’t already have an account.
3. 🔑 Log in: Authenticate using the email and password created during registration.
4. ✈️ Trips - Creating a Trip:
   🔗 https://planner-front-gold.vercel.app/trips/
   4.1 - Enter the destination. 📍
   4.2 - Select the trip dates. 📅
   4.3 - *Click Continue.* ➡️
   4.4 - Invite others to your trip (optional): Invite new participants to your trip. Click "Invited People," enter their email address, and click "Invite" to send them an email invitation to your trip. After inviting, close the modal and click *Confirm Trip.* ✅
   *Note:* If no one else is added to the trip, the application owner (mirandax.gui13@gmail.com) will be automatically added and invited. You can remove this user after the trip is created!
   **Participant Confirmation:** Participants need to register and log in to confirm their participation in the trip. Once confirmed, they can co-manage the trip with the owner.
   4.5 - Trip Confirmation: Confirm the trip creation by entering your registered email and name.
5. 🔧 Managing Your Trip: On the trip page (https://planner-front-gold.vercel.app/trips/"yourtrip"), you can access features that interact with the API endpoints:
   5.1 - Edit trip dates and destination: Modify the destination and dates of your trip anytime. 📍
   5.2 - Create activities for your trip: Add activities planned for your trip by specifying a title, date, and time. 📝
   5.3 - Register links: Add important links for your trip by providing a title and valid URL. 🔗
   5.4 - Guest management modal: Manage trip participants by adding or removing them. Enter the email and name of the guests, and we’ll send them an invitation email. 👥

## 🛠️ For issues, bugs, or questions about the application, contact me:

- **📧 Email**: mirandax.gui13@gmail.com
- **🔗 LinkedIn**: https://www.linkedin.com/in/mirandagui/

