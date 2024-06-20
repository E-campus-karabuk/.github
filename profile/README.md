# E-Campus Student Automation System - Organization Overview

## Overview

Welcome to the Student Automation System repository. This repository is part of a comprehensive suite that includes the web application, backend services, and mobile application designed to streamline academic processes and enhance communication between students and lecturers. Developed by a dedicated team of four Computer Engineering students from Karabuk University, this system aims to provide a seamless academic experience through advanced automation and efficient communication tools.

## Team Members

- **Mohamad ZUBI** - [GitHub](https://github.com/MOHAMAD-ZUBI)
- **Muhannad SALKINI** - [GitHub](https://github.com/muhannadsalkini)
- **Nisreen BOUTA** - [GitHub](https://github.com/nisreenbouta)
- **Roula KOURANI** - [GitHub](https://github.com/R-Kourani)

## Features

### For Students

1. **Student Academic Information:**
   - Access schedules, exam timetables, and GPA.
   - Centralized hub for academic organization.
   - Monitor academic progress continuously.

2. **Request Submission:**
   - Submit recommendation letters, grade objections, and internship applications.
   - Efficient communication processes.

3. **Department Profile Exploration:**
   - Insights into lecturers, courses, and department history.
   - Informed decision-making for academic pursuits.

4. **AI Chatbot:**
   - Quick access to information on university rules and guidelines.

### For Lecturers

1. **Automated Lecturer Schedule:**
   - Efficient time management with a clear view of upcoming classes and office hours.

2. **Academic Information Section:**
   - Showcase expertise, background, qualifications, and research interests.
   - Transparency for students.

3. **Resource Sharing:**
   - Share lecture notes, presentation slides, and external resources.
   - Enhances student learning experiences.

4. **Request Management:**
   - Efficiently handle recommendation letters and internship opportunities.

## Repository Structure

This organization includes the following repositories:

### 1. Web Application (React Web Frontend)

This repository contains the full-stack web application built with React.

- **Clone the Repository:**
   ```bash
   git clone https://github.com/E-campus-karabuk/React-Web-Front.git
   ```

### 2. Backend Services (NodeJS Backend)

This repository contains the backend services and APIs supporting the web and mobile applications.

- **Clone the Repository:**
   ```bash
   git clone https://github.com/E-campus-karabuk/NodeJS-Backend.git
   ```

### 3. Mobile Application (React Native)

This repository contains the mobile applications for both iOS and Android platforms, built with React Native.

- **Clone the Repository:**
   ```bash
   git clone https://github.com/E-campus-karabuk/React-Native.git
   ```

## Getting Started

Follow these instructions to set up and run the entire suite on your local machine for development and testing.

### Prerequisites

- Ensure you have Node.js and npm installed.
- MongoDB installed and running.
- [Expo CLI](https://docs.expo.dev/get-started/installation/) for mobile development.

### Setup Instructions

#### Web Application

1. **Install Dependencies:**
   ```bash
   cd React-Web-Front
   npm install
   cd client
   npm install
   ```

2. **Configure MongoDB:**
   - Configure the database connection in `server/config/keys.js`.

3. **Run the Server:**
   ```bash
   cd ..
   npm run server
   ```

4. **Run the Client:**
   ```bash
   cd client
   npm start
   ```

#### Backend Services

1. **Install Dependencies:**
   ```bash
   cd NodeJS-Backend
   npm install
   ```

2. **Run the Server:**
   ```bash
   npm start
   ```

#### Mobile Application

1. **Install Dependencies:**
   ```bash
   cd React-Native
   npm install
   ```

2. **Start the Mobile Application:**
   ```bash
   expo start
   ```

### Accessing the Applications

- **Web Application:** Open your browser and navigate to `http://localhost:3000`.
- **Backend Services:** Ensure the backend is running on the designated port (default is 5000).
- **Mobile Application:** Use the Expo app on your mobile device to scan the QR code provided by `expo start`.

## Contributing

If you would like to contribute to this project, please reach out to us via GitHub.

## License

This project is licensed under the Tubitak License.

## Acknowledgments

We appreciate all the guidance and support provided by our professors and peers throughout the development of this project. Feel free to contact the project maintainers with any questions or feedback.
