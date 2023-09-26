To run the app:

"flask run" (This only runs on local host, to make it run on all IPs, bind to gunicorn)

To bind it to gunicorn:

"gunicorn app:app -c gunicorn.py"

To run the tests:

"python3 -m pytest"

