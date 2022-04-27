# What does this docker-compose yml do?
> This docker-compose file is being used in conjuction with specific setup with Traefik 2. I have not tested its usability with a differnt setup of Traefik 2. I'll document that setup later.

## ENV {ENVIROMENT FILE}
> ENV files can hold sensitive information that you do not want to be seen in your docker-compose files.
> Using the ENV file can let you quickly edit password or domain without digging through your compose file.

If you are to use this compose.yml file ensure you rename the **.env.sample** file to **.env**

#### How to deploy this YML file?
>with console output

```docker-compose -f keycloak.yml up``` 

>without console output

```docker-compose -f keycloak.yml up -d``` 



