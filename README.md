# Project Proposal

## What
To build a resource reservation application for Hotel business.
The resource reservation app will be used by the Sale department of the hotel.
The app shall provides the online reservation facilities to the Sale so that she can immediately create a reservation
online via talk to the customer. The app also provide the automation process for create and manage of issuing the
quotation to the customer.

## Objectives
* Design and develop all business logic associated to the application
* Design and construct relational database for support domain modules
* Design User Interface and User Experience (UI/UX) for the application
* Develop API and provide RESTful endpoint for the Front-end app
* Develop Frontend application
* Develop the continuous integration and deployment automation process
* Develop and perform both integration test and end-to-end test

## Scopes
* To have a functional RESTful API that provide neccessary CRUD operations for the reservations and quotations
* Implement a notification system that send email to the targets when certain events were triggered
* Implement Frontend application according to the UI mockup design
* Deploy application to the Could server

## Team
There will be 2 teams take care of this project. Each team has one Backend engineer and one Frontend engineer.
The team will be allocated for develop specified modules exclusively for each team.
For the common development tasks, everyone in the teams will be required to take responsible, hands-on and decide togather such
as manage the git repository, continuous deployment. There will be some dedicated tasks assigns to an engineer
specifically too. All engineers activities and efforts will be log in the project report.

### Team A

Team member
| Backend  | Frontend |
| ----     | ----     |
| ALF @zx4545zx  | Ben @Benjawan1999 |

Responsible Tasks
| #    | Task   | Scope   | Remark |
| ---- | ----   | ----    | ----   |
| 1    | Implement HTTP Basic Authentication for User | * User is able to authenticate to the application with email and password | |
| 2    | Develop User module              | * Implement CRUD operation for the User module | |
| 3    | Develop Customer module          | * Implement CRUD operation for the Customer module | |
| 4    | Develop Quotation module         | * Implement CRUD operation for the Quotation module<br>*Design REST API endpoint for Quotation response in JSON | |
| 5    | Develop the Notification module  | * Design and implement the notification API<br>* Design and implement the background process flow for dispatching the notification | |
| 6    | Develop the calendar timeslot UI | * Render the reservation view period that support the view in Day, Week and Month | |
| 7    | Reservation invalidation module  | * Design and implement invalidation process of the existing reservation<br>* Develop the corresponding UI for invalidation realization | optional |

### Team B
| Backend  | Frontend |
| ----     | ----     |
| Mild @Mildyani  | Toon @pdtoon |

Responsible Tasks
| #    | Task   | Scope   | Remark |
| ---- | ----   | ----    | ----   |
| 1    | Develop the Venue module          | * Implement CRUD operation for the Venue module | |
| 2    | Develop the Package module        | * Implement CRUD operation for the Pacakge module | |
| 3    | Develop the Reservation module    | * Implement CRUD operation for the Reservation module<br>*Design REST API endpoint for Reservation module<br>*Implement validation logics for validate the reservation period and validity | |
| 4    | Develop the TimeSlot management module | * Design and implement the validation logic and process to validate the confliction of the timeslot<br>* Design and implement business logic to handle overlap windows of the reservation period | |
| 5    | Develop the calendar dashboard and card component | * Render the reservation card that place in the dashboard | |
| 6    | Manage the multiple conflict reservation periods  | * Implement the placement logic for conflict reservation period inside timeslot UI. | optional |

  
### Common Tasks
There are common tasks that everyone will have to learn, decide and develop togather
* Application UI Design, wireframe, mockup and review
* CI/CD operation
* Database design schema/fields
* REST API endpoints
* Unit Test

### Common responibilities
* Clean up the code before commit
* Manage and respect Git commit / merge rules
* Update the assigned card status in the Github project


## Project Charecteristics
| Item         | Description                                                           |
| ----         | ----                                                                  |
| Type         | Web application                                                       |
| Architecture | [Micro Service](https://en.wikipedia.org/wiki/Microservices)          |
| Backend API  | [Ruby on Rails](https://irubyonrails.org/)                            |
| Frontend     | [NextJs](https://nextjs.org/)                                         |
| CI/CD        | [Docker](https://www.docker.com/) / [Drone.io](https://www.drone.io/) |
| Cloud server | [Linode](https://www.linode.com/)                                     |
| Repository   | https://github.com/hellospec/electrum-go                              |
| App Mockup      | [Figma](https://www.figma.com/file/GkVXwkRfIx9JxoIfKptxFl/reservation_app?node-id=3%3A2)
