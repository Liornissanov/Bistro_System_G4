# Bistro Restaurant Management System

A Java desktop application for restaurant reservations, waiting lists, and table management. Four software engineering students developed it as a semester project for course 61756, Methods for Software Development.

## What the system does

| Workflow | Features |
| --- | --- |
| Customer visits | Guests and subscribers can make or cancel a reservation, join the waiting list, and check in for a table. |
| Restaurant operations | Staff can manage reservations, waiting lists, current diners, tables, and subscriber records. |
| Payments and reports | The client includes a payment screen and separate reports for visit times and subscriber activity. |

## Architecture

The **JavaFX client** presents the workflows through FXML screens. It sends requests over **OCSF** to the **Java server**, which processes them and uses **MySQL** for persistent data.

## Final submission

| Location | Contents |
| --- | --- |
| [Project source](Assignment3/PROJECT/) | Java client, server, and supporting modules |
| [Database script](Assignment3/DB/G4_Assignment3_DB.sql) | SQL script for the final submission |
| [Packaged applications](Assignment3/JAR/) | Client and server JAR files |
| [Project documents](Assignment3/DOC/) | Supporting documentation |
| [Assignment 1](Assignment1/) and [Assignment 2](Assignment2/) | Earlier milestones |

## Team members

- [Lior Nissanov](https://github.com/Liornissanov)
- [Tal Klerman](https://github.com/klerman-tal)
- [Liem Dahan](https://github.com/liemdahan)
- [Michal Pomiankevich](https://github.com/Michal-Pomiankevich)
