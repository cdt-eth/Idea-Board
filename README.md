<div align="center">
<h1>Idea Board</h1>

<a href="https://www.emojione.com/emoji/1f4a1">
<img height="80" width="80" alt="palette" src="https://user-images.githubusercontent.com/26611339/40788877-100f43bc-64bf-11e8-89a6-8e6d0d164475.png" />
</a>

<p> An Idea Board built with Rails & React. </p>
</div>

<hr />

[![GitHub followers](https://img.shields.io/github/followers/christiandavidturner.svg?style=social&label=Follow)](http://github.com/christiandavidturner) [![Twitter Follow](https://img.shields.io/twitter/follow/imcdt.svg?style=social&label=Follow)](https://twitter.com/imcdt)

## Table of Contents

- [Overview](#overview)
- [Tools](#tools)

# Overview

An Idea Board built with Rails & React. Create-React-App was used to scaffold the frontend. Rails was used for the api configuration. It has endpoints for adding ideas as well as editing and deleting them. I used Axios to make async requests to our rails app to populate the data and create new ideas. I enabled CORS to allow us to make these requests.

SQLite is the db used in development by default but Postgres is used for production to play well with Heroku, where I deployed the final project. You can see the final project [here](#).

# Tools

- Rails
- React
- Axios
- SQLite 3
- Postgres
- Rack/Cors
- Heroku
