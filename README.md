# ![logo](https://cdn.discordapp.com/attachments/1075493710692876330/1160639407947255908/logo_3.png?ex=653564ae&is=6522efae&hm=311db172fb3b5ac50d3581c1542bd5a53fd39465ecd3c4fedd567bc7f8061738&)

<!-- # Social-network -->

## Table of Contents
- ### [General Information](#general-information)
- ### [Technologies](#technologies)
- ### [Setup](#setup)
- ### [Usage](#usage)
- ### [Authors](#authors)

## General Information

This project involves the creation of a feature-rich social networking platform, inspired by popular social networks like Facebook. The platform will encompass a wide range of functionalities, including user registration and login, the ability to create posts, engage in commenting, send private messages, manage followers, and interact within groups. Key technologies utilized in this project include SQLite for data storage, Golang for backend development, JavaScript for frontend interactivity, HTML for structuring web pages, and CSS for styling. A single-page application approach will be adopted for a seamless user experience, with real-time features powered by WebSockets.

The project contains the following features:

- Followers
- Profile
- Posts
- Groups
- Notifications
- Chats

## Technologies
- ### [TypeScript](https://www.typescriptlang.org/)
- ### [React](https://react.dev/)
- ### [Golang](https://go.dev/)
- ### [HTML](https://www.w3.org/html/)
- ### [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- ### [SQLite](https://sqlite.org/index.html)

## Setup
<!-- TODO -->
Clone the repository
```
git clone https://01.kood.tech/git/ekhalets/social-network.git
```

## Usage
1. Run backend:
```
cd backend/
```
```
go run .
```

2. Open a new terminal and move to frontend directory:
```
cd frontend/
```
3. Install the required modules:
```
npm install
```
wait a minute or two if npm install fails then try `yarn install`

4. Run frontend: 
```
npm start
```
5. Test it from the [http://localhost:3000/](http://localhost:3000/)

Users for testing:
- jane.smith@email.com
- ajohnson@email.com
- sunny.d@email.com

Password <code>1111</code> for all.

For the docker, run:
```
make docker-run
```
To stop the docker, use:
```
make docker-remove
```

## Authors
- [Elena Khaletska](https://github.com/khaletska)
- [Olha Balahush](https://github.com/OlhaBalahush)
- [Karme Bärg](https://01.kood.tech/git/Karme)
- [Taivo Tokman](https://github.com/taivox)
- [Gert Nõgene](https://01.kood.tech/git/Gert)
- [Even Luiv](https://01.kood.tech/git/evenluiv)
