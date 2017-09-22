# It Cloud Academy final project
Final project for students of It Cloud Academy (https://itcloud.academy/)

### Table of contents

1. [Description](#description)
2. [Installations and usage](#installations-and-usage)
    + [Project init](#project-init)
    + [Server configuration](#server-configuration)
    + [Apply results](#apply-results)
3. [Js requirements](#js-requirements)

### Description
---
You need to create contact app like google contacts. Feel fre to use any libraries and frameworks that you need.

App must include functionality: 
+ show list of contacts;
+ add/delete/edit contacts;
+ show info of contact in modal window;
+ filter contacts by input field;
+ sort users by several points;

Browser requirements: IE9+ adn last 5 versions of modern browsers;
Screen resolution:
+ desktop (min - 1280 - 1024);
+ tablet (min - 768 - 1024);
+ mobile (min - 320 - 568);

### Installations and development
#### Project Init
Init new prject by your own or by cli of framework that you will use.

Init git and npm
``` bash
git init
npm init
```
Configure your ```package.json``` file for your development needs.

Install all dependencies
``` bash
npm install
```

For more information about work with npm [here](https://docs.npmjs.com/getting-started/what-is-npm);

#### Server configuration

For development server you will use JSON-server by typicode;

You can read documentation and installation guide on [this page](https://github.com/typicode/json-server);

For db.json file use this object
``` json
{
  "contacts": [
    { 
        "id": 1,
        "firstName": "John",
        "secondName": "Doe",
        "phone": 380666666666,
        "birthday": "01.01.2000",
        "website": "http://example.com",
        "email": "john.doe@example.com",
        "company": "freelance"
    }
  ],
  "profile": { "name": "typicode" }
}
```


#### Apply results
