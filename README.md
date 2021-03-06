# Project Overview

Most of us can relate to kicking back on the couch and enjoying a movie with friends and family. In this project, you’ll build an app to allow users to discover the most popular movies playing. 
You’ll build the complete functionality of this app in two stages which you will submit separately.

# Stage 1:  Main Discovery Screen, A Details View, and Settings
## User Experience

In this stage you’ll build the core experience of your movies app. You will build a clean UI, sync to a server, and present information to the user.
Your app will:
* Upon launch, present the user with an grid arrangement of movie posters.
* Allow your user to change sort order via a setting:
  * The sort order can be by most popular, or by top rated
* Allow the user to tap on a movie poster and transition to a details screen with additional information such as:
  * original title
  * movie poster image thumbnail
  * A plot synopsis (called overview in the api)
  * user rating (called vote_average in the api)
  * release date

# App UX

<img src="https://github.com/Aimannab/popular_movies/blob/master/Popular%20Movies%201(1).gif" />

<img src="https://github.com/Aimannab/popular_movies/blob/master/Popular%20Movies%201(2).gif" />

# Why this Project

To become an Android developer, you must know how to bring particular mobile experiences to life. Specifically, you need to know how to build clean and compelling user interfaces (UIs), fetch data from network services, and optimize the experience for various mobile devices.You will hone these fundamental skills in this project. By building this app, you will demonstrate your understanding of the foundational elements of programming for Android. Your app will communicate with the Internet and provide a responsive and delightful user experience.

# What Will I Learn?

* You will fetch data from the Internet with theMovieDB API.
* You will use adapters and custom list layouts to populate list views.
* You will incorporate libraries to simplify the amount of code you need to write

# How Will I Complete this Project?
## Supporting Course Material

You should have the skills you need to complete this app after completing Lessons 1-4 of Developing Android Apps.

## Required Tasks

* Build a UI layout for multiple Activities.
* Launch these Activities via Intent.
* Fetch data from themovieDB API

# Implementation Guide

For step-by-step support, we've provided details on how to approach each task in this Implementation Guide.
Link: https://docs.google.com/document/d/1ZlN1fUsCSKuInLECcJkslIqvpKlP7jWL2TP9m6UiA6I/pub?embedded=true

# Rubric

## Required Specifications

* App is written solely in the Java Programming Language.
* Movies are displayed in the main layout via a grid of their corresponding movie poster thumbnails.
* UI contains an element (i.e a spinner or settings menu) to toggle the sort order of the movies by: most popular, highest rated.
* UI contains a screen for displaying the details for a selected movie.
* Movie details layout contains title, release date, movie poster, vote average, and plot synopsis.
* App utilizes stable release versions of all libraries, Gradle, and Android Studio.

## User Interface Specifications

* When a user changes the sort criteria (“most popular and highest rated”) the main view gets updated correctly.
* When a movie poster thumbnail is selected, the movie details screen is launched.

## Network API Implementation

In a background thread, app queries the /movie/popular or /movie/top_rated API for the sort criteria specified in the settings menu.

