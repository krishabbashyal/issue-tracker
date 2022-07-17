# issue-tracker

This project is an issue tracking application that can be used to communicate what needs to be done on a particular, or group of projects. Things like bugs, new features, technical updates, bumping versions are all tasks that can be represented as tickets. With these tickets you can create a new "workspace" for each including a chat where progress and blockers can be documented and discussed. These tickets can also be assigned to particular developers who have been added as "members" of the particular project, this way everyone is able to see what each other is working on.

Tickets can be divided into 6 main groups or sections:

To Do: This is the backlog, everything that needs to be done resides here. When tickets are created by anyone on the project's team they default to this category. From here anyone can go in and claim tickets and start working on them as they please.

In Progress: This section is for tickets which have been claimed and work has began. At this point a ticket can not be just claimed by anyone as someone has already claimed it and started working on it. In order to update the ticket holder a request must be sent to the current holder, similar to a friend request. When transfer is approved, then the ticket will reflect the new owner.

Developer Testing: After the developer thinks that the ticket has been properly implemented, at this point it is expected that the developer thoroughly tests their implemention and code. Ensuring that there are no new bugs or problems that have been introduced with the new code. For example: a new feature of removing from cart, does not break the previous feature implemention of adding to cart, both should work flawlessly.

Code Review: Once the developer has tested their application and everything looks good, they will submit some type of request to merge their new code with the existing codebase (Pull Request) at this stage of the ticket life cycle someone other than the developer will take a look at the new code and check its validity. If everything looks good then the ticket will move on to the next stage, otherwise it will go back to the "In Progress" section.

Live Testing: Unlike "Developer Testing", in this section the testing will be done by someone other than the developer on a live version of the application. This step is to make sure that the new code is working smoothly with the existing codebase and that everything is still running smoothly outside of the developers local environment. Testing in this section can be done by other developers, people from business or other fields, or the end customer.

Implemented / Complete: This section is where the tickets will do once they have been implemented and tested as working with the rest of the system. As your applicaiton rapidly expands this section could get cluttered. Which is why you will be able to set the "Sprint Length" upon completion of the "Sprint" the Implemented / Complete section of the board will clear and will be archived into another section that is not on the main board.
