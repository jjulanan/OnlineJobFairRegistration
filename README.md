# OnlineJobFairRegistration

## Developer

- Julanan Jiwanantaprawat [@jjulanan](){:target="\_blank"}
- Wisaroot Lertthaweedech [@wisarootl]()

## Brief Decription

Demo backend project for online job fair booking

## Contents

- Problem Statement
  - Scope
  - Functional Requirements
  - Non-Functional Requirements
  - Constraints
- Digrams
  - ER Diagram
  - Class Diagram
  - [Sequence Diagrams](#sequence-diagrams) : [`Auth`](#auth), [`Booking`](#booking), [`Company`](#company)
- [Demo: Functional Requirements Verification](#demo-functional-requirements-verification)
  - [Testing as User](#testing-as-user) : [`Auth`](#auth-1), [`Booking`](#booking-1), [`Company`](#company-1)
  - [Testing as Admin](#testing-as-admin) : [`Auth`](#auth-2), [`Booking`](#booking-2), [`Company`](#company-2)
- Demo: Basic Security Testing
- Conclusion
- Developer's contribution

## Problem Statment

### Scope

### Functional Requirements

| Description                                                                                                                                                                                                                                                                                                                         | Completed |
| :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------: |
| 1. The system shall allow a user to register by specifying the name, telephone number, email, and password.                                                                                                                                                                                                                         |    ✅     |
| 2. After registration, the user becomes a registered user, and the system shall allow the user to log in to use the system by specifying the email and password. The system shall allow a registered user to log out.                                                                                                               |    ✅     |
| 3. After login, the system shall allow the registered user to book up to 3 interview sessions by specifying the date (during May 10th-13th, 2022) and the preferred companies. The company list is also provided to the user. A company information includes the company name, address, website, description, and telephone number. |    ✅     |
| 4. The system shall allow the registered user to view his interview session bookings.                                                                                                                                                                                                                                               |           |
| 5. The system shall allow the registered user to edit his interview session bookings.                                                                                                                                                                                                                                               |           |
| 6. The system shall allow the registered user to delete his interview session bookings.                                                                                                                                                                                                                                             |           |
| 7. The system shall allow the admin to view any interview session bookings.                                                                                                                                                                                                                                                         |           |
| 8. The system shall allow the admin to edit any interview session bookings.                                                                                                                                                                                                                                                         |           |
| 9. The system shall allow the admin to delete any interview session bookings.                                                                                                                                                                                                                                                       |           |
| 10. The system shall allow the admin to create/update/delete company. (addition from requirement in assignment)                                                                                                                                                                                                                     |           |

### Non-Functional Requirements

### Constraints

## Diagrams

### ER Diagram

![er diagram](./doc_asset/diagrams/er_diagram.svg)
[full size image](./doc_asset/diagrams/er_diagram.svg)

### Class Diagram

![class diagram](./doc_asset/diagrams/class_diagram.svg)
[full size image](./doc_asset/diagrams/class_diagram.svg)

### Sequence Diagrams

#### Auth

- Get Me

  ![get me](./doc_asset/diagrams/squence_diagrams/auth/get_me.svg)

  [full size image](./doc_asset/diagrams/squence_diagrams/auth/get_me.svg)

- Login

  ![login](./doc_asset/diagrams/squence_diagrams/auth/login.svg)

  [full size image](./doc_asset/diagrams/squence_diagrams/auth/get_me.svg)

- Logout

  ![logout](./doc_asset/diagrams/squence_diagrams/auth/logout.svg)

  [full size image](./doc_asset/diagrams/squence_diagrams/auth/get_me.svg)

- Register

  ![register](./doc_asset/diagrams/squence_diagrams/auth/register.svg)

  [full size image](./doc_asset/diagrams/squence_diagrams/auth/get_me.svg)

#### Booking

#### Company

## Demo: Functional Requirements Verification

### Testing as User

#### Auth

#### Booking

#### Company

### Testing as Admin

#### Auth

#### Booking

#### Company

## Demo: Basic Security Testing

## Conclusion : Significant Change from VacQ project

## Developer's Contribution

<!-- ## Function testing with Postman

<a name="paragraph1"></a>

### Testing as user

#### Auth

![user register test](./doc_asset/function_test/user/01_register.png)

#### Company

#### Booking

### Testing as admin

#### Auth -->
