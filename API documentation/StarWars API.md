# Star Wars API Overview
## Introduction

Welcome to the SWAPI, the Star Wars API! 
SWAPI helps all the fans of Star Wars movies to play around with the Star Wars universe’s people and retrieve detailed information about them. SWAPI uses standard HTTPS requests and responses. 
This documentation will help you to understand the endpoints and make API calls to get to know more about your favorite Star Wars characters.
## Getting Started
SWAPI is an open API. You can use any API platform that supports REST APIs to make the API calls. SWAPI supports the following environments: Python, JavaScript, Android, Java, Go, PHP, Ruby, C Sharp, Objective C, Angular, R, F#, and Elixir.
## Authentication
SWAPI is an open API. No authentication is required to query and get data. 
## Headers
Request content type – *application/json*

Request content type – *application/Wookiee*

Wookiee is for our tall hairy allies who speak Wookiee, this encoding is identical to JSON except with wookiee translations.

Using the wookiee renderer is easy, just append ?format=wookiee to your urls:

For example, https://swapi.py4e.com/api/planets/1/?format=wookiee

## Return Status Codes ##
| HTTP Status Code    | Status Code        | Description        
|----------------------|--------------------|------------------------------------------|
| 200 OK               |Success             |Request is processed correctly            |
| 404 Not found        |Data not found      |Data indicated in the request is not available in the SWAPI system            |


