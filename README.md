# ws_two_window_chat
Test of django channels two window chat

No support for non mac os is currently explored.

Before running preform the following:
    1. "brew install redis"  (I use hmebrew as a package manager)
    2. create and activate a virtual environment in the top level of the project
    3. "pip install requirements.txt"
    4. from the src folder: "python3 manage.py makemigrations"
    5. from the src folder: "python3 manage.py migrate"
    6. from the src folder: "python3 manage.py runserver"
    7. go to the server localhost at the /chat extension
    8. enter any name into the desired chat room and submit
    9. make a seperate window incognito (if google chrome) and past the url from the previous window in
    10. you should be able to submit messages in each window that will display on both
