1. Fetch Team Members with Specific Roles
Task: Fetch the projects and then extract a list of all team members who have the role of "Developer" across all projects.

2. Calculate Total Hours Worked per Project
Task: Fetch the projects and for each project, calculate the total number of hours worked by all team members. Display each project’s title along with the total hours worked.

3. Update Task Status Based on Condition
Task: Fetch the tasks of a specific project (e.g., id: 1), then change the status of any in-progress tasks to completed and update the server with the new task status.

4. Calculate Total Budget for All Projects 
Task: Fetch all projects and calculate the total budget across all projects, then log the total sum.

5. Find the Most Worked-on Project
Task: Fetch all the projects and determine which project has the highest total number of hours worked across all its team members. Return an object containing the project's title and the total hours worked.

6. Aggregate Hours Worked per Role Across All Projects
Task: Fetch the projects and calculate the total hours worked by team members for each role (Developer, Designer, QA, etc.) across all projects. Return an object where the keys are the roles, and the values are the total hours worked for that role.


7. Calculate Average Task Completion Status (High Complexity)
Task: For each project, calculate the percentage of tasks that are marked as "completed". Create an object where the keys are project titles, and the values are the completion percentage (as a number between 0 and 100).