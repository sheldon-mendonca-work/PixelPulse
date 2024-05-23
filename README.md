What I want this project to be:

Front-end:
1. Will be built with Angular
2. Will be mobile compatible
3. Will have levels for:
    a. unvisited
    b. customer
    c. Store
    d. Admin
    e. SuperAdmin(me only)
4. lazy loading will be used
5. Front end logging and failure reporting will be done
6. Cookies will be used for tracking
7. Tailwind will be used for CSS. Not using it for inherited CSS and animations.

Backend:
1. Will be built with Springboot
2. Will support all of the above
3. Will have campaign code
4. Will have a payment gateway for multiple sources. Should be able to switch from one provider to another.
5. Access for each of these users will be limited
6. Will use logging at backend

Database:
1. MySql will be used for persistence
2. Redis will be used for in-mem

SDLC:
1. Github will be used for code management
2. master branch will be used for deployment
3. beta branch will be used for testing
4. jira will be used for ticket creation and tracking.
5. Documentation will be written from the POV of super admin. All other documentation is subset of super admin.