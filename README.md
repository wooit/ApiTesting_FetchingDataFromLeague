# ApiTesting_FetchingDataFromLeague

## General Info
I have created this GitHub repository to conduct tests on an API that I am using in another of my project. 
* API link: [RiotGames API](https://developer.riotgames.com/)
* Link of my project: [Repository FetchingDataFromLeague](https://github.com/wooit/FetchingDataFromLeague)
  
In this repository, I am testing the API routes that I use in my project to ensure that my interface can adapt to changes in the data. Since the API is constantly evolving, with frequent updates and modifications, it’s crucial to verify that these changes are properly reflected in my project. By regularly testing these routes, I can make the necessary adjustments to my user interface, ensuring that it remains functional and up-to-date as the API evolves.

I have uploaded several videos to demonstrate how my testing environment is set up in Postman. These videos cover key aspects such as how to obtain an API key, what my route tests look like, and how to run tests across my entire collection of routes. Additionally, I provide a walkthrough on how to generate an automated report of these tests by using Newman. These resources are intended to help others understand the testing process and replicate it in their own environments.

## Get and set an API key
First it's necessary to visit the RiotGames API in order to get a valid developper key (this key is valid only for 24 hours) as demonstrated in the following video. Then copy / paste in the global variables of your collection on Postman.

https://github.com/user-attachments/assets/f9f66cf0-2909-4dd6-85b1-ae0c3082a2b4

## A quick glance at some of my tests
In my tests, I focus specifically on the properties sent by the API that are directly used in my project. I also verify the structure of the response and the status code to ensure that everything aligns with my requirements. By testing only the information that impacts my project, I can quickly identify what needs to be updated when the API evolves. This targeted approach allows me to efficiently adapt to changes and maintain the functionality of my application.

https://github.com/user-attachments/assets/9a994f07-e22f-43d7-87ba-c3e155fc07ea

## Run the entire test collection at once
Testing a collection of API routes in Postman offers significant advantages, especially once everything is properly configured. With just one click, I can execute tests for all 15 routes simultaneously, ensuring that they all function as expected. This streamlined process not only saves time but also provides a comprehensive overview of the API's performance and reliability. By automating these tests, I can quickly identify any issues across multiple routes and make necessary adjustments to keep my project running smoothly.

https://github.com/user-attachments/assets/f817e776-866f-47d7-a6f3-aa93e9fd21fc

## Generate a report automatically with 'newman'
