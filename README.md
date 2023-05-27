TaskPro is a task tracker built with Ruby on Rails and React

## Prerequisites

In order to use this repository, you will need to have the following setup in your computer.

![node:v0.9.0](https://img.shields.io/badge/node-v0.9.0-blue.svg)
![npm:v8.15.0](https://img.shields.io/badge/npm-v8.15.0-blueviolet.svg)
![ruby:2.7.4](https://img.shields.io/badge/ruby-2.7.4-yellow.svg)

- `node v0.9.0+`
- `npm 8.15.0+`
- `ruby 2.7.4+`

## Setup Instructions

This section will guide you through setting up and running this repository on your local machine.

### Project

- Clone the repository
  ```
  git clone https://github.com/mooose22/Task-Pro
  ```
- Navigate to the project folder
  ```
  cd Task-pro
  ```
- To interact with the front-end part of the application, navigate to the `client` folder
  ```
  cd client
  ```
- To interact with the back-end part of the application, navigate to the `api` folder
  ```
  cd api
  ```

### Environment Variables

To use the environment variables, create three environment files: `.env`, `.env.development` and `.env.production`.

Use the following criteria to set your environment variables:

- `.env` - Common variables that are not specific to any environment.
- `.env.development` - Variables that are only specific to `development` or `test` environments.
- `.env.production` - Variables that are only specific to production environment. Example: `ENTRY`.

```{shell}
# POSTRESQL DATABASE
DEV_DB_USER='database_username'
DEV_DB_PASSWORD='database_password'
DEV_DB_NAME='database_name'

# DOMAIN
CURRENT_SITE_DOMAIN=http://localhost:8080/

# SENTRY
SENTRY_DNS=8.8.8.8

# COMMON_API_CREDS
REACT_APP_API_URL=https://myApiServerUrl.com
```

NB:

- Ensure you use the prefix `REACT_APP_` to store all the variables that are needed in the React Application. Example: `REACT_APP_NAME=janedoe`
- **DO NOT** commit any of the environment files to version control.

## Technologies Used

This application has been built with these technologies:

- Ruby `v2.7.0`
- Sinatra `v3.0`
- RSpec `v3.1.2`
- React `v18.0`
- Typescript `v4.9.5`
- Jest `v29.5.0`
- Firebase `v9.17.0`
- nginx
- Docker
- GitHub Actions
- GitHub Projects
