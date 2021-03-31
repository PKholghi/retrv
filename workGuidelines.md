Team Name: retrv
Team Members: Darren Moore, Pedrum Kholghi, Danyaal Ghafoor
 
Hours: 9-12 2-5 

Practices: pair programming, tdd (to be revised continuously)

Bank holiday: Fri 2nd & Mon 5th Half-day mornings, potential research day and catch up with other group

Generale rule: majority of work to be done together, only individual work if situation requires it or later in to 
project to add new features once all feel comfortable with working style. 

Ceremonies: 9am Morning stand-up & 5pm close off - What went well? What didn't work well? Is there any bottlenecks?

Software architecture: file: - routes.js file - RESTful api route response and requests
                             - main controller file: - class for each collection containing methods to work on that
                                                       collections route
                             - config file: - object that contains configurations settings as member variables:
                                        e.g.
                                            config.js
                                            const config = {
                                                            app: {
                                                                  port: 3000
                                                                 },
                                                            db: {
                                                                  host: 'localhost',
                                                                  port: 27017,
                                                                  name: 'db'
                                                                 }
                                                             };
                             - .env file: - Dotenv is a great Node library that enables the use of a .env file that can
                                            hold environment variables and feed them to your Node app. Keep secret key in
                                            .env and add .env to .gitignore

                      database: mongoDB
                      collections: users/
                                   users/:id/questions



StartingTasks: - generate user stories
               - discuss how to achieve user stories and break down in to tasks
               - create project backlog of tasks
               - task review
               - decide smallest feature to implement

MiniDeadLine1: Friday 12pm: - config.js, .env, main controller file (one class of REST methods for routes), routes
                              for each collection

Deadline: Thursday 8th April 12pm - 2pm
