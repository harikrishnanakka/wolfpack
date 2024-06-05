# Wolf Pack JWT Authentication


1.It is a project related to the JWT(JSON WEB TOKEN AUTHENTICATION).


2.We have to create the LOGIN endpoint aswellas the register Endpoint.


3.IN register endpoint user should able to give the email,first_name,last_name,password.


4.While in the login endpoint user have to authenticate with the email and password beacause it is a email based authentication.


5.Therefore we can get the access key for the JWT or JWT token.


# FIRSTLY RUN THE SERVER


1.Firstly we have to activate the virtualenvironment in that all the neccessary pakages have been installed so no need to install the packaged again


2.TO activate the virtual environment use the command:


      cd wolfpack_project/myenv/scripts

      
       activate.bat


3.After completion of the activating the virtual environment run the development server by using the belo command:


       python manage.py runserver


4.Therefore development server will run you can now follow the below steps:


# How to use it:

1.Firstly we need to register the user by using the endpoint like:


      http://localhost:8000/api/register/


a.Json data should be given:

          {

          "email":"krishna123@gmail.com",

          "first_name":"krishna",

           "last_name":"jager",

            "password":"krishna123"

             }


2.In my case i used the POSTMAN for testing the endpoints:


![Screenshot (31)](https://github.com/harikrishnanakka/kkk/assets/152170400/b9deb5e5-af88-4273-86f0-067ef5e8e981)


3.After creating the user and now we have to login and that page should be authenticate for that the endpoint is:


     http://localhost:8000/api/login/


a.Json data provided for that is:

         {

         "email":"krishna123@gmail.com",

         "password":"krishna123"

          }

4.By giving this we can get the access token as shown in the below image:

![Screenshot (32)](https://github.com/harikrishnanakka/kkk/assets/152170400/88eaaa1f-7173-4cb9-816a-c1692a5ee237)


5.This is the AUthentication by using the JWT authentication

NOTE:USE THE POSTMAN APPLICATION FOR THE TESTING THE ENPOINTS FOR BETTER RESULT

# *************************************************Thank You*****************************************************************

