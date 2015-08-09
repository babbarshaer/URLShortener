# Shortly.ly
Let's shorten the world. Shortly is a url shortening service.


# Execution Steps

1. Install `virtualenv` and `Flask` for the project. Steps for installing it and provided in the [link](http://flask.pocoo.org/docs/0.10/installation/).
2. Create a virtual environment by executing `virtualenv venv` in the project root.
3. Activate the profile `source venv/bin/activate`.
4. Install Flask and Dependencies provided in the requirements folder. `pip install -r requirements.txt --allow-all-external`
5. Make **server.py** file executable by changing permission. 
6. Execute `./server.py`
7. Open link *http://localhost:5000/* on your browser.
8. Enjoy **shortly.ly**.


# Test Execution Steps

1. Go to the root folder of the project.
2. Execute the command `python -m unittest discover test/ *_test.py` to run tests.

