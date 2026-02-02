Strapi Task 1 – DevOps Internship
Name: Akash K
Program: DevOps Pre‑Internship
Company: PearlThoughts

Introduction: What is Strapi (My Understanding)
Strapi is an open‑source Headless Content Management System (CMS) that allows developers to create, manage, and deliver content through APIs such as REST and GraphQL.

From my understanding gained during this task, Strapi is designed to decouple content management from frontend presentation. This allows backend teams to manage structured content efficiently, while frontend applications (web or mobile) consume the content via APIs.

Key points about Strapi:

Provides a powerful web‑based Admin Panel

Allows creation of custom content types without writing backend code

Exposes content securely via APIs

Highly flexible and suitable for modern, API‑driven applications

Commonly used in cloud‑native and DevOps‑oriented environments

Objective of Task 1
The objective of this task was to gain hands‑on experience with Strapi by performing the following:

Clone and explore the official Strapi repository

Run Strapi locally

Understand the project folder structure

Access and use the Admin Panel

Create a sample content type

Push the setup to GitHub

Document the complete workflow

Technology Stack Used
Node.js: v18 (LTS)

Strapi: v5

Database: SQLite (default)

Version Control: Git and GitHub

Operating System: Windows

Strapi Repository Exploration
As part of the task, I cloned the official Strapi repository to understand its internal structure.

Key directories explored:

packages/ – Core Strapi packages and modules

examples/ – Sample projects for reference

docs/ – Official documentation

scripts/ – Build and automation scripts

This helped me understand how Strapi is modularized and how different components interact within the framework.

Local Strapi Setup
For running Strapi locally in a stable and recommended way, I used the official Strapi CLI.

Creating the Strapi Application
npx create-strapi-app my-strapi-app --quickstart
This command:

Created a new Strapi project

Configured SQLite automatically

Started the development server

Opened the Admin Panel

Running the Application
npm run develop
Admin Panel URL:

http://localhost:1337/admin
Admin Panel Configuration
Created an administrator account

Logged into the Strapi Dashboard

Accessed the Content‑Type Builder and Content Manager

Content Type Creation
Using the Content‑Type Builder, I created a Collection Type named Article.

Fields Defined
title – Text (Required)

description – Rich Text

publishedDate – Date

The content type was saved successfully and the server restarted as required.

Sample Content Entry
Created one Article entry

Added sample data

Published the entry

Verified it under the Published section

This confirmed that the content type and database configuration were working correctly.

Project Structure Overview
Important directories and files in the project include:

config/ – Server, database, and plugin configuration

src/api/ – API logic for content types

src/api/article/ – Schema, routes, controllers, and services for Article

public/ – Static assets

database/ – SQLite database and migrations

How to Run the Project Locally
npm install
npm run develop
Then access:

http://localhost:1337/admin
Loom Video Demonstration
The Loom video demonstrates:

Running Strapi locally

Accessing the Admin Panel

Article content type configuration

Published sample entry

GitHub repository overview

Loom Video Link:
https://www.loom.com/share/c5d7219c00674fe38a87d6daab7df1bc

GitHub Repository
Repository Link:
https://github.com/AKASH8525/strapi-task-1

Conclusion
Through Task 1, I gained practical exposure to Strapi setup, headless CMS concepts, local development, content‑type creation, and GitHub workflow.
This task helped me understand how Strapi fits into modern backend and DevOps workflows, especially for API‑based applications.

Task 1 completed successfully.