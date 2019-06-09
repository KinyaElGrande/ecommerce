**Execute these commands below as in their order** 

~~~
1. git clone https://github.com/deniswawerungure/ecommerce.git
~~~

~~~
2. composer install
~~~

~~~
3. cp .env.example  .env
~~~

~~~
edit .env
> DB_CONNECTION=[YOUR_DATABASE_CONNECTION]
> DB_HOST=[YOUR_HOST]
> DB_PORT=[YOUR_PORT]
> DB_DATABASE=[YOUR_DB_NAME]
> DB_USERNAME=[YOUR_DB_USERNAME]
> DB_PASSWORD=[YOUR_DB_PASSORD]
~~~

~~~
4. php artisan key:generate
~~~

~~~
5. php artisan migrate
~~~

~~~
6. php artisan db:seed
~~~

~~~
7. php artisan vendor:publish
-> Press 0 and then press enter to publish all assets and configurations.
~~~

~~~
8. php artisan storage:link
~~~

~~~
9. composer dump-autoload
~~~



**How to log in as admin:**

> *http(s)://example.com/admin/login*

~~~
email:admin@example.com
password:admin123
~~~

**How to log in as customer:**

*You can directly register as customer and then login.*

> *http(s)://example.com/customer/register*


