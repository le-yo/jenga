[![Latest Unstable Version](https://poser.pugx.org/amranidev/scaffold-interface/v/unstable)](https://packagist.org/packages/amranidev/scaffold-interface) [![License](https://poser.pugx.org/amranidev/scaffold-interface/license)](https://packagist.org/packages/amranidev/scaffold-interface)

# ScaffoldInterface
####this is a test version####

![Scaffold](http://i.imgur.com/KHDtfP1.png)


Scaffold Interface for laravel v5.1 using materailize

####features :

+ Generate your model,views,controller and migrations just in few clicks.

+ Rollbacking possibility.

+ Using an interface to design your table

###I. Package installation

  1. Add scaffold-interface to your composer.json file to require Scaffold-Interface :

    ```json
    require : {
    "laravel/framework": "5.1.*",
    "Amranidev/scaffold-interface": "dev-master"
    }
    ```

  2. Update Composer :

  
    ```
    composer update
  
    ```

  3. Add the service provider to config/app.php :

    ```php

    Amranidev\ScaffoldInterface\ScaffoldInterfaceServiceProvider::class,
    Amranidev\Ajaxis\AjaxisServiceProvider::class,
  
    ```

  4. Publish assets in your application with :

    ```
    php artisan vendor:publish
  
    ```

  5. Migrate scaffoldinterface :
  
    ```
    php artisan migrate

    ```

Congratulations, you have successfully installed Scaffold Interface!

###II. Usage
  
  1. Access to scaffold interface :
    
    "localhost:8000/scaffold" to get into scaffoldinterface.
  
  2. Table creation :

     tablename must be tiny and plural *for example : products* . you can add many of attributes like (String,date,longtext,etc.) 

  3. After creation :
     
     to complete your scaffolding . go to your terminal and type.  
     
     ```
     $ php artisan migrate
     
     ```
  
  4. Finally :
     
     scaffolding it's done. you can use your CRUD for example : localhost:8000/product   



###contact : amranidev@gmail.com
