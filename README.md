# Event Planner - Full-stack application for creating, attending and managing events

- **Front End (Angular):** [Git Repo](https://github.com/kzi-nastava/iks-project-event-planner-siit-2024-team-10)
- **Back End (Spring Boot):** [Git Repo](https://github.com/kzi-nastava/iss-project-event-planner-siit-2024-team-10)
- **Mobile App (Android Java):** [Git Repo](https://github.com/kzi-nastava/ma-project-event-planner-siit-2024-team-10)

---

## About
Event Planner is a mobile and web application which deals with planning events like celebrations, conferences, team building, etc.

This application uses the following tools:
 - Angular (TS, HTML, CSS), Bootstrap, JWT, Leafelt
 - Java, Spring Boot, PostgreSQL
 - Android SDK

This application has multiple user roles, depending on which, they are able to interact with the app in different ways:

### **Unauthenticated User (UA):**

* Can search all open-type services/products/events
* Can view all information about open-type services/products/events
* Can view all information about a SPP (service/product provider — company/agency/shop/organization)
* Can register

### **Authenticated User (AU):**

* Can search all open-type services/products/events
* Can view all information about open-type services/products/events
* Can view all information about a SPP
* Can view and edit their own profile
* Can view their own calendar with events they are attending
* Can communicate with Event Organizers (EO)

### **Event Organizer (EO):**

* Has an account and can log in to the system
* Can search all services/products
* Can view all information about services/products
* Can view all information about a SPP
* Can communicate with all application users
* Can make service reservations
* Can plan their own event (budget planning, create event agenda, guest list, etc.)
* Can mark favorite services/products

### **Service and Product Provider (SPP):**

* Can register their company/agency/shop/organization (SPP)
* Can manage SPP information (enter product/service categories, event types they support, location, description, contact info, etc.)
* Can register and manage employees
* Can manage their account and update their own information
* Can manage their services/products
* Can manage pricing for their services/products
* Can communicate with Event Organizers
* Can accept/reject service reservations
* Can report Event Organizers/comments/ratings


### **Administrator (Admin):**

* Manages service/product categories
* Manages event types
* Can review user reports (related to users, comments, and ratings)
* Can block reported users
* Can delete reported comments and ratings

