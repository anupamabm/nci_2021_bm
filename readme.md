
# Readme for Blockchain technology project Anupama Bitmandi Mutt Student id : x20205121

This is the readme for this project.  

## First downloadn and install Visual Studio Code from th below url

```https://code.visualstudio.com/Download```

## Install Git locally and link to to the new repository created in github account##

1. get a github account at github.com

2. install git locally

```https://github.com/git-guides/install-git```

## Next is to Install NodeJs ##

Install following the instructions at the following web page:

```https://nodejs.org/en/download/```

## In order to start using code from git repo clone it from a Repository ##

Create a folder for your college projects.  Go into that folder.

Inside that college folder, run:

```git clone https://github.com/anupamabm/nci_2021_bm.git```

## Updating Code in Repo from Github ##

From the terminal in Visual Studio Code (or from the command line - as long as you are in the folder), run the following command:

```git pull origin main```

  make your changes

  then run the following commands:

```$git add <your updated files>```

```$git commit -m "<your commit message>"```

```$git push origin main```

# Once all this is done just verify all the installatiosn aer done properly by checking the versions
Git :

```$git version```

Node :

```$node -v```


## Executing a .JS file ##

To execute a javascript file using node.js, run the following command:

```$node <file name>```

  example : node distribute.js


## Dependencies and NPM ##

In order to have the node_modules folder we need to install all the required packages.

From inside your folder, to create your own package.json:

```$npm init```


## CURL accessing of handlers"

To POST to a route, execute the following CURL command:

```curl -XPOST http://localhost:8080/transfer -H 'content-type: application/json' -d '{"account_to": "0x4d60E7f9d4901816981a0E4c6D95F394159C6371", "amount": "123000"}'```


## Set up docker ##
Install teh docker desktop and verify installation is proper by giivng below commands :

```docker ps``` : Gives the list of docker containers

```docker build -t nci/lab2021 .```  : builds the new docker container

```docker run -p 8090:8080 --name nci -d nci/lab2021```  : runs the image named "nci"

```docker start/stop [name]``` : start/stop the container

```docker logs [name]``` : Check the working logs for running image

### Use the below commadn to run these scripts from docker compose  ####

````docker-compose up````

### Below are the links of Git and Docker hub url for this code : ###

Git url : https://github.com/anupamabm/nci_2021_bm
Docker hub url : https://hub.docker.com/repository/docker/anupamabmutt/abm_nci_blockchain_project


