# Whatsnxt

[Checkout the app here](https://whatsnxt.in/)

Whatsnxt is a video based learning platform along with relevant articles and tutorial series to create rich quality content. App also faciliates trainer search and consulting for other business or users

- Latest tech courses
- Practical training with live examples
- ✨Best courses  available✨

## Tech

Whatsnxt uses a number of open source projects to work properly:

- [NextJS] - HTML enhanced for web apps!
- [TiptapEditor] - awesome rich-text editor
- [MantineUI] - great component based UI for modern web apps
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

whatsnxt is currently extended with the following features.
Instructions on how to use them in your own application are linked below.

[Checkout the app here](https://whatsnxt.in/)

| Features | README |
| ------ | ------ |
| Security | helmet, csrf, cors, api rate limiting |
| App-scaling | PM2 nodejs clustering module |
| Login | HttpOnly JWT Cookie |
| Mantine Notifications | Mantine spinner loader on FE |
| Google Analytics using party town| Page views
| Search | Algolia |
| Payment options | Razor pay integration | Automated payouts
| Custom CMS | custom history page for logged in user with search by name, date and category tags, single or multi delete articles|
| Cache | redis between FE and BE | enabled cache control responses
| Email | Node mailer to send email to user about course |
| User management | profile, enrolled courses, password reset option |
| Data tables | material UI tables |
| Comments and replies | Nextjs Comments and replies component and nested comments
| Performance | Mongo Schema fields are indexed selectively to increase the read query Performance of the app |
| Mono repo | pnpm workspaces | pnpm re-useable packages
| ADR - Architectural decisions records | JS Docs
| SEO optimisation for desktop and mobile | Light house checks
| Course video URL's are encrypted

## Deployment
```sh
npm run deploy
```

This will create the whatsnxt image and pull in the necessary dependencies.
Pushes the images in to AWS ecr and creates infra using terraform

