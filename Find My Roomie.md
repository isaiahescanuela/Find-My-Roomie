# Find My Roomie

<div align="center">

![Typing](https://badgen.net/npm/types/prop-types)
[![Netlify Status](https://api.netlify.com/api/v1/badges/78f89ea8-00c2-4966-81c6-c601cf7f81dd/deploy-status)](https://app.netlify.com/sites/brave-date/deploys)
[![Demo on Netlify](https://badgen.net/badge/icon/Netlify/green?icon=slack&label=brave-date)](https://brave-date.netlify.app/)
[![Tag](https://badgen.net/github/tag/brave-date/brave-date)](https://github.com/brave-date/brave-date/releases/tag/v0.2.0)
[![Docs](https://badgen.net/badge/icon/docs?icon=wiki&label)](https://brave-date.github.io/brave-date/)

</div>

<div align="center">

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-1-blue.svg?style=flat)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

</div>

![Find My Roomie.](./docs/static/images/Banner.png)

## Table of Contents

- [Introduction](#introduction)
- [Supported Features](#supported-features)
- [Core Libraries](#core-libraries)
- [Running locally with NPM](#running-locally-with-npm)
- [Deployment](#deployment)
- [Documentation](#documentation)
- [License](#license)
- [Contributors](#contributors)

## Introduction

**Find My Roomie** is a modern roommate-matching app designed to help college students find compatible roommates based on personality, lifestyle, and habits ensuring a smooth and enjoyable living experience. Unlike traditional roommate finding methods, Find My Roomie prioritizes safety, compatibility, and affordability. With the combination of of free background checks, institutional collaboration, self-matching, and free unlimited messaging positions Find My Roomie as a leader in the roommate-matching space, catering to students who value both security and a user-friendly experience.

As well as being **feature-rich**, **Find My Roomie** is also **fully responsive**, meaning it will work seamlessly on a wide range of devices. So whether you're dating on your desktop or your mobile, you'll always have a great experience.

## Supported Features

* Landing Page.
    
![Landing Page.](./docs/static/images/landing-page.png)

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

## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/wiseaidev"><img src="https://avatars.githubusercontent.com/u/62179149?v=4?s=100" width="100px;" alt="Mahmoud Harmouch"/><br /><sub><b>Mahmoud Harmouch</b></sub></a><br /><a href="#maintenance-wiseaidev" title="Maintenance">🚧</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
