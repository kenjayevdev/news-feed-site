# 🗞 NEWS FEED SITE

🛠The following technologies were used in this project: HTML5, CSS3, Bootstrap, JavaScript, Python, Django, Django REST framework, Sqlite3


🔹What's on the site:
- Add news
- Edit news
- Delete news
🧑🏻‍💻Only admins can do these three actions.

- User registration (SignUp)
- User login to the site with an opened account (LogIn)
- User logout (LogOut)
- User account editing (Edit profile)
- User password change (password change)

- Write a comment (comment)
- Search for news (search)
- View news sorted by category
- View the time the news was added

## Setup

- run `git clone https://github.com/kenjayevdev/news-feed-site.git` copy repositories
- run `cd news-feed-site` accessing repositories
- run `python -m venv env` to create virtual environment
- run `env\Scripts\activate` to activate the env
- run `pip install -r requirements.txt` to install all required packages
- Create a .env file and set your SECRET_KEY and DEBUG=True in the file
- run `python manage.py makemigrations`
- run `python manage.py migrate`
- run `python manage.py runserver`
