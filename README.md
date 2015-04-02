# ProjectRepo

## To run

setup environment first then

```
./run.py
```
navigate to [localhost:5000](http://localhost:5000)

# Setup Environment
install mongodb
```
sudo apt-get install mongodb
```

create a virtual environment and install python packages
```
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
```

you can now start editing


# Pushing Rules


make sure that all requirements of the project are in requirements.txt

```
source venv/bin/activate
pip freeze > requirements.txt
```
make sure that all package documentation is linked in the documentation section bellow

if you installed tools that are required to run the server add them to the readme under setup environment


add anyfiles that you many have created

```
git add --all
```

# Templates

All HTML is generated by the server and the templates are stored in the application/templates

Static files such as images, css, and javascript go into the application/static/imgs, application/static/css and application/static/js respectively

# Various documentation

Flask documentation : [http://flask.pocoo.org/docs/0.10/](http://flask.pocoo.org/docs/0.10/)

Flask-mongoengine documentation : [http://docs.mongoengine.org/](http://docs.mongoengine.org/)

# Bugs

If you happen to find a bug report it AND THEN attempt to fix it, if you cannot indicate that in the bug report

The issue tracker is [here](https://github.com/BaySchoolCS2/ProjectRepo/issues/new)
