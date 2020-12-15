### Application Name
* Blog H

## Author
* Henry Kanyoro

### Description
* This is a website where users get a chance to post and view quotes from other users.
* User can also give their comments on different qoutes posted by other users.


## To run my page on your browser,

* Git  clone https://github.com/HenryKanyoro/Blog.git to your terminal
* Open the pitch with your text editor.
* Install necessary requirements as highlighted on [run](**pip install -r requirements.txt**)

### creating a DATABASE
*   1.Go to your terminal Install postgress bt [run](sudo apt-get install postgresql postgresql-contrib libpq-dev)
*   2. Open your shell by using **psql**
*   3. Create database by *CREATE DATABASE  logs;*
*   4. Connect to your database by */c logs*
*   5.To view your database structure use *select *from Users;*

* ##### Exporting database configurations
* export SQLALCHEMY_DATABASE_URI=postgresql+psycopg2://{User Name}:{password}@localhost/{database name}

* Use pip install with the version of your text editor
* To render the page live locally, run **./start.sh**

## Known Bugs
* Still editing on mail search authentification for signup template.

## Technologies Used
* Python3.8
* flask
* Heroku
* html

## Support and contact details
* email *kanyorohenry6@gmail.com*
* phn: *0796636481*

### License
licensed under [MIT license](LICENSE)