# ft_server

### 🎯 Object

This is a System Administration subject, to discover Docker and set up my first web server!

* **Wordpress**, 
* **phpMyAdmin**, and a 
* **SQL database**

• It was set up a web server with **Nginx**, in only one debian buster docker container. 

• Ther web server is be able to run several services at the same time: WordPress website, phpMyAdmin and MySQL. (It was make sure that the SQL database works with the WordPress and phpMyAdmin.)

• The server is be able to use the SSL protocol.

• Depending on the url, the server redirects to the correct website.

• Ther server is running with an autoindex that is be able to be disabled.

### 💻 How to Run

docker build . -t ft_server
docker run -it -p80:80 -p443:443 ft_server

