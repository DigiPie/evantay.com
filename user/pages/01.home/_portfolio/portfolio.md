---
title: Portfolio
categories:
  - SE:
    title: Projects
    description: My full-stack and software engineering projects
    portfolio:
      - title: DigiCourse
        quickSubtitle: Full-stack course management platform [NodeJS, ExpressJS, PostgreSQL, Herokuapp]
        quickLink: digicourse
        previewImg: digicourse.png
        fullImg: digicourse_full.png
        subtitle: Full-stack course platform with forum and enrolment features
        period: September to November 2019
        tech: NodeJS, ExpressJS, PostgreSQL, Herokuapp
        team: "<a href=\"https://github.com/DigiPie/\">Evan Tay</a>, <a href=\"https://github.com/halcyoneee/\">Lee Tze Ting</a>, <a href=\"https://github.com/Aquarinte/\">Jacqueline Cheong</a>, <a href=\"https://github.com/awarenessxz/\">Bryan Koh</a>"
        quote: "A course management platform where student-teacher interactions can take place seamlessly online."
        content: "We worked on DigiCourse under the National University of Singapore's <a href=\"https://nusmods.com/modules/CS2102/database-systems\">CS2102: Database Systems module</a>. It is a database-centric project which features two major components, a course enrolment system, and a forum system.<br><br>DigiCourse is continuously deployed from Github to Herokuapp, with the aid of Heroku build-packs such as the <a href=\"https://evantay.com/psql-heroku-buildpack\">psql-heroku-buildpack</a>. I wrote this build pack to automate the execution of a PostgreSQL setup script file on deployment to Heroku."
        repo: https://github.com/DigiPie/DigiCourse
      - title: Dynalite
        quickSubtitle: Internet-of-Things room occupancy visualisation app [Raspberry-Pi, Python, COAP, NodeJS, ExpressJS, PostgreSQL, ReactJS, Docker]
        quickLink: dynalite
        previewImg: dynalite.png
        fullImg: dynalite_full.png
        subtitle: Full-stack Internet-of-Things occupancy visualisation app
        period: September to November 2019
        tech: Raspberry-Pi, Python, COAP, NodeJS, ExpressJS, PostgreSQL, ReactJS, Docker
        team: "<a href=\"https://github.com/DigiPie/\">Evan Tay</a>, <a href=\"https://github.com/pikulet/\">Joyce Yeo</a>, <a href=\"https://github.com/crazoter/\">Matthew Lee</a>, <a href=\"https://github.com/Happytreat/\">Melodies Sim</a>"
        quote: "Dynalite is an Internet-of-Things application which performs dynamic visualisation of room occupancy."
        content: "We worked on Dynalite under the National University of Singapore's <a href=\"https://nusmods.com/modules/CS3103/computer-networks-practice\">CS3103: Computer Networks Practice module</a>. It is an Internet-of-Things application which performs dynamic visualisation of room occupancy.<br><br>Dynalite was built using 3 Docker containers and 1 Raspberry Pi. The RPi reads light data and sends it via COAP to the first Docker container containing a backend NodeJS-ExpressJS web server.<br><br>The backend server authenticates and stores the measurements into a PostgreSQL database stored in the second Docker container.<br><br>The backend server also provides a <a href=\"https://www.evantay.com/tech/dynalite-api/occupancy\">HTTP REST API</a> which is used by a frontend React web server in the third Docker container."
        repo: https://github.com/DigiPie/dynalite
        deploy: https://www.evantay.com/tech/dynalite/
      - title: BrainTrain
        quickSubtitle: Spaced-repetition flashcard desktop app [Java, JUnit5, JavaFx, OpenCSV]
        quickLink: braintrain
        previewImg: braintrain.png
        fullImg: braintrain_full.png
        subtitle: Spaced-repetition flashcard desktop app
        period: March to April 2019
        tech: Java, JUnit5, JavaFx, OpenCSV
        team: "<a href=\"https://github.com/DigiPie/\">Evan Tay</a>, <a href=\"https://github.com/halcyoneee/\">Lee Tze Ting</a>, <a href=\"https://github.com/eugenefdw\">Eugene Foo</a>, <a href=\"https://github.com/lallanachang\">Chang Lei</a>, <a href=\"https://github.com/jeraldtsy\">Jerald Tan</a>"
        quote: "BrainTrain is a spaced-repetition flashcard application which makes memorizing easy and effective. With BrainTrain’s <a href=\"https://www.theguardian.com/education/2016/jan/23/spaced-repetition-a-hack-to-make-your-brain-store-information\">Spaced Repetition System (SRS)</a> optimizing your flashcard revision intervals, you will be able to learn more in less time."
        content: "<a href=\"https://travis-ci.org/CS2103-AY1819S2-W14-1/main\" title=\"Build status\"><img src=\"https://travis-ci.org/CS2103-AY1819S2-W14-1/main.svg?branch=master\" /></a> <a href=\"https://ci.appveyor.com/project/eugenefdw/main\" title=\"Build status\"><img src=\"https://ci.appveyor.com/api/projects/status/vl6bo937loonr7x3?svg=true\" /></a> <a href=\"https://coveralls.io/github/CS2103-AY1819S2-W14-1/main?branch=master\" title=\"Coverage status\"><img src=\"https://coveralls.io/repos/github/CS2103-AY1819S2-W14-1/main/badge.svg?branch=master\" /></a> <a href=\"https://www.codacy.com/app/cs2103-w14-1/main?utm_source=github.com&utm_medium=referral&utm_content=CS2103-AY1819S2-w14-1/main&utm_campaign=Badge_Grade\" title=\"Codacy code quality\"><img src=\"https://api.codacy.com/project/badge/Grade/d236c7af6a71427ebeae2571add1f3f4\" /></a><br><br>
        We worked on BrainTrain under the National University of Singapore's <a href=\"https://nusmods.com/modules/CS2103T/software-engineering\">CS2103T: Software Engineering module</a>. My primary responsibility was to design and develop the Card Management System. My secondary responsibility was to act as the project’s documentation lead. To find out more, view my <a href=\"https://digipie.github.io/BrainTrain/team/digipie.html\">project portfolio page</a>."
        tags: Java, JUnit5, JavaFx, OpenCSV
        repo: https://github.com/DigiPie/BrainTrain
        doc: https://digipie.github.io/BrainTrain/index.html
      - title: "Glory: Tales of Yi-Shun"
        quickSubtitle: 2D hack-n-slash action game [Unity, C#]
        quickLink: glory
        previewImg: glory.png
        fullImg: glory_full.png
        subtitle: 2D hack-n-slash action game
        period: May to September 2018
        tech: Unity, C#
        team: "<a href=\"https://github.com/DigiPie/\">Evan Tay</a>, <a href=\"https://github.com/Lunastryke/\">Lim Xuan Hao</a>"
        quote: "In Glory, you play as Yi-Shun, the last remaining swordsman of the great city of Sandosa. The undead warlord Ma Ti and his minions are advancing on the city and only you can stop them."
        content: "We worked on this project under the National University of Singapore's <a href=\"http://nusskylab-dev.comp.nus.edu.sg/\">CP2106: Independent Software Development Project (Orbital) module </a>. This module was conducted during the summer break.<br><br>We were one of the top 11 out of 211 teams which received an award (Honorable Mention), and a Google Chromecast each from Google Singapore."
        repo: https://github.com/DigiPie/Glory
        download: https://digipie.itch.io/glory
  - Web:
    title: Contributions
    description: My open-source utilities, tutorials and other contributions
    portfolio:
      - title: Mongo-Action
        quickLink: mongo-action
        previewImg: mongo-action.png
        fullImg: mongo-action_full.png
        subtitle: Github action which creates a mongo Docker container
        period: March 2020
        tech: GitHub Action, NodeJS, Docker
        team: "<a href=\"https://github.com/DigiPie/\">Evan Tay</a>"
        quote: "mongo-action is a Github Action which creates a mongo Docker container using the official <a href=\"https://hub.docker.com/_/mongo\">Dockerhub image</a>. The MongoDB instance's port will be exposed to other containers and also to the host running the Github Workflow."
        content: "<a href=\"https://github.com/DigiPie/mongo-action/workflows/mongo-action%20CI/badge.svg\" title=\"mongo-action CI\"><img src=\"https://github.com/DigiPie/mongo-action/workflows/mongo-action%20CI/badge.svg\" /></a><br><br>I created this Github Action to learn more about Continuous Integration tooling, and to simplify automated testing for my own <a href=\"https://github.com/DigiPie/mocha-chai-mongoose\">Node-ExpressJS-Mongoose</a> project.<br><br>By using this Github Action, there is no longer a need to provision a test database on MongoDB Atlas or elsewhere. Furthermore, each test will run on a fresh, isolated copy of a MongoDB instance.<br><br>I submitted this to the <a href=\"https://githubhackathon.com/\">Github Hackathon for Github Actions</a>."
        repo: https://github.com/DigiPie/mongo-action
        production: https://github.com/marketplace/actions/mongo-action
      - title: Google Developer Student Club NUS
        quickLink: dsc-nus
        previewImg: dscnustech.png
        fullImg: dscnustech_full.png
        subtitle: Tech team's website for workshop registration and materials
        period: January to March 2020
        tech: Jekyll, Bootstrap, Github pages
        team: "<a href=\"https://github.com/DigiPie/\">Evan Tay</a>, <a href=\"https://github.com/AndreWongZH/\">Andre Wong</a>, <a href=\"https://github.com/Happytreat/\">Melodies Sim</a>"
        quote: "Developer Student Club, National University of Singapore is made up of people from diverse backgrounds, majors, years of study, genders and races. We come together to push our mission of <a href=\"https://www.instagram.com/dscnus/\">#TechforGood</a>."
        content: "The Technology team is responsible for the execution of DSC-NUS workshops and thematic tech events.<br><br>We created this website to act as a one-stop portal for NUS students to find out more about our workshops, register for them, and access past workshop materials."
        repo: https://github.com/dscnustech
        production: https://dscnustech.github.io/
      - title: psql-heroku-buildpack
        quickLink: psql-heroku
        previewImg: heroku-buildpack.png
        subtitle: Heroku buildpack which executes a PostgreSQL script file
        period: September 2019
        tech: Herokuapp, PostgreSQL
        team: "<a href=\"https://github.com/DigiPie/\">Evan Tay</a>"
        quote: "psql-heroku-buildpack is a buildpack which executes a PostgreSQL script file on deployment to Heroku."
        content: "I developed this buildpack while working on <a href=\"https://evantay.com/digicourse\">DigiCourse</a>, a full-stack application built on PostgreSQL. I wrote this build pack to automate the execution of a PostgreSQL setup script file in the Git repo on deployment to Heroku from Github."
        repo: https://github.com/DigiPie/psql-heroku-buildpack
---

#Check out my notable projects and contributions
