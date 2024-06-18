# symfony5-concepts-implementation

##### To build the container, run:
`docker-compose up -d --build`

##### Install Symfony CLI using one of the ff:
`wget https://get.symfony.com/cli/installer -O - | bash`

`curl -sS https://get.symfony.com/cli/installer | bash`

##### Check if your system meets the Symfony requirements
`symfony check:requirements`

##### Create Symfony Application
###### Run this if you are building a traditional web application
`symfony new my_project_directory --version=“5.4.*” --webapp`

###### Run this if you are building a microservice, console application or API
`symfony new my_project_directory --version=“5.4.*”`

Refer to this [link](https://www.twilio.com/en-us/blog/get-started-docker-symfony) for a more detaill setup

