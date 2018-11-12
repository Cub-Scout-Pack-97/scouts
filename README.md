# Cub Scouts Pack 97 
This repo will let you build and run the Docker containers for the cubscoutpack97.org app.

## Production version
Running the following steps will alow you to run the Production level version cubscoutpack97.org web app on your local machine.
1. Install Docker to your local machine. Go to [The Docker site](https://www.docker.com/get-started) and follow there install steps.

2. Install the latest version of MongoDB. Go to the [MongoDB site](https://www.mongodb.com/download-center/community) and follow their steps

3. From your terminal do the following:

    a. Clone this repo to your local drive.
    ```
    git clone https://github.com/Cub-Scout-Pack-97/scouts.git
    ```
        
    b. Open the new scouts folder
    ```
    cd scouts
    ```
        
    c. Build the docker containers and images
    ```
    docker-compose build
    ```
        
    d. Run the docker images
    ```
    docker-compose up
    ```
    
4. From your web browser enter 'localhost' into the URL bar
Congratulations! You are now running the cubscoutpack97.org web app on your local machine.

## Developer version.
This repo will let you build and run the development version of the Docker containers for the cubscoutpack97.org web app.
1. Complete the steps for setting up the "Production version" of the cubscoutpack97.org web app.

2. Install the latest version of NodeJS. Go to the [NodeJS site](https://nodejs.org/en/) and follow their steps

3. From your terminal do the following:

    ### Front End
      
      a. Clone the Front End repo to your local drive.
      ```
      git clone https://github.com/Cub-Scout-Pack-97/Pack97NodeJSFE.git
      ```
      
      b. Open the Pack97NodeJSFE folder.
      ```
      cd Pack97NodeJSFE
      ```
      
      c. Checkout the develop branch.
      ```
      git checkout develop
      ```
      
      d. Run install.
      ```
      npm install
      ```
      
    ### Back End
      
      a. Clone the Front End repo to your local drive.
      ```
      git clone https://github.com/Cub-Scout-Pack-97/Pack97NodeJSBE.git
      ```
      
      b. Open the Pack97NodeJSBE folder.
      ```
      cd Pack97NodeJSBE
      ```
      
      c. Checkout the develop branch.
      ```
      git checkout develop
      ```
      
      d. Run install.
      ```
      npm install
      ```
      
    ### Mail
      
      a. Clone the Front End repo to your local drive.
      ```
      git clone https://github.com/Cub-Scout-Pack-97/Pack97NodeMail.git
      ```
      
      b. Open the Pack97NodeMail folder.
      ```
      cd Pack97NodeMail
      ```
      
      c. Checkout the develop branch.
      ```
      git checkout develop
      ```
      
      d. Run install.
      ```
      npm install
      ```
      
    ### Container Running
     c. Build the docker containers and images
      ```
      docker-compose -f dev.yml build
      ```
        
      d. Run the docker images
      ```
      docker-compose -f dev.yml up
      ```
    
    
