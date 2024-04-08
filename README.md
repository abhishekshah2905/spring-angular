# Spring Angular Application

This project is a simple web application built with Spring Boot and Angular. It demonstrates how to create a RESTful API using Spring Boot and consume it in an Angular frontend.

## Getting Started

### Prerequisites
- Java JDK 8 or higher
- Maven
- Node.js and npm installed

### Installation
1. Clone the repository:
```bash
  git clone https://github.com/abhishekshah2905/spring-angular.git
```
2. Navigate to the project directory:
```bash
  cd sprular-server
```
3. Build the project:
```bash
  mvn clean install
```
4. Run the application:
```bash
  mvn spring-boot:run
```
5. Navigate to the angular.json file directory:
```bash
  cd sprular-web/src/main/web/np-app
```
6. Install the Angular CLI if you haven't already:
```bash
  npm install -g @angular/cli
```
7. Install the frontend dependencies:
```bash
  npm install
```
8. Build the Angular application:
```bash
  ng build --prod
```
9. Access the application at http://localhost:4200/

### Configuration
- The CorsConfig class enables CORS for the API endpoints, allowing the Angular frontend to make requests to the backend.
- The Angular frontend is configured to use environment-specific settings (environment.ts and environment.prod.ts) for API endpoints and other configurations.