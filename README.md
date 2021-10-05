# A Flask Todo  App

## installing, run
    pip install pipenv 
    pipenv shell
    pipenv install Flask
    pipenv install Flask-SQLAlchemy
    pipenv install SQLAlchemy


## after cloning the code, and installing the neccessary files run in your terminal:
    python
    from app import db
    db.create_all()
    exit()

### it consists of:
    home route (where the completed and uncompleted todos are displayed)
    add route(to add todos)
    complete(to mark a todo if it is completed)
