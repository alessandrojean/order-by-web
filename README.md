<p align="center">
<img src="https://i.imgur.com/oSlvwO6.png"><br/>
<img src="https://img.shields.io/badge/presented-2015.11.25-green.svg"> <img src="https://img.shields.io/badge/grade-MB-blue.svg"> <img src="https://img.shields.io/badge/part-web-orange.svg">
</p>

Term paper for the Information Systems Technician course, finished and presented in November, 2015.

The project consists in an administration software for a school, with the management done by a [software](https://github.com/alessandrojean/order-by-desktop), an [website](https://github.com/alessandrojean/order-by-web) and an [application](https://github.com/alessandrojean/order-by-android).

## Features
- Read all the news published by the [software](https://github.com/alessandrojean/order-by-desktop);
- Access to the school timetable;
- Teacher control of grades and abcenses;
- Generate student list for abcense control, and student photo list;
- Student visualization of grades and abcenses;
- API for the [application](https://github.com/alessandrojean/order-by-android).

## Contents
- All the files that website needs to work;
- Database file (`banco-de-dados.sql`).

## Instructions

Put all the files in your Apache `www` folder, import the database SQL in phpMyAdmin or in your MySQL, and access.

For create a teacher or a student login, you'll need first to install the [software](https://github.com/alessandrojean/order-by-desktop), and create one, so you can access the teacher or student management panel.

## Resources

You will find all the resources used in the `recursos` folder, that contains:

- **[bootstrap](https://github.com/twbs/bootstrap)** *v3.3.5+*: used in all the website;
- **[Font-Awesome](https://github.com/FortAwesome/Font-Awesome)** *v4.4.0+*: used in all the icons;
- **[lightbox2](https://github.com/lokesh/lightbox2)** *v2.8.1+*: used for show the pictures in the news section;
- **[salvattore](https://github.com/rnmp/salvattore)** *v1.0.8+*: used for the layout of the news section.

## License

    Copyright 2017 Order By

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
