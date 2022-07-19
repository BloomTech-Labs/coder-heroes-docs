## CoderHeros registration details (BL-467)

*This epic focused on bringing the core feature of registration for classes to production*

### UX: Iterate design artifacts to include class registration (BL-473 In Progress)

_Assignee: Lauren Ruiz_
_Co-owner: Anthony Layne_

    - Iterate the Figma design artifacts for this product
     - Designs for this flow should be complete, or close to complete. 
     - We may need some registration updates to the mockups with a simplified version of existing designs, where a parent can see more about courses they are interested in.


### FE: I want to be able to add courses (BL-474 In Progress)

_Assignee: Lauren Ruiz_ 
_Co-owner: Anthony Layne_ 

    - Admins should be able to add courses, so that parents can find the courses when they are searching
    - Use designs from BL-473 for this feature 
    - Update Admin component to include a button to add at the top, and a list of courses that are available
    - They would be able to add all of the necessary details that need to be shown to a parent when searching for courses


### FE: I want to be able to search for available courses (BL-476 In Progress)

_Assignee: Irving Delgado_ 
_Co-owner: David Shipuk_

    - Parents should be able to explore programs for their children, search available courses, and learn about available options
    - Use designs from BL-473 for this feature
    - Flow should start from booking view


### FE: I want to be able to filter options based on my needs (BL-477 In Progress)

_Assignee: David Shipuk_ 
_Co-owner: Irving Delgado_

    - Parents should be able to filter course options, so that they are presented only with courses that are relevant to their interests
    - Use designs from BL-473 for this feature
    - Flow should start from booking view 


### FE: I want to be able to pay for the course (BL-478 Ready for Work)

_Assignee - Unassigned_ 
_Co-owner - Unassigned_ 

    - Parents should be able to purchase a course, so that they can officially sign their child up for the class
    - Use designs from BL-473 for this feature


### Write and implement unit tests for registration features (BL-481 In Progress)

_Assignee - Kevin Lee_
_Co-owner - Danny Chui_

    - Implement a minimum of 3 tests to verify the case data is the expected shape and in the proper format


 
### FE: I want to see class details (BL-518 In Progress)

_Assignee - Lauren Ruiz_ 
_Co-owner - Anthony Layne_ 

    - Parents should be able to learn more about a course, so that they can know if it would be the right choice to register for
    - Use designs from BL-473 for this feature
    - Incorporate 'drill down' component that displays full details of a specific course being viewed
    - Get more information from stakeholder regarding course details 


 ### BE: Assess backend needs for the Register for Class feature (BL-519 Done)

_Assignee - David Shipuk_ 
_Co-owner - Irving Delgado_

    - Analyze existing code and make a list of what is already available and what remains to be built
    - Already have:
        1. routes to enroll a child to the said course that includes middleware for authentication, child exists, and child is enrolled
        2. children model to add a child to the enrolled course and retrieve courses child is in
    - Still need:
        1. Middleware to check age is between course constraints
        2. Middleware to check if a course exists for addEnrolledCourse and getEnrolledCourses
        3. Middleware to check if a course is full


### BE: Create middleware for course registration (BL-562 Ready for Work)

_Assignee - Unassigned_
_Co-owner - Unassigned_ 

    - Create middleware that covers the three cases as pointed out in the previous discovery ticket (BL-519)
