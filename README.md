# Angular Task Management App – Services & Dependency Injection Deep Dive

A feature-rich Angular Task Management application built to explore and master Angular's **Services** and **Dependency Injection (DI)** system. The project demonstrates how Angular manages shared state, service instances, dependency resolution, and custom providers through a practical real-world application.

## 🌐 Live Demo

https://angular-task-management-app-service.vercel.app/

## 📖 Overview

This project was created to gain hands-on experience with Angular's dependency management architecture while building a functional task management application.

Users can create tasks, update their status, and filter tasks based on their current state. The application leverages Angular Services for centralized state management and demonstrates various Dependency Injection concepts used in scalable Angular applications.

## 🚀 Features

* Create new tasks with title and description
* View all tasks in a clean task board
* Filter tasks by status:

  * All
  * Open
  * In-Progress
  * Completed
* Update task status dynamically
* Color-coded task status badges
* Responsive and modern dark-themed UI
* Centralized task management using Angular Services
* Reusable and modular component architecture

## 🛠️ Angular Concepts Covered

### Services

* Creating and consuming services
* Sharing data across components
* Managing application state with services

### Dependency Injection (DI)

* Constructor-based dependency injection
* Service registration and providers
* Understanding Angular's injector system

### Hierarchical Injectors

* Root-level providers
* Component-level providers
* Service instance scope and lifetime

### DI Resolution Process

* How Angular resolves dependencies
* Injector hierarchy traversal
* Provider lookup mechanism

### Injection Tokens & Values

* Creating custom Injection Tokens
* Providing primitive values
* Using custom providers

## 📂 Project Structure

```text
src/
├── app/
│   ├── components/
│   ├── services/
│   ├── models/
│   └── shared/
├── assets/
└── styles/
```

## 🎯 Learning Objectives

This project focuses on understanding:

* How Angular Services work behind the scenes
* The Dependency Injection lifecycle
* Injector hierarchy and service scope
* State management using services
* Custom dependency providers and Injection Tokens
* Building maintainable and scalable Angular applications

## 🏃 Getting Started

### Clone the repository

```bash
git clone <repository-url>
```

### Install dependencies

```bash
npm install
```

### Run the development server

```bash
ng serve
```

Navigate to:

```text
http://localhost:4200
```

## 🧰 Technologies Used

* Angular
* TypeScript
* HTML5
* CSS3

## 📸 Application Highlights

* Task creation form
* Dynamic status updates
* Task filtering functionality
* Service-driven state management
* Dependency Injection examples
* Modern dark UI design

## 📜 License

This project is created for learning and educational purposes.
