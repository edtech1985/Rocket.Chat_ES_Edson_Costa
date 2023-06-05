<p align="center"> 
  <img  src="https://github.com/RocketChat/Rocket.Chat.Artwork/raw/master/Logos/2020/png/logo-horizontal-red.png" data-canonical-src="https://github.com/RocketChat/Rocket.Chat.Artwork/raw/master/Logos/2020/png/logo-horizontal-red.png" width="400" />
</p>

# Rocket.Chat_ES_Edson_Costa
Welcome to my Rocket.Chat Enterprise Solutions Technical Assessment repository!

## 🚀 Overview
This repository contains the results of the technical assessment for the Rocket.Chat Enterprise Solutions Team. It includes the setup and deployment of a Rocket.Chat server instance, as well as the API queries and updates performed.

## 🚀 Rocket.Chat Server Setup
To complete the technical assessment, I followed the installation method recommended in the Rocket.Chat documentation, which involved using Docker & Docker Compose. Here are the steps I followed:

1. Installation Method:
   - I chose to install Rocket.Chat using Docker & Docker Compose. I followed the steps provided in the Rocket.Chat documentation: [Docker & Docker Compose Installation](https://docs.rocket.chat/deploy/prepare-for-your-deployment/rapid-deployment-methods/docker-and-docker-compose).

2. URL:
   - Initially, I used the URL `edtech1985:3000` to run the server locally since I was the only user accessing it. However, to allow external users to access it, I used Ngrok to generate a temporary URL. The installation and setup instructions for Ngrok can be found at [Ngrok Docs](https://ngrok.com/docs/).
   - Important: Please notify me when evaluating the assessment so that I can run the server and provide you with the updated Ngrok URL.

3. Access Credentials:
   - User: edtechRocketChat
   - Password: Provided via email

Please refer to the respective documentation links for detailed instructions on each step.

Please refer to the [installation documentation](https://docs.rocket.chat/) and [GitHub repository](https://github.com/RocketChat/Rocket.Chat) for detailed information on Rocket.Chat installation methods and setup instructions.

## 🚀 API Queries and Updates

The following API queries and updates were performed on the Rocket.Chat server using Postman:

1. Create a new user via an API endpoint:

   - Request: POST http://localhost:3000/api/v1/users.create
   - Headers: X-Auth-Token, X-User-Id
   - Body: 
     ```
     {
         "name": "CreateUserTestApi",
         "email": "edson.costa@rocket.chat",
         "password": "Password23$$",
         "username": "TestCreateUser"
     }
     ```
   - Response: [Create a new user via an API endpoint (JSON)](https://github.com/edtech1985/Rocket.Chat_ES_Edson_Costa/blob/main/results/users_create_response.json)
   - Screenshot: [Create a new user via an API endpoint](https://github.com/edtech1985/Rocket.Chat_ES_Edson_Costa/blob/main/results/users_create.png)

2. Get room information via an API endpoint:

   - Request: GET http://localhost:3000/api/v1/rooms.info?roomId=GENERAL
   - Headers: X-Auth-Token, X-User-Id
   - Response: [Get room information via an API endpoint (JSON)](https://github.com/edtech1985/Rocket.Chat_ES_Edson_Costa/blob/main/results/room_info_response.json)
   - Screenshot: [Get room information via an API endpoint](https://github.com/edtech1985/Rocket.Chat_ES_Edson_Costa/blob/main/results/room_info.png)

3. Get a list of all user roles in the system via an API endpoint:

   - Request: GET http://localhost:3000/api/v1/roles.list
   - Headers: X-Auth-Token, X-User-Id
   - Response: [Get a list of all user roles in the system via an API endpoint (JSON)](https://github.com/edtech1985/Rocket.Chat_ES_Edson_Costa/blob/main/results/system_usres_roles_response.json)
   - Screenshot: [Get a list of all user roles in the system via an API endpoint](https://github.com/edtech1985/Rocket.Chat_ES_Edson_Costa/blob/main/results/system_usres_roles.png)

Please find the API responses and screenshots in the provided links.

Please refer to the [Rocket.Chat API documentation](https://developer.rocket.chat/reference/api) for more details on the available API endpoints and their usage.

## 🚀 Additional Integrations and Setup
Optional integrations and setup performed:

- As a cryptocurrency enthusiast and investor, I installed CryptoVert, which allows for cryptocurrency conversions.

## 🚀 Results and Screenshots
The results of the technical assessment, including screenshots and actual files/collections, can be found in the [results](results/) directory of this repository.

## 🚀 Contact Information
If you have any questions or need further information, please feel free to contact me:

- Name: Edson Costa
- Email: edtech1985@gmail.com

Thank you for considering my submission. I hope you find the results and documentation satisfactory.

