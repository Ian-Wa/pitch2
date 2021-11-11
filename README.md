# Ian Pitches
## Author
[Ian Wanjira]( https://github.com/Ian-Wa)

# Description
This is a flask application where user can create pitches and view other people's pitches once logged in. Users can also comment on other people's pitches.

## Installation Instruction
1. Cloning the repository:
  ```bash
  https://github.com/Ian-Wa/pitch2.git
  ```

2. Move to the folder and install requirements
  ```bash
  cd pitch2
  pip install -r requirements.txt
  ```
3. Exporting Configurations
  ```bash
  export SQLALCHEMY_DATABASE_URI=postgresql+psycopg2://{User Name}:{password}@localhost/{database name}
  ```
4. Running the application
  ```bash
  python3.8 manage.py server
  ```
5. Testing the application
  ```bash
  python3.8 manage.py test
  ```
Open the application on your browser `127.0.0.1:5000`.

## Technology used

* [Python3.8](https://www.python.org/)
* [Flask](http://flask.pocoo.org/)
* [Heroku](https://heroku.com)