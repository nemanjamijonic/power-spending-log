# Energy Consumption Forecast and Realization Tracker

## Description

This project, part of a Memory Virtualization course, aims to develop a multi-layered C# application that tracks and calculates the deviation between forecasted and actual electrical energy consumption. Data is imported from CSV files and processed by a WCF service, which is accessed through a console user interface. The application supports storing data in an XML database or an in-memory database, depending on the configuration.

## Features

- Data Import: Import data about forecasted and actual energy consumption from CSV files.
- Deviation Calculation: Calculate the deviation between forecasted and actual consumption per hour. The deviation can be calculated as absolute percentage deviation or squared deviation.
- Data Storage: Data can be stored in an XML database or in an in-memory database.

## Architecture

The application consists of the following layers:

- **Database layer:** An XML or in-memory database for data persistence.
- **Service layer:** Handles business logic, file parsing, and calculation tasks.
- **Client layer:** Console user interface for user interactions.
- **Common:** Shared entities and utilities.

## Setup

Detailed setup instructions will be included at a later date, once the application has been fully developed.

## Technologies Used

- C#
- WCF (Windows Communication Foundation)
- .NET Framework

## Participants

- Luka Vidaković PR 137/2020 [LukaVidakovic]
- Nemanja Mijonić PR 138/2020 [nemanjamijonic]
- Olivera Čakan PR 71/2020 [oli167]
- Milica Klincov PR 70/2020 [klincovmilica]
