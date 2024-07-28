# Chat Application

## Overview
This project is a real-time chat application built with Laravel, Node.js, React, and Tailwind CSS. The application consists of two main parts:
1. **Laravel app** - Responsible for handling web requests and serving views.
2. **Node.js app** - Acts as a WebSocket chat echo server.

All chat messages are logged to a PostgreSQL database. The frontend is built using React and Tailwind CSS, with Webpack for JavaScript bundling.

## Features
- Users can join the chat with a unique nickname.
- All users join a single chat room.
- Messages are broadcast to all users in the chat room.
- Security measures are implemented to prevent CSRF and XSS attacks.

## Prerequisites
Ensure you have the following installed on your machine:
- Node.js
- npm
- PHP
- Composer
- PostgreSQL
