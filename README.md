
# Project Title

This is a simple blog site made using Wagtail CMS.


Before setting up the project locally, please make sure you have Python3.6+ installed and running on your machine.


    
## Run Locally

Clone the project and change directory into it

```bash
  git clone git@github.com:nickmwangemi/wagtail-blog-2.git
  cd wagtail-blog-2
```

Create virtual environment and activate it

```bash
  python3 -m venv .venv
  source .venv/bin/activate
```


Go to the project directory

```bash
  cd wagtail-blog-2/mysite
```


Install dependencies

```bash
  pip install -r requirements.txt
```

Create the database

```bash
  python manage.py migrate
```

Create superuser account

```bash
  python manage.py createsuperuser
```

Start the server

```bash
  python manage.py runserver
```

  
## Tech Stack

**Client/Server:** [Wagtail CMS](https://wagtail.io/)
  
## License
[MIT](/LICENSE)


  
## Demo

Insert gif or link to demo

  