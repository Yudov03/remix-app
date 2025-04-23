# Welcome to yuDoV Remix App!

- This is my first Remix Wep App

## Introduction

The application consists of 5 pages: Homepage, Login, Register, Dashboard, and Contact.

- By default, the Homepage is displayed, allowing users to choose between Login or Register.

- Upon successful Login/Register, a navigation bar will appear along with the Dashboard.

- Users can navigate to other pages, such as Contact.

- Clicking Logout will exit the application and return to the Homepage.

## Sercurity:

- Users cannot access internal pages (Dashboard, Contact, etc.) without logging in.

- Session management is used to handle login state.

## Architecture:

Server-Side Rendering (SSR) with Remix.

ORM using Prisma.

## Run:

Run the dev server:

```shellscript
npm run dev
```
