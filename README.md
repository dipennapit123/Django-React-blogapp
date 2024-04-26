#Read this Before the installation
1. run thi command : git clone https://github.com/dipennapit123/Django-React-blogapp.git
2. run these commands for backend :
   1. cd Backend
   2. create virtual environment :
      * for mac/linux : python -m venv venv
      * activate virtual env : source myvenv/bin/activate
3. Instll these dependencies to run backend:
   1. pip install django
   2. pip install djangorestframework
   3. pip install django-cloudinary-storage
   4. pip install django-cors-headers
   5. pip install djangorestframework-simplejwt
   6. pip install pillow
   7. python manage.py migrate
4. Create superuser to have access on database.
   * python mange.py createsuperuser
   * register username and password
   * then runserver : python manage.py runserver
5. -------------- FrontEnd------------------
6.run this sommand: cd ..
7. run this command for frontend directory:
   * cd Frontend
   * cd blog

   1. to install dependencies for reacu run this command : npm install
   2. run the program : npm start


3.Remember to run both frontend and backend to see the result
4.  Due to 1 day deadline I couldnot complete the whole project you can do CRUD from  Database admin from here :
   * http://127.0.0.1:8000/admin
   * You can add all the content from here and can perform CRUD operation.
   * you can get these data on frontend.
     
