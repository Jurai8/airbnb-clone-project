
# AirBnB Clone

## Overview

This is a comprehensive, real-world application designed to simulate the development of a robust booking platform like Airbnb. It involves a deep dive into full-stack development, focusing on backend systems, database design, API development, and application security. This project enables learners to understand complex architectures, workflows, and collaborative team dynamics while building a scalable web application.

## Technology Stack

- HTML
- CSS
- JS
- Python
- Django: a web framework for building RESTful APIs
- MySQL
- GraphQL

## Database Design

### Key entities

- Users
  - bookings made
  - payment history
- Properties
  - amount of Bookings
  - schedule for Bookings
  - reviews
- Bookings
  - user id
  - property id
  - date
  - duration
- Reviews
  - property id
  - value of review associated with property ( 5 stars )
  - review (text)
- Payments
  - user id
  - payment amount
  - payment date

## Feature Breakdown

- User Management
  - manage how users book, pay and review properties
- Property Management
  - track which properties have been booked
  - allow properties to be reviewed
- Booking System
  - keep track of which days properties are booked for
  - track which users have booked said property
- Payment Management
  - allow users to pay to confirm a booking
  - send a receipt to the users
- Review System
  - allow users to review a property
  - assign reviews to properties

## API Security

- Authentication
  - verify a user's identity, preventing unauthorized access to systems, data, and resources
- Authorization
  - maintainins security and integrity within systems by controlling access to resources and actions, ensuring only authorized users and processes can perform specific operations
- Rate Limiting
  - maintains the stability, security, and efficiency of systems and services
  - protects against various attacks like DDoS, brute-force, and API abuse, while also optimizing resource usage and enhancing user experience

## CI/CD Pipeline

These are automated workflows that streamline the software development process by integrating and testing code changes frequently and then automating the release and deployment of those changes. With this we can detect any issues early on

### Tools

- GitHub Actions
- Docker

## Team Roles

- Software engineer (back & frontend)
- Test automation engineer
- DevOps engineer
