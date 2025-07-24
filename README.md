# Task Scheduler API

A Spring Boot RESTful API for managing and processing scheduled tasks with custom business logic. This system is designed to handle task creation, prioritized processing, and enforce valid status transitions.

## ✨ Features

- ✅ Create new tasks with unique string IDs
- 📥 Retrieve task details
- 🔄 Update task status with validation (pending → processing → completed)
- 🧠 Automatically fetch the next task to process based on shortest time and earliest submission
- 📃 List pending tasks with sorting and limit options

## 🧱 Tech Stack

- Java 17
- Spring Boot
- JPA / Hibernate
- MySQL / H2
- Maven

## 🚀 API Endpoints

### Create a Task
