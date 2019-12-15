# <a href="https://immense-ridge-78589.herokuapp.com/">Email Lesson Manager</a> <img src="https://github.com/danninemx/email-lesson-manager/blob/master/public/lesson-manager-logo.png/" alt="email-lesson-manager logo" align="right" height="50"> <a name="top"></a>

## Table of Contents <a name="toc"></a>

- [Overview](#overview)
- [Instructions](#instructions)
- [Technologies](#technologies)
- [Future Development](#future)
- [Developers](#team)

---

## Overview <a name="overview"></a>

This is a full stack web application that provides daily lessons via email to subscribed users.

It utilizes scheduled mailing in tandem with static resources to solve the challenge of pacing in self-education.

![Lynx-dataflow-diagram](./public/lynx-DFD.svg)

---

## Instructions <a name="instructions"></a>

1. Sign up will send an welcome email and set you up for daily JavaScript lessons.

## <p align="center"><img src="https://github.com/danninemx/email-lesson-manager/blob/master/public/e-learning-welcome.png" alt="email lesson manager welcome email"> </p>

2. Server sends scheduled, daily emails containing lessons.

**[ Daily Lesson ]**

## <p align="center"><img src="https://github.com/danninemx/email-lesson-manager/blob/master/public/e-learning-daily.png" alt="email lesson manager daily email"> </p>

If you have completed all available materials, an alternative reading material will be suggested until new courses become available.

**[ Completion Message ]**

## <p align="center"><img src="https://github.com/danninemx/email-lesson-manager/blob/master/public/e-learning-completion.png" alt="email lesson manager completion email"> </p>

3. User can choose to follow the emailed link to the website, which provides further detail about the subject.

4. User can explore at will related subjects such as HTML, CSS, HTTP status codes and more.

5. Get smarter every day!

<p align='right'><a href='#top'><sup>[Back to Top]</sup></a></p>

---

## Technologies <a name="technologies"></a>

| Technology/Dependency Used                                                  | Purpose                        |
| --------------------------------------------------------------------------- | ------------------------------ |
| [Node.js](https://nodejs.org/en/)                                           | JavaScript runtime environment |
| [NPM: Chalk](https://www.npmjs.com/package/chalk)                           | Logging                        |
| [NPM: Express](https://www.npmjs.com/package/express)                       | Server                         |
| [NPM: Express Handlebars](https://www.npmjs.com/package/express-handlebars) | Server-side rendering          |
| [NPM: MySQL 2](https://www.npmjs.com/package/mysql2)                        | Database                       |
| [NPM: Node Cron](https://www.npmjs.com/package/node-cron)                   | Job Scheduling                 |
| [NPM: Node-Sass](https://www.npmjs.com/package/node-sass)                   | Styling                        |
| [NPM: Nodemailer](https://www.npmjs.com/package/nodemailer)                 | Mailing                        |
| [NPM: Passport](https://www.npmjs.com/package/passport)                     | Authentication                 |
| [NPM: Sequelize](https://www.npmjs.com/package/sequelize)                   | Database                       |
| [Heroku](https://heroku.com)                                                | Deployment                     |
| [Heroku Add-on: JawsDB MySQL](https://elements.heroku.com/addons/jawsdb)    | Database                       |

<p align='right'><a href='#top'><sup>[Back to Top]</sup></a></p>

---

## Future Development <a name="future"></a>

- Selection-driven progression
- Additional subjects and structures
- Profile personalization
- More dynamic server-side rendering
- Database schema reorganization

<p align='right'><a href='#top'><sup>[Back to Top]</sup></a></p>

---

## Developers <a name="team"></a>

- [Danny Kim](https://github.com/danninemx)
- [Bladimir Orellana](https://github.com/BladimirOrellana)
- [John Paschal](https://github.com/patrickjpaschal)
- [Martin Palacios](https://github.com/martinapalacios)

<p align='right'><a href='#top'><sup>[Back to Top]</sup></a></p>
