## BL-467 - CoderHeros registration details 

*This epic focused on bringing the core feature of registration for classes to production*

- [BL-473](#bl-473---ux-iterate-design-artifacts-to-include-class-registration) - UX: Iterate design artifacts to include class registration
- [BL-474](#bl-474---fe-i-want-to-be-able-to-add-courses) - FE: I want to be able to add courses 
- [BL-476](#bl-476---fe-i-want-to-be-able-to-search-for-available-courses) - FE: I want to be able to search for available courses 
- [BL-477](#bl-477---fe-i-want-to-be-able-to-filter-options-based-on-my-needs) - FE: I want to be able to filter options based on my needs
- [BL-478](#bl-478---fe-i-want-to-be-able-to-pay-for-the-course) - FE: I want to be able to pay for the course
- [BL-481](#bl-481---write-and-implement-unit-tests-for-registration-features) - Write and implement unit tests for registration features  
- [BL-518](#bl-518---fe-i-want-to-see-class-details) - FE: I want to see class details
- [BL-519](#bl-519---be-assess-backend-needs-for-the-register-for-class-feature) - BE: Assess backend needs for the Register for Class feature
- [BL-562](#bl-562---be-create-middleware-for-course-registration) - BE: Create middleware for course registration 




### BL-473 - UX: Iterate design artifacts to include class registration 

_Assignee: Lauren Ruiz_
_Co-owner: Anthony Layne_

    - Iterate the Figma design artifacts for this product
    - Designs for this flow should be complete, or close to complete
    - We may need some registration updates to the mockups with a simplified version of existing designs, where a parent can see more about courses they are interested in


### BL-474 - FE: I want to be able to add courses 

_Assignee: Lauren Ruiz_ 
_Co-owner: Anthony Layne_ 

    - Admins should be able to add courses, so that parents can find the courses when they are searching
    - Use designs from BL-473 for this feature 
    - Update Admin component to include a button to add at the top, and a list of courses that are available
    - They would be able to add all of the necessary details that need to be shown to a parent when searching for courses


### BL-476 - FE: I want to be able to search for available courses 

_Assignee: Irving Delgado_ 
_Co-owner: David Shipuk_

    - Parents should be able to explore programs for their children, search available courses, and learn about available options
    - Use designs from BL-473 for this feature
    - Flow should start from booking view


### BL-477 - FE: I want to be able to filter options based on my needs 

_Assignee: David Shipuk_ 
_Co-owner: Irving Delgado_

    - Parents should be able to filter course options, so that they are presented only with courses that are relevant to their interests
    - Use designs from BL-473 for this feature
    - Flow should start from booking view 


### BL-478 - FE: I want to be able to pay for the course 

_Assignee - Unassigned_ 
_Co-owner - Unassigned_ 

    - Parents should be able to purchase a course, so that they can officially sign their child up for the class
    - Use designs from BL-473 for this feature


### BL-481 - Write and implement unit tests for registration features 

_Assignee - Kevin Lee_
_Co-owner - Danny Chui_

    - Implement a minimum of 3 tests to verify the case data is the expected shape and in the proper format


 
### BL-518 - FE: I want to see class details 

_Assignee - Lauren Ruiz_ 
_Co-owner - Anthony Layne_ 

    - Parents should be able to learn more about a course, so that they can know if it would be the right choice to register for
    - Use designs from BL-473 for this feature
    - Incorporate 'drill down' component that displays full details of a specific course being viewed
    - Get more information from stakeholder regarding course details 


 ### BL-519 - BE: Assess backend needs for the Register for Class feature 

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


### BL-562 - BE: Create middleware for course registration 

_Assignee - Unassigned_
_Co-owner - Unassigned_ 

    - Create middleware that covers the three cases as pointed out in the previous discovery ticket (BL-519)
