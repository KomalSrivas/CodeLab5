# CodeLab5

Shows on localhost:81 [  a formatted meal recommendation with an associated price ] 

Process

Overview

We use Flask to build a very small but runnable example - a meal recommendation service! 

Container 1, api, will publish meal recommendations via an API

Container 2, consumer, will consume the meal recommendation and present it via HTML 

Container 3, db, will provide meal recommendations to Container 3

Container 4, dba, will provide a GUI to container 3

We organize our work in the following structure:
		
		/
		
		api/
		
			code/
			
			Dockerfile
			
		consumer/
		
			code/
			
			Dockerfile
			
		db/
		
			data/ 
			
		docker-compose.yml

