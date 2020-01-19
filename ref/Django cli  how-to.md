# Django Project Reference

#### Create env from directory main folder ref: https://docs.python.org/3/library/venv.html <br>
* <code>python3 -m venv ./venv</code>

#### Activate enviroment (mac version)
* <code>source ./venv/bin/activate</code>

#### Deactivate enviroment
* <code>deactivate</code>

### Django cli start projecct - to create new django project
* <code>django-admin startproject btre . </code>

### Initialize local git repo
* <code>git init </code> 

### Create .gitignore file using website: http://www.gitignore.io/
#### Note: Add the venv file to the gitignore

#### Git add all files and commit to current branch
* <code>git add . && git commit -m 'message'</code>

### Git create branch
* <code>git checkout -b 'name' </code>

### Git push branch to master and switch to branch
* <code> git push --set-upstream origin branch_name </code>

### Run manage.py run server command
* <code>python manage.py runserver </code>

### Create Django App
* <code>python manage.py startapp <name_of_app></code>

### Collect static file command 
* <code> python manage.py collectstatic</code>

