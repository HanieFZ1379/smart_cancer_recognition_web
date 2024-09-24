python3 -m venv venv
touch requirements.txt
source venv/bin/activate
python --version
Python 3.8.10
pip install -r requirements.txt
touch app.py
mkdir templates
touch templates/base.html
touch templates/home.html
touch templates/input.html
touch templates/login.html
touch templates/register.html
touch templates/result.html
touch templates/history.html
mkdir static
mkdir static/css
mkdir static/js
touch models.py
touch README.md
------------------------------------------------------
smart_website_project/
│
├── app.py  # Main Flask application
├── models.py  # models for cancer recognition
├── templates/  # HTML templates
│   ├── home.html
│   ├── login.html
│   ├── register.html
│   ├── input.html
│   ├── result.html
│   ├── history.html
├── static/  # Static files (CSS, JS, images, etc.)
│   ├── css/
│   └── js/
├── venv/  # Virtual environment
└── requirements.txt  # Project dependencies