# issue-tracker

### This project is an issue tracking application that can be used to communicate what needs to be done on a particular, or group of projects. Things like bugs, new features, technical updates, bumping versions are all tasks that can be represented as tickets. With these tickets you can create a new "workspace" for each including a chat where progress and blockers can be documented and discussed. These tickets can also be assigned to particular developers who have been added as "members" of the particular project, this way everyone is able to see what each other is working on

## Projects can be created by anyone and other developers and be added as you wish

- **Group Creator**: This person will have the "Admin" role of the project, including the ability to oversee all of the tickets and alter the group by renaming, adding and removing members, setting the group image, setting the sprint length, creating and removing ticket lables. The Admin can also give these permissions to others, but only one "Admin" can exist in a project. The "Admin" is the only person who can delete the group.

- **Projects**: Once a project has been created, it will be empty initally. From there you can begin to create tickets, or add other memebers to the project via an invite request. This functions will work similar to a friend request in which the request has to be accepted by the other person before being added to your project. At this point it is unclear if subprojects can exist within a project, other workarounds may be explored such as grouping or color-coating on the client side.

## Tickets can be divided into 6 main groups or sections by default, but these can be changed by the project "Admin"

- **To Do**: This is the backlog, everything that needs to be done resides here. When tickets are created by anyone on the project's team they default to this category. From here anyone can go in and claim tickets and start working on them as they please.

- **In Progress**: This section is for tickets which have been claimed and work has began. At this point a ticket can not be just claimed by anyone as someone has already claimed it and started working on it. In order to update the ticket holder a request must be sent to the current holder, similar to a friend request. When transfer is approved, then the ticket will reflect the new owner.

- **Developer Testing**: After the developer thinks that the ticket has been properly implemented, at this point it is expected that the developer thoroughly tests their implemention and code. Ensuring that there are no new bugs or problems that have been introduced with the new code. For example: a new feature of removing from cart, does not break the previous feature implemention of adding to cart, both should work flawlessly.

- **Code Review**: Once the developer has tested their application and everything looks good, they will submit some type of request to merge their new code with the existing codebase (Pull Request) at this stage of the ticket life cycle someone other than the developer will take a look at the new code and check its validity. If everything looks good then the ticket will move on to the next stage, otherwise it will go back to the "In Progress" section.

- **Live Testing**: Unlike "Developer Testing", in this section the testing will be done by someone other than the developer on a live version of the application. This step is to make sure that the new code is working smoothly with the existing codebase and that everything is still running smoothly outside of the developers local environment. Testing in this section can be done by other developers, people from business or other fields, or the end customer.

- **Implemented / Complete**: This section is where the tickets will do once they have been implemented and tested as working with the rest of the system. As your applicaiton rapidly expands this section could get cluttered. Which is why you will be able to set the "Sprint Length" upon completion of the "Sprint" the Implemented / Complete section of the board will clear and will be archived into another section that is not on the main board.

## Current Technical Stack (Subject to Change):

- **Node.js (v16.14.2)**: Our runtime for JavaScript so we will be able to run it outside of the browser, we are using v16.14.2 but any recent version should be fine.
- 
- **Express.js**: Our backend minimalist framework for the API, everything must be done from scratch meaning that it will provide a good learning experience.
- 
- **React.js**: Our frontend portion of the application, we will use functional components to create the application, good marketability for job market.
- 
- **PostgreSQL**: Database that we will use, no reason for this other than having no experince with anything else. Want to dive into relational DBs before looking into MongoDB.
- 
- **Git/GitHub**: Used for version control and online repository, this way we can keep track of our project and have it online if we need it on the go.
