# V Profile Project - Local Setup
I’ve just completed my V Profile Project, where I built a full multi-tier web application stack right on my local environment. This hands-on experience was a great deep dive into practical DevOps and has prepared me for even more advanced challenges in the near future.

**What I Built**

**1-** **Full Multi-Tier Web Application Stack**
To simulate a real-world production environment, I assembled a complete web app stack tailored for a social networking platform built in Java. Here's an overview of the components I worked with:

- **Nginx – Configured as a load balancer to efficiently route traffic across backend services.**

- **Apache Tomcat – Hosted the core Java application that powers the web app’s backend logic.**

- **RabbitMQ – While it served as a placeholder in this setup, integrating it gave me practical exposure to message brokers.**

- **Memcached – Implemented caching with Memcached to accelerate database query responses and offload MySQL.**

- **MySQL – Deployed as the primary relational database to store user data and app content.**

**2-** **Automation with Vagrant**
To eliminate repetitive tasks and ensure a consistent environment, I used Vagrant to automate the provisioning of separate virtual machines for each component. This made the setup reproducible and scalable, while saving time on manual configuration.

**3.** **Testing and Validation**
Once the full stack was up, I rigorously tested to verify system integrity and service interaction:***

- **Confirmed Nginx was distributing requests correctly to the Tomcat backend.**

- **Verified user information was stored and retrieved from MySQL without issues.**

- **Checked Memcached was effectively caching data to reduce MySQL load.**

- **Ensured RabbitMQ was properly installed and integrated, even if inactive in this phase.**

# Prerequisites
- JDK 17 or 21
- Maven 3.9
- MySQL 8

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- Tomcat
- MySQL
- Memcached
- Rabbitmq
- ElasticSearch
# Database
Here,we used Mysql DB 
sql dump file:
- /src/main/resources/db_backup.sql
- db_backup.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < db_backup.sql


