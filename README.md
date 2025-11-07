# File Metadata Microservice

<div align="center">

<img alt="Node.js" src="https://img.shields.io/badge/Node.js-12.x-339933?logo=node.js&logoColor=white" />
<img alt="Express" src="https://img.shields.io/badge/Express-4.x-000000?logo=express&logoColor=white" />
<img alt="Multer" src="https://img.shields.io/badge/Multer-1.4.x-6E3B6E" />

</div>

## Overview

Minimal Express microservice that accepts a file upload and returns its metadata (name, type, size) as JSON. Built as part of freeCodeCamp's APIs & Microservices curriculum; useful as a reference for basic multipart handling with Multer.

## Key Features

- Upload a file via multipart/form-data to `POST /api/fileanalyse`
- Returns JSON with `name`, `type`, and `size` in bytes
- Static HTML form at `/` for quick manual testing

## Tech Stack

Node.js 12, Express 4, Multer 1

## Architecture

Express server with Multer middleware for disk storage, static assets under `public/`, and a simple view in `views/index.html`. Single API endpoint: `POST /api/fileanalyse`.

## Performance & Accessibility

Lightweight server and static assets; minimal HTML with semantic structure for the upload form.

## Prerequisites

- Node.js: `12.0.0`

## Installation

```bash
git clone https://github.com/maxgalchenko/file-metadata-microservice.git
cd file-metadata-microservice
npm install
```

## Quick Start

```bash
npm start
```

Open http://localhost:8080

## Available Scripts

- `npm start` – Start the Express server (PORT from env or 8080)

---

<div align="center">

Built with ❤️ by [Maksym Galchenko](https://github.com/maxgalchenko)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/galchenko-max/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-green?style=for-the-badge&logo=web)](https://portfolio-green-six-29.vercel.app/)
[![Email](https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail)](mailto:galchenko.maksym@gmail.com)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

</div>
