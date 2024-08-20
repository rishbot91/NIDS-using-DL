# Network Intrusion Detection System

This project is designed to detect network intrusion anomalies using the NSL-KDD dataset. It employs deep learning techniques, specifically the Long Short-Term Memory (LSTM) model, an advanced version of Recurrent Neural Network (RNN), as well as the K-Nearest Neighbors (KNN) algorithm for both binary and multi-class classification.

## Features

- Utilizes LSTM and KNN algorithms for network intrusion detection.
- Front-end interface developed with ReactJS for user interaction.
- Predicts the type of attack based on user-input hacking parameters.
- Stores data in MongoDB.
- Back-end framework implemented with NodeJS.
- Fully responsive design.
- Implements session and cookies for user authentication.
- Utilizes Google OAuth 2.0 for secure user authentication.
- User details stored securely in MongoDB using salted hash.

## To run locally on your system:


- Fork or Clone the project using command [git clone "https://github.com/rishbot91/NISD-using-DL.git"]
- Create a .env file and set up the dovenv variable which is used in app.js (or) remove dotenv variables from app.js and set the links like mongoDB link etc.
- Use command [npm install] to install all the packages.
- Use command [node app.js] to run it locally.
