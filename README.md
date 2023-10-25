Jamming - page to create and save Spotify playlists.

Project Requirements

    Build a web app using React
    Version control your application with Git and host the repository on GitHub
    Integrate with Spotify or another API
    Deploy your application
    Write a README (using Markdown) that documents your project, including:
        The purpose of your project
        Technologies used
        Features
        Future work

Features:

    Users can search for songs by song title.
        You can also include functionality to search by other attributes like artist’s name, genre, etc.
    Users can see information about each song like title, artist, and album for songs they queried
        You can also include other information – the design is up to you
    Users can export their custom playlist to their personal Spotify account

Prerequisites:

    HTML
    CSS
    JavaScript
    React
    HTTP Requests and Responses
    Authentication

Part 2

    Additional feature - Retrieve Track Preview Samples

App deployed on Netlify @ https://curious-heliotrope-2a69da.netlify.app/

===============================================================

# Jamming - create and save your Spotify playlist.

## Purpose

A coding exercise to practice working with API while creating an organized working application that allows user to create and save Spotify playlists.

## Technologies used

Spotify API - https://developer.spotify.com/
Netflify (test deployment)
React.js
HTML/CSS

## Features

App offers an option to search Spotify database for music. On first search there will be authorization request with Spotify.
After user has been authorizated search results are displayed on the left collumn. "+" buttons can be used to move songs into the playlist. "-" can be used to remove them from playlist. Playlist can be renamed and saved to user's Spotify profile.

## Future work

As additional feature, I tried to add previews for search results, however, I have not managed to make it work properly yet. Currently most search results display "No preview available for this track". I've not yet determined if there is an issue with API request or whether I have missed something, but that is a fix that I am in progress figuring out.
