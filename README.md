# P1008-WordPressDockerEnv
Docker-compose environment for local WordPress development.

# Setup
This will require Docker and docker-compose installed on your computer.


Fill in the environment variables in the `.env` file. You can leave the `MYSQL_VERSION` and `WORDPRESS_VERSION` to the default values.
But you should change `MYSQL_ROOT_PASSWORD` and `DB_PASSWD` to something strong and random. `DB_USER` is normaly something like the person that is going to have the website or a company.


To run the setup open a command prompt and type `docker-compose up` or `docker-compose up -d` to detach the terminal from the process and run it in the background.


To stop the containers use either `CTRL+C` or `docker-compose down`.
