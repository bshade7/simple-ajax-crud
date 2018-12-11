# Simple Ajax Crud

Example used in the blog post [How to Implement CRUD Using Ajax and Json](https://simpleisbetterthancomplex.com/tutorial/2016/11/15/how-to-implement-a-crud-using-ajax-and-json.html)

## Running Locally
Clone the git repository.
```bash
git clone https://github.com/bshade7/simple-ajax-crud.git
```

Install pipenv package for virtualenvironment and dependency management.
```bash
pip install pipenv
```

Move into cloned project directory.
```bash
cd simple-ajax-crud
```

Create virtual environment in the local directory.
```bash
pipenv install
```

Activate your new virtual environment
```bash
pipenv shell
```

Migrate the database changes required.
```bash
python manage.py migrate
```

Run the development web server.
```bash
python manage.py runserver
```
