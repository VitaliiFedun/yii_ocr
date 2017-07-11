
Installation
------

Create a project:

~~~
composer create-project --prefer-dist --stability=dev yii-ocr project
~~~

or clone the repository for `pull` command availability:

~~~
git clone https://github.com/VitaliiFedun/yii_ocr.git project
cd project
composer install
~~~

Init an environment:

~~~
php init
~~~

Fill your DB connection information in `config/common-local.php` and execute migrations:
and create database 'ocr_data'

~~~
php yii migrate
~~~

Sign up on site or create your first user manually:

~~~
php yii user/users/create
~~~

Init RBAC roles:

~~~
php yii rbac/init
~~~

Assign `admin` role to your user:

~~~
php yii roles/assign
~~~