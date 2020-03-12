# Django-personal-website

My Django-based personal website adapted from here: https://github.com/vladislavalerievich/Django-personal-website

# Changes from OG and resources:
Updated Django version to 2.0.13 in requirements.txt

Configuring email settings: https://medium.com/@_christopher/how-to-send-emails-with-python-django-through-google-smtp-server-for-free-22ea6ea0fb8e

Changed secret key in portfolio/settings.py: https://stackoverflow.com/questions/15170637/effects-of-changing-djangos-secret-key

Emailing with Django: https://blog.mailtrap.io/django-send-email/
	○ Changed email settings for my email
	○ Researched email config and how to use
	○ Researched forms and cleaned_data

Needed to create .gitignore
		*.pyc
    *~
    /.vscode
    __pycache__
    myvenv
    db.sqlite3
    /static
    .DS_Store

