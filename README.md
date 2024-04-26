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

   1. to install dependencies for react run this command : npm install
   2. run the program : npm start


3.Remember to run both frontend and backend to see the result
4.  Due to 1 day deadline I couldnot complete the whole project you can do CRUD from  Database admin from here :
   * http://127.0.0.1:8000/admin
   * You can add all the content from here and can perform CRUD operation.
   * you can get these data on frontend.

These are the screen shot:
Add, Update Delete data from Backend:
1. <img width="800" alt="Screenshot 2024-04-26 at 12 56 43 PM" src="https://github.com/dipennapit123/Django-React-blogapp/assets/114264588/641ff4b8-1b2e-478f-857e-2e3105ed72c5"> 
2. <img width="800" alt="Screenshot 2024-04-26 at 12 56 51 PM" src="https://github.com/dipennapit123/Django-React-blogapp/assets/114264588/fd702e64-ff3f-40b1-b9be-42f52a7a4fdf">

Frontend screenshot:
1.  <img width="800" alt="Screenshot 2024-04-26 at 1 00 40 PM" src="https://github.com/dipennapit123/Django-React-blogapp/assets/114264588/1097325d-df9c-4eb5-a366-241dc5178e0d"> 
2.  <img width="800" alt="Screenshot 2024-04-26 at 1 00 34 PM" src="https://github.com/dipennapit123/Django-React-blogapp/assets/114264588/f31386af-ec21-43f8-ab2d-b2f417858550"> 

3.<img width="800" alt="Screenshot 2024-04-26 at 1 00 14 PM" src="https://github.com/dipennapit123/Django-React-blogapp/assets/114264588/41aae40b-bbb5-4444-ba16-40eb918080a3"> 
4. <img width="1423" alt="Screenshot 2024-04-26 at 1 00 25 PM" src="https://github.com/dipennapit123/Django-React-blogapp/assets/114264588/05eef3cf-8c56-46d9-9bf9-b68ce4d77406"> 








