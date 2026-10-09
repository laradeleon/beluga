# The Story Machine

The Story Machine is a platform where anyone can write, publish, read, and discuss interactive stories in which readers shape the story through their choices, bringing authors and readers together in one community.

This repository contains the **front end** (Angular). The back end (NestJS + MongoDB) lives in a separate repository: _link coming soon_.

## Documentation
- [Vision Statement](./docs/sprint-0/vision.md)

## Deliverables
- [Sprint 0](./docs/sprint-0/sprint0.md)

## Running Locally

### Requirements
- [Git](https://git-scm.com/downloads)
- [Node.js](https://nodejs.org/) **version 24**

Check your versions with `node -v` (should print `v24.x.x`) and `git --version`.

### Install (once)
```bash
git clone https://github.com/laradeleon/the-story-machine.git
cd the-story-machine
npm ci
```
`npm ci` installs the exact dependency versions recorded in `package-lock.json`.

### Start the app
```bash
npm start
```
Then open http://localhost:4200. Press `Ctrl+C` in the terminal to stop the server.


## Group Members
- Lara De Leon
- Carsten Kolynchuk
- Colin Leger
- Arthur McMullen
- Krupal Patel
- Adejare Taiwo
- Oluwanifemi Tawoju
