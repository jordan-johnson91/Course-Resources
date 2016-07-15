# Weekend Study

- Review List and Dictionary Data Structures
- Complete all challenges from the slides
  - Complete all exercises (List Slides)
  - Come up with ideas for Slide 8 & 19 (Dictionary Slides)
  - Complete exercises on slides 20-23 (Dictionary Slides)

- Optional Project for Practice (Project Description Below)

# Student Resources Checkout System
## Due: N/A

## Overview
Develop the first iteration of the Bootcamp Resources Checkout System as a console application. The Bootcamp Resources Checkout System should allow current WCCI Bootcamp students to checkout WCCI books from the bookshelf and check-in materials when returned. The current product specifications are as follows:

[Example](https://drive.google.com/file/d/0B5A2Jb7LrKtqdURuc0QyazZmeGc/view)

## Tasks

- [ ] Application should be clearly named in the application (Bootcamp Resources Checkout System or an original name)
- [ ] Program should be case insensitive
- [ ] Application should have a menu with the following options:
  - [ ] View Students
  - [ ] View Available Resources
  - [ ] View Student Accounts
  - [ ] Checkout Item
  - [ ] Return Item
  - [ ] Exit
- [ ] View Students
  - [ ] Print a vertical list of all of the students in the system (minimum 5 students)
  - [ ] Names should be alphabetized (by either first or last name)
  - [ ] Menu should be available to navigate to another option
- [ ] View Available Resources
  - [ ] Print vertical list of only the resources that are available (not checked out)
  - [ ] List should be alphabetized
  - [ ] If no items are checked out, there should be a minimum of 10 resources
  - [ ] Menu should be available to navigate to another option
  - [ ] If all resources are checked out, print “All resources are checked out.”
- [ ] View Student Accounts
  - [ ] Ask for a student’s name
  - [ ] If the student’s name does not exist, print “Error: Request Unavailable”
  - [ ] If the student has 0  items checked out, print “Nothing is checked out…”
  - [ ] If items are checked out, print a vertical list of those items
  - [ ] After printing the student’s account, menu should be available to navigate to another option
- [ ] Checkout Item
  - [ ] Ask for a student’s name
  - [ ] If the student’s name does not exist, print “Error: Request unavailable”
  - [ ] Ask for the title of the item
  - [ ] If the title does not exist in the available resources, print “Error: Request Unavailable”
  - [ ] If the item is available, print “[Student Name] checked out [Title]."
  - [ ] Each student can only have 3 items checked out at one time
  - [ ] If a student has 3 items already checked out, when the student’s name is entered on the checkout screen, print “[Student Name] has checked out the max number of resources.”
- [ ] Return Item
  - [ ] Ask for a student’s name
  - [ ] If the student’s name does not exist, print “Error: Request Unavailable”
  - [ ] Ask for the title of the resource to be returned
  - [ ] If the title exists in the student’s account, remove the the title from the student’s account
  - [ ] Add the returned title back to the available resources list
  - [ ] If the title does not exist in the student’s account, print “Error: Request Unavailable”
  - [ ] Menu should be available to navigate to another option
- [ ] Exit
  - [ ] The program should not exit until told to by the user
  - [ ] Before exiting, print an exit message, such as “Goodbye”	


