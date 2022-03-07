# Docker-compose for WordPress development

 - At the moment, docker-compose file only contains three services(MySQL, PHPMyAdmin & WordPress)
 - The WordPress volume is mounted to the host operating system(Windows etc.). So, that developers can make changes in the code easily.
 - Contributions are strongly welcome

# Setup Guide
 - Clone the repository
 - Go inside the repository
 - Run *docker-compose up*
 - Login to PHPMyAdmin.
 - Create database
 - Access WordPress URL
 - Enter database configurations etc.
 - Thats it

**Note**

 - Update the database configuration in the file before running the containers
 - Don't need to enter the host while logging-in to PHPMyAdmin

