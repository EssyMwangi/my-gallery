# Tourism Hub 
## Author  
  
>[EssyMwangi](https://github.com/EssyMwangi/my-gallery)  
  
# Description  
This is a Django application for personal gallery that allows a user to upload images for other to see and be able to to share by coping the image link.
  
##  Live Link  
 Click [View Site](https://travel-gallerybyess.herokuapp.com/)  to visit the site
  
## Screenshots 
###### Home page
 
<img src="https://user-images.githubusercontent.com/44394821/82762995-fd054a80-9e0c-11ea-86c7-24f5b4dbc14c.png">
 
 ###### Image Details 
 <img src="https://user-images.githubusercontent.com/44394821/82762996-fecf0e00-9e0c-11ea-9323-052eace2cbe6.png">
 
## User Story  
  
* View different photos that interest them  
* Click a single image to expand it and view the details of that photo  
* Search for different categories   
* Copy a link to the photo to share with my friends.  
* View photos based on the location they were taken.  
  

  
## Setup and Installation  
To get the project .......  
  
##### Cloning the repository:  
 ```bash 
https://github.com/EssyMwangi/my-gallery.git 
```
##### Navigate into the folder and install requirements  
 ```bash 
cd my-gallery pip install -r requirements.txt 
```
##### Install and activate Virtual  
 ```bash 
- python3 -m venv virtual - source virtual/bin/activate  
```  
##### Install Dependencies  
 ```bash 
 pip install -r requirements.txt 
```  
 ##### Setup Database  
  SetUp your database User,Password, Host then make migrate  
 ```bash 
python manage.py makemigrations mygallery 
 ``` 
 Now Migrate  
 ```bash 
 python manage.py migrate 
```
##### Run the application  
 ```bash 
 python manage.py runserver 
``` 
##### Running the application  
 ```bash 
 python manage.py server 
```
##### Testing the application  
 ```bash 
 python manage.py test 
```
Open the application on your browser `127.0.0.1:8000`.  
  
  
## Technology used  
  
* [Python3.7](https://www.python.org/)  
* [Django 1.11.17](https://docs.djangoproject.com/en/2.2/)  
* [Heroku](https://heroku.com)  
  
  
## Known Bugs  
* There are no known bugs currently but pull requests are allowed incase you spot a bug  
  
## Contact Information   
If you have any question or contributions, please email me at [sonnieessy@gmail.com]  
  
## License:
- _MIT License:_[LICENSE MIT](./license)

- Copyright (c) 2020 **Essy Mwangi**
