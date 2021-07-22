# Gin Rummy
Developed by Ben Brackenbury & Sonny Ash for Durham University

## [Demo](https://benbrackenbury.github.io/ginrummy-prod/)
Link above provides access to a working demo of the application.\
Note: The link to the survey will not work, and the demo will not send any chat data.

## Deployment
This application is a standard HTML web page, so can be run from any web server.

### Survey and PHP form URLs
Modify the `links.json` file to specify the URLs of the survey and the PHP form to which the chat data is sent.

The default values are as follows, and need to be updated to point to the necessary locations
```
{
    "chatLogPHP": "http://community.dur.ac.uk/e.c.stanton/studies/GinRummy/ginrummy.php",
    "survey": "URL"
}
```

### Source code
The source code for this project can be found [here](https://github.com/benbrackenbury/Gin-Rummy).\
It is built using the following technology stack:
* React JS
* Node JS
* SCSS
