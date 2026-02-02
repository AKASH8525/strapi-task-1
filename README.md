# Strapi Task 1 – DevOps Internship

## Candidate Details

* **Name:** Akash K
* **Program:** DevOps Pre‑Internship
* **Company:** PearlThoughts

---

## Introduction – What is Strapi (My Understanding)

Strapi is an open‑source **Headless Content Management System (CMS)** that allows developers to create, manage, and deliver content through APIs such as REST and GraphQL.

From my understanding during this task, Strapi decouples content management from frontend presentation. This enables backend teams to manage structured content efficiently, while frontend or mobile applications consume the content via APIs.

### Key Features of Strapi

* Web‑based Admin Panel for content management
* Custom content‑type creation without backend coding
* Secure content delivery through APIs
* Highly flexible and developer‑friendly
* Suitable for modern, cloud‑native and DevOps‑oriented applications

---

## Objective of Task 1

The objective of this task was to gain hands‑on experience with Strapi by completing the following:

1. Clone and explore the official Strapi repository
2. Run Strapi locally
3. Explore the project folder structure
4. Access and use the Admin Panel
5. Create a sample content type
6. Create and publish sample content
7. Push the complete setup to GitHub
8. Document all steps in a README file
9. Record a Loom video demonstration

---

## Technology Stack Used

* **Node.js:** v18 (LTS)
* **Strapi:** v5
* **Database:** SQLite (default)
* **Version Control:** Git and GitHub
* **Operating System:** Windows

---

## Strapi Repository Exploration

As part of the task, I cloned the official Strapi repository to understand its internal structure.

### Key directories explored:

* `packages/` – Core Strapi modules
* `examples/` – Reference applications
* `docs/` – Official documentation
* `scripts/` – Build and automation scripts

This helped me understand how Strapi is modularized and structured internally.

---

## Local Strapi Setup

To run Strapi locally in a stable and recommended way, I used the official Strapi CLI.

### Create the Strapi Application

```bash
npx create-strapi-app my-strapi-app --quickstart

```

**This command:**

* Created a new Strapi project
* Configured SQLite automatically
* Started the development server
* Opened the Admin Panel

### Run the Application

```bash
npm run develop

```

### Admin Panel URL

[http://localhost:1337/admin](https://www.google.com/search?q=http://localhost:1337/admin)

---

## Admin Panel Configuration

* Created an administrator account
* Logged into the Strapi Dashboard
* Accessed Content‑Type Builder and Content Manager

### Content Type Creation

Using the Content‑Type Builder, I created a Collection Type named **Article**.

**Fields Defined:**

* **title** – Text (Required)
* **description** – Rich Text
* **publishedDate** – Date

The content type was saved successfully and the server restarted as required.

### Sample Content Entry

* Created one Article entry
* Added sample data
* Published the entry
* Verified it under the Published section

This confirmed that the content type and database configuration were working correctly.

---

## Project Structure Overview

Important directories and files in the project:

* `config/` – Server, database, and plugin configuration
* `src/api/` – API logic for content types
* `src/api/article/` – Schema, routes, controllers, and services
* `public/` – Static assets
* `database/` – SQLite database and migrations

---

## How to Run the Project Locally

1. Clone the repository
2. Install dependencies:
```bash
npm install

```


3. Start the development server:
```bash
npm run develop

```


4. Access the admin panel at: [http://localhost:1337/admin](https://www.google.com/search?q=http://localhost:1337/admin)

---

## Loom Video Demonstration

The Loom video demonstrates:

* Running Strapi locally
* Accessing the Admin Panel
* Article content type configuration
* Published sample entry
* GitHub repository overview

**Loom Video Link:** [https://www.loom.com/share/c5d7219c00674fe38a87d6daab7df1bc](https://www.loom.com/share/c5d7219c00674fe38a87d6daab7df1bc)

---

## GitHub Repository

**Repository Link:** [https://github.com/AKASH8525/strapi-task-1](https://github.com/AKASH8525/strapi-task-1)

---

## Conclusion

Through Task 1, I gained practical exposure to Strapi setup, headless CMS concepts, local development, content‑type creation, and GitHub workflow. This task helped me understand how Strapi fits into modern backend and DevOps workflows, especially for API‑based applications.

**Task 1 completed successfully.**

Branch:akash