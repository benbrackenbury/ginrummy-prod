# Gin Rummy
Developed by Ben Brackenbury & Sonny Ash for Durham University

## Demo
Access a full demo of the application [here](https://benbrackenbury.github.io/ginrummy-prod/).\
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
