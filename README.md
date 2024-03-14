# Ecommerce Application
 
E-commerce is a fully functional *Clothing Ecommerce* Platform made using Django and React.


## Characteristic Features

* <img src="https://img.icons8.com/ultraviolet/40/000000/shop.png" height = "20" width = "20"/> Viewing the cloths and we can 
* <img src="https://img.icons8.com/ultraviolet/40/000000/color-dropper.png" height = "20" width = "20"/> Select from a wide variety of products, different color and sizes options.
* <img src="https://img.icons8.com/ultraviolet/40/000000/lock-2.png" height = "20" width = "20"/> Utilized strong encrption algorithm like JWT for user safety and to prevent the tampering
* <img src="https://img.icons8.com/fluent/48/000000/fast-cart.png" height = "20" width = "20"/> we can add the products in the cart and we can change their quantities and we can check the price of the cart
* <img src="https://img.icons8.com/ultraviolet/40/000000/filter.png" height = "20" width = "20"/> we can filter our products based on the category and prices
* <img src="https://img.icons8.com/color/48/000000/overview-pages-1.png" height = "20" width = "20"/> Pagination feature for better user experience and decreased server load.


## Tech Stack Used

* [React.js](https://github.com/facebook/react "React.js + Hooks") is used for creating the User interface.
    * [React's Context API](https://github.com/facebook/react "React's Context API") is used for managing complex state.
* [Django](https://www.djangoproject.com/ "Django") is used for the backend purpose of the project.
    * [Django Rest Framework](https://www.django-rest-framework.org/ "Django Rest Framework") is used for setting up API endpoints.
* [SQLite DB](https://sqlite.org/docs.html "SQLite DB") is used as the database which comes as in built in the django project.
* [React Router Dom](https://reactrouter.com/web "React Router Dom") is used for declarative routing in the browser.
* [Simple JWT](https://django-rest-framework-simplejwt.readthedocs.io/en/latest/ "Simple JWT") provides a JSON Web Token authentication backend for the Django REST Framework.
* [Pillow](https://pillow.readthedocs.io/en/stable/ "Pillow") library is used for extensive file support and image processing tasks.
* [Localstorage](https://developer.chrome.com/docs/devtools/storage/localstorage/ "Localstorage") used for storing user info like access tokens and session data in the browser storage.



## Prototype

**Product List View**
![Product List View](images/listview.png)

**Pagination**
![Pagination demonstration](images/pagination.png)

**Product Detail View**
![Product Detail View](images/detailview.png)

**Product Added to Cart**
![Product added to cart](images/addedtocart.png)

**Cart View**
![Cart View](images/cartview.png)



## What more can be done?
 
This project is far from perfect. Many more things can be done in order to make the user experience and the overall functioning of the product. These are some of the features that I believe could be added in the future:
 
*It is a cloth recommendation system which gives us the cloth based on your search.
* Mechanism for storing user tokens in *cookies*
*Integrating the database can be done
 


## How to setup on a local machine?

To setup this project on a local machine:

* Fork this repository.
* Clone the repository using simple zip download or use the command
    ```
        git clone https://github.com/{Your-Username}/Ecommerce-Application.git
    ```
* Create a virtual environment for the project
    ```
        pip install virtualenv
        virtualenv env_name
        
    ```
* Activate the Virtual environment
    ```
       source env_name/bin/activate
    
    ```
    Once the virtual environment is activated, the name of your virtual environment will appear on left side of terminal. This will let you know that the virtual environment is currently active. 

* Install all the dependencies
    ```
       pip install -r requirements.txt
    ```

* To start the  the developement server, run the command
    ```
        cd ./backend
        python manage.py runserver
    ```
* Installing the dependencies for frontend client
    ```
        cd ./client
        npm install
    ```    
* For viewing the app
    ```
        npm start
    ```

    Now at `localhost:3000`, you should see the app successfully running.
