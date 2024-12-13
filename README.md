# College Event Photo Gallery

## Overview
This is a Django-based project designed to showcase pictures of college events. It uses MongoDB as the database, integrated directly through Django without requiring an external database setup.

## Features
- Displays event photos in an organized, user-friendly gallery.
- Easy to manage and extend through the Django admin interface.
- No external database setup is required — MongoDB runs seamlessly with Django.

## Installation

### Prerequisites
- Python 3.12 installed on your machine.
- MongoDB server installed and running locally (if needed).

### Clone the Repository
- Clone this repository to your local machine using:
```bash
git clone https://github.com/SubikshaMuralidass/Gallery.git
```
### Create a Virtual Environment
- Create a virtual environment and activate it:
```bash
python -m venv env
.\env\Scripts\activate
```
### Install Dependencies
- Install the required Python packages:
```bash
pip install -r requirements.txt
```
### Migrate Database
- Apply Django migrations to create the database schema:
```bash
python manage.py migrate
```
### Run the Development Server
- Start
```bash
python manage.py runserver
```
### Create a Superuser
- Create a superuser account to access the Django admin interface:
```bash
python manage.py createsuperuser
```

### Access the Gallery
- Open your web browser and navigate to http://localhost:8000/ to view the gallery.

### Access the Admin Interface
- To access the Django admin interface, navigate to http://localhost:8000/admin/ and log in with your superuser credentials.

## Usage
- To add or manage event photos, use the Django admin interface.
- Customize the gallery layout and styling by modifying the templates.

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Submit a pull request to the main repository.

## License
This project is licensed under the MIT License.


## Contact
For questions or feedback, please contact Subiksha Muralidass at subiksham88@gmail.com.



## Project Structure
```bash
Gallery_pics/
├── manage.py
├── Gallery_pics/                   
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   ├── wsgi.py
├── picture/
│   ├── migrations/
│   │   ├── __init__.py
│   │   ├── 0001_initial.py
│   ├── templates/
│   │   ├── event_detail.html 
│   │   ├── event_image.html
│   │   ├── gallery_grid.html
│   │   ├── Gallery.html     
│   ├── static/             
│   ├── views.py 
│   ├── __init__.py 
│   ├── urls.py
│   ├── tests.py        
│   ├── models.py           
│   ├── admin.py
│   ├── apps.py
├── requirements.txt
└── README.md
``` 