# Student Management Web Service – SOAP

A student management application built around a SOAP web service, with Java and PHP clients consuming the service operations.

## Overview

This project demonstrates how to expose student-management operations through a SOAP web service and consume them from different client applications.

The Java server provides operations to manage student records stored in a database. A Java client and a PHP client call the service to perform these operations.

## Features

- Retrieve and display the list of students.
- Add a new student.
- Update an existing student's information.
- Delete a student by ID.
- Access the same service from both Java and PHP clients.
- Verify changes against the database.

## Architecture

The project is organized around three main parts:

1. **SOAP web service (Java server):** exposes student-management methods, including listing, adding, updating and deleting students.
2. **Java client:** calls the SOAP service operations to manage student records.
3. **PHP client:** consumes the SOAP service and displays student records with actions to add, update and delete them.

## Technologies and Concepts

- Java
- SOAP Web Services
- PHP
- Database integration
- Client-server architecture
- CRUD operations
- Service consumption from multiple programming languages

## Learning Objectives

This project helped practice designing and consuming a SOAP web service, implementing CRUD operations for student records, and integrating clients developed in different programming languages with a shared service.

## Author

Raky Gueye
