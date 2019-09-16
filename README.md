# flask_admin_skeleton
This app shows the basic usage of Flask framework. It allows creation and deletion of users.   
A user can self register but will require and approval from administrator before the user can have access to database entries.

Once the user has access, (s)he can create a post and enter expenses. This functionality demonstrates the usage of `wtforms`.
More specifically, usage of dropdown and display of date field and checkboxes.

Further activities to explore:
* Create a grid editable form
* Creation of subforms
* Creation of forms in modals

# How To?

1. Clone this repository on your desktop in the python virtual environment.
2. Go to the directory `approot` on terminal / commandline and give the command `python run.py`
3. Install any missing dependencies.
4. Once the run.py has worked, press `Ctrl+C` to stop the server.
5. Then type python and in the python interpreter initiate database using the `create_admin_user.py`
6. Now start the app by typing `python run.py`
7. In your browser type: http://localhost:5000/ and register a user with your own username and password.
8. Login using the username `admin@admin.com` and password `adminpassword`
9. Go to "Registered Users" link and update the user role to `Admin`.
10. Logout and login with user you created in Step 7.
11. Go to Registered users and delete the default admin user you created.
12. Explore further!!!
