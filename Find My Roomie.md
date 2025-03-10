# Find My Roomie

<div align="center">



</div>

<div align="center">



</div>

![Find My Roomie.](./docs/static/images/findmyroomie.png)


## Table of Contents

- [The Problem](#the-problem)
- [The Solution](#supported-features)
- [What we Offer](#core-libraries)
- [Customer Benefits](#running-locally-with-npm)
- [Why are we unique?](#deployment)
- [Our Team](#documentation)
- [license](#license)
- [Contributors](#contributors)

## Introduction

**Find My Roomie** is a modern roommate-matching app designed to help college students find compatible roommates based on personality, lifestyle, and habits ensuring a smooth and enjoyable living experience. Unlike traditional roommate finding methods, Find My Roomie prioritizes safety, compatibility, and affordability. With the combination of of free background checks, institutional collaboration, self-matching, and free unlimited messaging positions Find My Roomie as a leader in the roommate-matching space, catering to students who value both security and a user-friendly experience.

As well as being **feature-rich**, **Find My Roomie** is also **fully responsive**, meaning it will work seamlessly on a wide range of devices. So whether you're dating on your desktop or your mobile, you'll always have a great experience.

## Supported Features

* Landing Page.
    
![Landing Page.](./docs/static/images/IMG_3475.jpg)

* OnBoarding Page.
    
![OnBoarding Page.](./docs/static/images/onboarding-page.png)
    
* Find My Roomie Cards.
    
![Find My Roomie Cards.](./docs/static/images/tinder-cards.png)

* Keyboard shortcuts.
    
![Keyboard shortcuts.](./docs/static/images/keyboard-shortcuts.png)
    
* Sending and receiving text messages in real time.
    
![Sending and receiving text messages.](./docs/static/images/snd-rcv-text.gif)
    
* Sending and receiving images in real time.
    
![Sending and receiving images.](./docs/static/images/snd-rcv-img.gif)

* Emoji support.
    
![Emojies support.](./docs/static/images/emojies.png)
 
* The ability to render HTML tags, links, emails, etc.
    
![HTML tags being rendered.](./docs/static/images/html-render.png)

* The ability to render markdown text.
    
![HTML tags being rendered.](./docs/static/images/md-markdown.png)

## Core Libraries

\- Create React App

\- React

\- React Router 6

\- Material UI

\- Redux

## Running locally with NPM

- Fork/Clone the repo:

```sh
git clone git@github.com:brave-date/brave-date.git
```

- Open the newly created directory:

```sh
cd brave-date
npm install
```

In order to run the project locally or build for production use, you will need to set the following environment variables to connect with the server: 

```sh
export REACT_APP_SERVER_URL=http://localhost:8000/api/v1
export REACT_APP_SOCKET_URL=ws://localhost:8000/api/v1/ws
```

Now, you can run the client:

```sh
npm start
```

Navigate to [http://localhost:3000](http://localhost:3000) to explore the landing page.

## Deployment

To deploy the client, you will need to set the following environment variables that help the client connect to the server.

```sh
* REACT_APP_SERVER_URL - Your deployed server APIs url.
* REACT_APP_SOCKET_URL - Your deployed server Sockets url.
```

### Deploy to a Static Hosting Provider

[![Deploy on Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/brave-date/brave-date)

[![Deploy on Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/brave-date/brave-date)

### Deploy locally with Compose v2

Navigate to [the server repository](https://github.com/brave-date/brave-date-server) and follow the instructions listed in [this section](https://github.com/brave-date/brave-date-server#deploy-locally-with-compose-v2) to run both the client and the server in docker containers.

## Documentation

You can refer to [the official documentation](https://brave-date.github.io/brave-date) for additional guides, examples, and APIs.

## License

This project and the accompanying materials are made available under the terms and conditions of the [`MIT LICENSE`](https://github.com/brave-date/brave-date/blob/main/LICENSE).
