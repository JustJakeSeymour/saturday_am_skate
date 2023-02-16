# README

# Saturday Morning Skate
### (A monolithic rails site to communicate to regular skaters)

# Goals

- Use Rails CRUD functions for users and skate days.
- Use authorization and session techniques for different features.
- Implement mailing once learned.

# User Stories

### Part 1: User Registration and Features
```
User Story 1 - User Registration
As a visitor
When I visit the root_path
I see a button to register as a user or to log in 
```

```
User Story 2 - User Dashboard
As a registered user
When I log in and visit my dashboard
I have the ability to RSVP for the next week's skate
if I am already RSVP'd I see the ability to drop my reservation
```

### Part 2: Admin Features
```
User Story 3 - Admin Approval
As the admin
when I visit my dashboard
I see every user that has RSVP'd to skate
I am able to assign each skater to team Light or team Dark
```

### Part 3: Organizer Communication
```
User Story 4 - Broadcast Information
As the admin
I can send a message to the users who are registered to skate that week
As a skating user
I will recieve a message with information of the skate and my assigned team
```