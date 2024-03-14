# Ecommerce Application
 
E-commerce is a fully functional *Clothing Ecommerce* Platform made using Django and React.


## Characteristic Features

* <img src="https://img.icons8.com/ultraviolet/40/000000/shop.png" height = "20" width = "20"/> Allow users to browse, view, and purchase clothing products
* <img src="https://img.icons8.com/ultraviolet/40/000000/color-dropper.png" height = "20" width = "20"/> Provide users with a diverse selection of products, offering a range of color and size options corresponding to individual preferences and requirements
* <img src="https://img.icons8.com/ultraviolet/40/000000/lock-2.png" height = "20" width = "20"/> Utilized strong encryption algorithms such as RSA to sign JWTs for user safety
* <img src="https://img.icons8.com/fluent/48/000000/fast-cart.png" height = "20" width = "20"/> Cart functionality for adding the products in the cart, updating the quantities in the cart and checking the items in the cart
* <img src="https://img.icons8.com/ultraviolet/40/000000/filter.png" height = "20" width = "20"/> Implementing flexible filtering options such as categories, price ranges
* <img src="https://img.icons8.com/color/48/000000/overview-pages-1.png" height = "20" width = "20"/> "Implemented pagination to efficiently manage large datasets, providing users faster access to the products


## Tech Stack Used
 
* [React.js](https://github.com/facebook/react "React.js + Hooks") is used for creating the User Interface
    * [React's Context API](https://github.com/facebook/react "React's Context API") is used for managing complex state.
* [Django](https://www.djangoproject.com/ "Django") is used for the backend.
    * [Django Rest Framework](https://www.django-rest-framework.org/ "Django Rest Framework") is used for setting up API endpoints.
* [SQLite DB](https://sqlite.org/docs.html "SQLite DB") is used that comes bundled by default in the Django app.
* [React Router Dom](https://reactrouter.com/web "React Router Dom") is used for declarative routing in the browser.
* [Simple JWT](https://django-rest-framework-simplejwt.readthedocs.io/en/latest/ "Simple JWT") provides a JSON Web Token authentication backend for the Django REST Framework.
* [Pillow](https://pillow.readthedocs.io/en/stable/ "Pillow") library is used for extensive file support and image processing tasks.
* [Localstorage](https://developer.chrome.com/docs/devtools/storage/localstorage/ "Localstorage") used for storing user info like access tokens and session data in the browser storage.


## Prototype

**Product List View**

![list view](https://github.com/Sriharikagathi/Ecommerce-Web-Application/assets/131581052/a866da75-d2e2-4673-8d32-d59df4463f15)


**Pagination**

![pagination](https://github.com/Sriharikagathi/Ecommerce-Web-Application/assets/131581052/20d1bb4d-09f6-477b-bd08-ded03bfcb47f)

**Product Detail View**
![product detail view](https://github.com/Sriharikagathi/Ecommerce-Web-Application/assets/131581052/69c20351-c808-4b82-a3a6-c81e749eff1f)

**Product Added to Cart**

![product added to cart](https://github.com/Sriharikagathi/Ecommerce-Web-Application/assets/131581052/ef685e57-e1f7-42a8-99e6-776c9e9a60bf)

**Cart View**

![cartview](https://github.com/Sriharikagathi/Ecommerce-Web-Application/assets/131581052/f2ca519a-32ca-41e0-bcf6-2f8ad4f7ec4c)


## What more can be done?
A Product reccomendation system: 
Implement a sophisticated product recommender system that analyzes user preferences and past searches for user customized reccommendations

## How to setup on a local machine?

To setup this projct on a local machine:

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
