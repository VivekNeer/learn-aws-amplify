<h1 align="center">learn-aws-amplify</h1>

<p align="center">
  <b>A simple React static site used to learn AWS Amplify hosting &amp; deployment.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite">
  <img src="https://img.shields.io/badge/AWS%20Amplify-FF9900?style=flat-square&logo=awsamplify&logoColor=white" alt="AWS Amplify">
</p>

---

## Overview

A minimal React + Vite static website (`staticwebsite`) built as a hands-on exercise for learning **AWS Amplify** — connecting a Git repo to Amplify, configuring the build, and getting continuous deployment of a static front-end on AWS.

The app itself is intentionally simple; the point of the project is the **hosting workflow**, not the UI.

## Tech Stack

- React 19 + Vite
- ESLint

## Getting Started

```bash
npm install
npm run dev        # local dev server
npm run build      # production build to dist/
```

## Deploying with AWS Amplify

1. Push this repo to GitHub.
2. In the AWS Amplify console, **Host web app** → connect this repository.
3. Amplify auto-detects Vite; the build command is `npm run build` and the output directory is `dist`.
4. Amplify builds and deploys on every push, serving the site from its CDN.
