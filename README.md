# Game Plan Documentation

## Purpose

Game Plan simplifies and streamlines the the process of organising board game events.

The purpose of the app is to empower board game hobbyists to connect, discover, host and join game events within their local communities, with a focus on streamlining the event creation process. The app aims to make make it effortless to be a part of these events while removing the typical barriers of scheduling conflicts and logistical challeneges. For example, a game must meet within the minimim and maximum player limitation, someone must own the board game, there but be a viable hosting location in order to be played.

## Target Audience

Game Plan targets an audience of board game enjoyers of all levels, who are seeking to connect with people through local events and discover new games, while the app takes care of the logistics of event management.

The target audience can be broken down further in these categories:

- Board game hobbyists: Those passionate about board games, seeking a convenient way to host and join game events
- Casual gamers: People interested in trying new games and meeting up with people in a social evironment
- Game groups and clubs: Organisations that want to streamline event scheduling, communications, and member engagement.

## Functionality and Features

User Profiles:

- Create personalised profiles with game collections, preferences

Game Event Creation:

- Search and select the prerferred game from the BoardGameGeek API
- Specify game, time, location, player minimum and maximum count
- Save the game event as a draft before publishing it for viewing

Game Event Discovery:

- Browser a currated list of upcoming game events, filtered by game and date
- See a brief overview of game names, date and time lcation, host, players going
- Access detailed event information when clicking into the event
- RSVP as 'Going', 'Can't go'

Game Collection Management:

- Build a digital library of owned gamed
- Click into it to get detailed game information as a link to BoardGameGeek

---

Log in and Sign up:
New users can regist and prvide a username and password, and returning users can log in using their existing credentials. This grants access to the core features of the app.

Navigation:
Once logged in, users can navigate to various sections of the app through the navigation menu. They can edit their profile, manage their owned games, view their upcoming event, access drafts of events they are creating, discover new events to join, explore games to add to library, and log out when finished. The prominent 'New Event' button allows users to become a host by initiating the event creation process.

User Profile:

Owned Games:

Upcoming Events:

Event Drafts:

Discover Events:

Discover Games:

New Event Creation:
The event creation flow is designed to be straightforward. The user selects the 'New Event' button on the navigation menu which allows them to become a host and initiate creating an event. The host is met with a form with criteria to fill out in order to satisfy the event requirements. A host begins by searching for a game by name and then selecting their desired result from a list pulled from BoardGameGeek API. Next, they set the date, time, and duration utilising react-calendar. The location is set as a simple string. A description section allows the host to provide additonal details for attendees to see. The minimum and maximum player limits for a game is automatically input when the game is selected from the BoardGameGeek API. There is a toggle to set the event as a private event which cannot be searched for in discover, and instead only found via a link. The 'Submit' button makes the event visible to others, while the 'Preview Event' allows the host to review th event details before finalising. 'Save as Draft' provides the flexibility to return to the event creation process later.

Event Page:

- Edit Profile
- Games Owned
- My Events
- Event Drafts
- Discover Events
- Discover Games
- Logout
- NEW EVENT

New Event:

- Search for Game name
- Date
- Time
- Location
- Duration
- Description
- Host
- Guests
- Minimum players
- Maximum players
- Is event private
- Publish event
- Preview Event
- Save as Draft

Events Page:

- Event Name
- Hosted by
- Game Image
- Date and Time
- Location
- Info / About
- Free Spots
- Greenlight
- Edit event (host only)
- Cancel event (host only)
- Join Game (guest only)

## Tech Stack

Core Framework:

- MERN:
  - MongoDB
  - Express.js
  - React.js
  - Node.js

API Intergrations:

- BoardGameGeek API

Frontend Development:

- Languages:
  - HTML5
  - CSS3
  - JavaScript
  - XML
- Library / Framework:
  - React.js
  - React Router
  - react-calendar
  - xml2js

Backend Development:

- Runtime:
  - Node.js
  - Nodemon
- Framework:
  - Express.js
- Data Formats:
  - JSON
  - XML
- Database Interaction:
  - Mongoose
  - Axios
  - bcryptjs
  - JWT
  - dotenv

Deployment:

- Heroku
- Netlify

DevOps and Version Control:

- Git
- GitHub
- Visual Studio Code

Testing:

- Bruno
- Jest
- Mocha
- Cypress

Planning and Management:

- Trello
- Miro
- Discord

Design and Prototyping:

- Procreate
- Figma
- Miro

## User Stories

## Wireframes

## Planning

Trello screenshots
Miro screenshots
