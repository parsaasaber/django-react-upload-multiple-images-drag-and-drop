# Introduction:
If you're wondering how to use React & Django to create a media fileuploader, you're in the right place. Also you can upload multi images at the time using multi select or adding them one by one. After hitting the save button, information will be sent to the database.

## Installation:

### Backend Setup

1. Clone Repository: 
```
git clone https://github.com/parsaasaber/django-react-upload-multiple-images-drag-and-drop.git


cd django-react-upload-multiple-images-drag-and-drop
```

2. Create a virtual environment and activate it:
```
python -m venv .venv
source .venv/bin/activate  # On Windows use `.\.venv\Scripts\activate`
```

3. Install the required Python packages:
```
pip install -r req.txt
```

4. Run the Django migrations:
```
python manage.py migrate
```

### Frontend

1. Open a new terminal in command line and navigate to `frontend` directory:
```
cd frontend
```

2. Install the required npm packages:
```
npm install
```

### Run the project:
1. Navigate to `Backend` directory and run the project:
```
python manage.py runserver
```
2. In the other terminal, navigate to the `frontend` directory and start the application:
```
npm start
```