# [![University Logo](app/assets/images/Logo_uandes.png)](https://www.uandes.cl/)

# Lab 2: Web Technologies -- About Me Page

## Table of contents:

- [Description](#description)
- [System dependencies & Versions](#system-dependecies--versions)
- [Installation](#installation)
- [Usage](#usage)

---

## Description

This project is a simple **Ruby on Rails web application** that recreates an *About Me* page.  
It uses **PostgreSQL** as the database and **Bootstrap** for styling and responsive layout.  

The app defines routes for both the root path (`/`) and `/about`, which point to the `About#index` controller action.  
The content is rendered using **Embedded Ruby (ERB) templates** styled with Bootstrap components.

---

## System Dependencies & Versions

- **Ruby:** 3.4.5
- **Rails:** 8.x
- **Database:** PostgreSQL

---

## Installation

1. Clone the repository

```bash
git clone https://github.com/ICC4103-202520-WebTech/lab-02-JuanCabelloVargas.git
cd lab-02-JuanCabelloVargas
```
2. Install dependencies:

```bash
bundle install
```

3. Set up the database:

```bash
rails db:create
```
---

## Usage

1. Start the development server:

```bash
bin/dev
```

2. Open your browser and go to:

[https://localhost:300](https://localhost:3000)

You will see the page running locally.

