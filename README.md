# learning-django

## To install Django

First install a virtual environment which makes easier to work with different versions and will not mess up the existing version, if any.

To install virtual env copy the command to your cmd
- py -m pip install virtualenvwrapper-win

Now create a virtual environment
- mkvirtualenv myproject

To switch to your virtual environment
- workon myproject

Finally install Django using the command
- py -m pip install Django

To verify that Django can be seen by Python, type ``python`` from your shell.
  Then at the Python prompt, try to import Django:

    >>> import django
    >>> print(django.get_version())
    |version|

Alternatively you can also check the version using the command
- django-admin --version

## Reasons to learn Django

1. Django is fast and realiable
2. Lots of components are already built in. 
3. Secure
4. Flexible and Scalable

## Start the first project

Open command prompt and switch to your virtual enviroment.

Make an empty directory `mkdir projects`.

Switch to that directory `cd projects`.

Create a baic Django starter app using `django-admin startproject basicapp`.



