[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/leanix-custom-report-tutorial-05)](https://api.reuse.software/info/github.com/SAP-samples/leanix-custom-report-tutorial-05)

Tutorial 05: transforming GraphQL data using Javascript Array methods

Transforming GraphQL data using Javascript Array methods

## Table of Contents

- [Table of Contents](#table-of-contents)
- [Project setup](#project-setup)
- [Available scripts](#available-scripts)

## Project setup

This project was bootstrapped with [leanix-reporting-cli](https://github.com/leanix/leanix-reporting-cli).

1. `npm install -g @leanix/reporting-cli`
1. `npm install` in project directory
1. create a `lxr.json` file in project directory (please see [Getting started](https://github.com/leanix/leanix-reporting-cli#getting-started))

## Available scripts

In the project directory, one can run:

`npm start`

This command will start the local development server. Please make sure you have properly configured `lxr.json` first.
It will take the specified API Token from `lxr.json` and automatically do a login to the workspace.

`npm run build`

Builds the report and outputs the build result into `dist` folder.

`npm run upload`

Uploads the report to the workspace configured in `lxr.json`.
Please see [Uploading to LeanIX workspace](https://github.com/leanix/leanix-reporting-cli#uploading-to-leanix-workspace).
