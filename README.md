# Summary
Consider you are trying to build a backend server for an application that has the option of managing users. The system should be able to create users, edit and delete them.The user should have the following information
1. Name
2. Email
3. Role

*Only authenticated admins should be able to create new users.The system should be able to authenticate using an email and password. The authenticated users should have a role as admin. Only after authentication, all the CRUD rest apis should work. While creating the user there should be an additional option to upload a profile pic.  The api to view users should expose the profile pic. The system should provide a way to admin users* 

# End Points
Rest APIs have to be developed to support the mentioned tasks.
1. Creating the user
2. Updating the user.
3. Deleting the user
4. Viewing all the users
5. Login using email and password
* SuperAdmin api to add system users

# Process
* Please use NodeJS for the challenge.
* Please design the database as per what you feel is right. Usage of any SQL or NoSQL database is permitted.* Usage of a orm will be encouraged (but not mandatory).
* Test Cases are mandatory.
* Bonus points for adding Swagger information)
* Please upload the working copy of your code to GitHub and send us the link .
* Please state all your assumptions in the readme file of your GitHub repository.
* Implement a proper authentication mechanism with roles.
* File upload should be preferably handled using a cloud storage
