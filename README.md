### a plasma and blood management website which uses docker compose for defining and running multi-container docker app with the help of YAML file to configure the app's services.
---------------------------------------------------------------------    
    Tech used - Docker, SQL, Bootstrap, PHP
---------------------------------------------------------------------

## Instructions on how to run

1->use docker-compose build (build the yml file)

2->and docker-compose up to run the container

3->after building

4->go to http://localhost:30002/  --> you will go to phpmyadmin then enter username->avinashkumar password->11812851 then go to ca_db database and import the sql file from www folder

5->then go to http://localhost:30001 --> then you see the blood-plasma bank page is working now

6->then got to http://localhost:30002 --> login with the these details -> username & password as mentioned in compose file and you can see the complete web app
