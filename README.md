# Whatsnxt

Whatsnxt is a learining provider where students can opt for online courses or live online training

- Latest tech courses
- Practical training with live examples
- ✨Best courses  available✨

## Tech

Whatsnxt uses a number of open source projects to work properly:

- [NextS] - HTML enhanced for web apps!
- [Sun Editor] - awesome rich-text editor
- [Twitter Bootstrap] - great UI boilerplate for modern web apps
- [node.js] - evented I/O for the backend
- [Express] - fast node.js network app framework
- [Redis] - the caching system
- [Docker] - Container system
- [Terraform] - To build infrastructure on AWS
- [SNS] - For cloudwatch Metric notification
- [MongoDb] - NoSQL database on mongo atlas

## Installation

Whatsnxt requires [Node.js](https://nodejs.org/) v10+ to run.

Install the dependencies and devDependencies and start the server.

```
npm i
npm run local
```

## Features

Dillinger is currently extended with the following plugins.
Instructions on how to use them in your own application are linked below.

| Plugin | README |
| ------ | ------ |
| Security | helmet, csrf, cors, api rate limiting |
| App-scaling | PM2 nodejs clustering module |
| Login | Next-auth |
| Notifications | Ract-toastify and custom spinnerloader on FE |
| Google Analytics | Page views |
| Search | Algolia |
| Payment options | Razor pay integration |
| Custom CMS | custom history page for logged in user with search by name, date and category tags, single or multi delete articles|
| Sidebar | show popular blogs by tags and tag count |
| Cache | redis between FE and BE |
| Email | Node mailer to send email to user about course |
| User management | profile, enrolled courses, password reset option |
| Data tables | next-ui |
| Comments and nested replies | Nextjs Comments, nested replies component, Backend logic was implemented using Model Tree Structures with an Array of Ancestors in mongodb |
| Performance | Mongo Schema fields are indexed selectively to increase the read query Performance of the app |
| Page views | Google analytics to analyse page views and visitors |

## Deployment
```sh
npm run deploy
```

This will create the whatsnxt image and pull in the necessary dependencies.
Pushes the images in to AWS ecr and creates infra using terraform
