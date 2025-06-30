# OnlineCourse App Setup Instructions

## Step 1: Install Required Packages

Open your terminal and run the following commands to install the necessary packages:

```bash
pip install --upgrade distro-info
pip3 install --upgrade pip==23.2.1
pip install virtualenv
virtualenv djangoenv
source djangoenv/bin/activate
pip install -U -r requirements.txt
```

## Step 2: Activate Models for the OnlineCourse App
Perform Migrations
Run the following command to create the necessary database tables:
```bash
python3 manage.py makemigrations
python3 manage.py migrate
```

## Step 3: Test the OnlineCourse App
Start the development server using the following command on defailt port 8000:
```bash
python3 manage.py runserver
```

