-------process-------
1) Activate virtual environment
    $venv\scripts\activate
2) Install the following requirements if not installed 
    django - 3.0.5
    pillow - 7.1.2
    six - 1.14.0
    django-crispy-forms - 1.9.0
    django-bootstrap-modal-forms - 1.5.0

3) Run the following command to start webpage
    python manage.py runserver

4) To register user has to enter his credentials:
    1) username
    2) password
    3) email
    4) group
    5) institute
5) User has to confirm his email by activating the link sent  to his email and Login


-----Functionalities implemented---------
{
    Login
    Logout
    Register with mail confirmation
    User gets added into the group opted while registration automatically
    Send posts in the group added
    Comment on the posts in the respective groups
    Connect with people by seding requests
    Send and receive messages(Message reloading periodically for every 5 secs)
    Notifications when one sends request or message
    View profile and connections of other user in same group(dynamic url + messages)
    Edit ones profile
    Send request to the admin to create a new group
}

-------Further improvements-----
{
    Notifications redirecting to the required page
    User to have option to join multiple groups
}