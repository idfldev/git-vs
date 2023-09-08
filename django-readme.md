### How to Upload Django project to GitHub

- __Sign in__ / __Create a new__ GitHub account.
- Create a new repository (___as the same Django project name___)
  - Public (_anyone  on the internet can see this repository. You can choose who can commit_).
  - Private (_You choose who can see and commit to this repository_).
  - Checked (_add a README file_).
  - Add .gitignone (_None_)
  - Choose a license (_None_)
  
---

### Tips in Django Projects

- Add __.env__ file on core project structure.
  - Project_root.
    - __.env__ file.
    - __setting__ python file.
  
  ```python
    # .env
    SECRET_KEY=django-insecure-8-isd-e).............(.........
  ```

  ```python
    # setting.py

    import environ

    # Initialise environment variables
    env = environ.Env()
    environ.Env.read_env()

    # SECURITY WARNING: keep the secret key used in production secret!
    SECRET_KEY = env('SECRET_KEY')
  ```

  - Create a __.gitignone__ file in the _project_root directory.
    - Add __.env__ on _.gitignone_ file.

  - Create a __requirements.txt__ file.

```python
pip freeze > requirements.txt
```






