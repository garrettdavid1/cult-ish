# Cult Ish

## Description

Cult Ish is a factions-like app that allows users to join a "Cult" with others, rank up by interacting in davidthed3v's Twitch streams and helping others via Discord, and cast incantations to perform neat actions. The idea is that this app will be a fun, positively reinforcing way to help everyone along their coding journey.

This app is a community build, so if you would like to help out, please do! Join us on [Discord](https://discord.gg/tptzFAYPvT) to collaborate!

---

&nbsp;

## Tech Stack

1. TypeScript
2. NextJS (ReactJS, Node.js)
3. PostgreSQL
4. Docker
5. Prisma (Object Relational Mapper)
6. TailwindCSS
7. Twitch API
8. Discord API

---

&nbsp;

## How to Contribute

In order to contribute, you will need to do the following:

1. Fork the repo
2. Clone the repo onto your local machine
3. Create branch - See [Branch Naming Convention](#branch-naming-conventions) below
4. Do your work
5. Commit (See [Commit Message Conventions](#commit-message-conventions)) & Push your changes to your remote repository
6. Create a Pull Request in THIS repo from the branch in your remote (forked) repo

---

&nbsp;

## Branch Naming Conventions

Branches should consist of 3 things:

1. Type of Branch [See below](#branch-types)
2. Issue Number
3. Description (using kebab-casing - hyphens between words)

> Template: \<type-of-branch>/\<issue-number>/\<description>

> Example: feature/#2/initial-readme-file

---

&nbsp;

## Commit Message Conventions

Commit messages should consist of 3 things:

1. Type of Branch [See below](#branch-types)
2. Issue number
3. Description of work

> Template: \<type-of-branch>/(closes \<issue-number>): \<description-of-work>

> Example: feature(closes #2): adds initiial readme file with basic info

---

&nbsp;

## Branch Types

1. feature
2. fix
3. infra

---

&nbsp;

## Setting Up Your Environment

1. Install Docker Desktop on your local machine.
2. Open a terminal/command line at the root of the project.
3. Locate the `.env.example` file in the root of the project and copy it, giving the new file the name of `.env`.
4. In the terminal, run `$ docker-compose up -d`. (Hint: Don't copy the $ symobl into the terminal) This will start a PostgreSQL database in a docker container without you having to install PostgreSQL on your local machine.
5. Run `$ npx prisma migrate dev` in the terminal.
