# Bot App

## Description
This is a web application for managing a collection of bots in your bot army. Users can view a collection of available bots, add bots to their army, release bots from their army, and discharge bots from the service.

## Requirements and Specifications
To run this project, you need the following:
* Node.js (v14.0.0 or higher)
* npm (v6.0.0 or higher)

## Setup Instructions
1. Make sure the db.json file is running by using json-server --watch db.json --port 3000
2. Run it on http://localhost:3000/bots

Follow these steps to set up the project on your local machine:
1. Clone the repository: `git clone git@github.com:ArchyMulei/Phase-2-Week-2-Code-Challenge.git`
2. Navigate to the project directory: `cd Phase-2-Week-2-Code-Challenge`
3. Install dependencies: `npm install`
4. Start the development server: `npm start`
5. You can access the app on `localhost:3000`

## Technologies Used
* React
* HTML
* CSS
* React Router

## How to Use
1. Upon opening the app, you will see the main page displaying the title "Bot App."
2. The navigation bar provides links to "Bot Collection" and "Your Bot Army" pages.
3. In the "Bot Collection" page, you can view a list of available bots. You can add a bot to your army by clicking the "Add to Army" button.
4. In the "Your Bot Army" page, you can view a list of bots in your army. You can release a bot from your army by clicking the "Release" button, which removes it from the army but not from the service.
5. You can also discharge a bot from the service by clicking the red "x" button, which deletes the bot from both your army and the backend service.
6. The app provides an intuitive interface to manage your bot army seamlessly.

## Author
Created by Archibald Mulei

## Contact
Feel free to contact me at archimulei023@gmail.com for any questions or inquiries. Contributions are welcome! Visit the [GitHub repository](https://github.com/ArchyMulei/Phase-2-Week-2-Code-Challenge) to contribute.

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
This project is licensed under the MIT License.