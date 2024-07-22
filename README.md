# AI Resume Builder Admin

This repository contains the admin interface for the AI Resume Builder application, developed using Strapi.

## Table of Contents

- [AI Resume Builder Admin](#ai-resume-builder-admin)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Features](#features)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)


## Overview

AI Resume Builder is an application that allows users to create AI-generated resumes quickly and easily. This repository contains the admin interface built using Strapi, a powerful open-source headless CMS.

## Features

- Manage user accounts
- Monitor resume creation
- Handle content and settings

## Installation

Follow these steps to set up the project on your local machine.

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/ai-resume-builder-admin.git
    cd ai-resume-builder-admin
    ```

2. **Install dependencies:**

    Ensure you have [Node.js](https://nodejs.org/) installed.

    ```bash
    npm install
    ```

3. **Set up environment variables:**

    Create a `.env` file in the root directory and add your environment variables. Here is an example `.env` file:

    ```env
    DATABASE_HOST=localhost
    DATABASE_PORT=5432
    DATABASE_NAME=strapi
    DATABASE_USERNAME=strapi
    DATABASE_PASSWORD=strapi
    JWT_SECRET=your_jwt_secret
    ```

4. **Set up the database:**

    Ensure you have a database set up according to the environment variables. For example, if you're using PostgreSQL:

    ```bash
    createdb strapi
    ```

## Running the Application

1. **Start the Strapi server:**

    ```bash
    npm run develop
    ```

    The Strapi server will start, and you can access the admin interface at `http://localhost:1337/admin`.

2. **Access the admin panel:**

    Open your browser and go to `http://localhost:1337/admin`. You will be prompted to create an admin account if you haven't done so already.


