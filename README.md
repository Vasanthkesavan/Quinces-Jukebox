# Quinces JukeBox

A viewable, dynamic, interactive song playlist application.

## Team

 - __API__: Nick Havens
 - __Front-end__: Jessica D'Andrea
 - __Server__: Joey Li / Vasanth Kesavan
 - __Database__: Joey Li / Vasanth Kesavan

## Table of Contents

1. [Usage](#Usage)
1. [Requirements](#requirements)
1. [Development](#development)
    1. [Installing Dependencies](#installing-dependencies)
1. [Team](#team)
1. [Contributing](#contributing)

## Usage

The JukeBox App allows a user to do the following:
- Search for songs & add songs to playlist
- Add a new user
- Upvote and downvote songs
- Play a song

### Search for songs & add songs to playlist
A user can go to the search page via the navigation menu. Once there, a user can type a song name in the input box and click the search button to see results. The user can select a song from the search results to add to the playlist.

If no username is selected when adding the song, the username associated with the added song will be `anonymous`

### Add a new user

To add a new user, go to the signup page via the navigation menu. Once added, the username should appear in the dropdown menu in the search page.

### Upvote and downvote songs
To upvote and downvote songs, click the correct buttons associated with each song on the playlist page. Songs are sorted based on their net vote count. A user can upvote or downvote a song more than once.

### Play a song
In order to play a song, the user must be logged in as host. To read more about this, please see [Placeholder]. Once logged in as host, the user should be able to see a button that says __Play top song__. If clicked, the top voted song will be sent to the player and that song will be removed from the playlist

#### Nick's section on logging in as host


## Development

### Installing Dependencies

From within the root directory:

```sh
npm install
nodemon server.js
```

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for contribution guidelines.
