# Express-Ride

> A MERN bus-ticket booking project with a React client and Express server.

## Overview

Express Ride models a bus-booking flow, with routes documented for travel between Mumbai and Bengaluru. The client and server are separate applications in this repository.

## What’s in this repo

- Bus search and booking interface
- Account and booking workflows
- Razorpay test-payment guidance in the existing project documentation

## Stack

React, Redux, Bootstrap, Node.js, Express, MongoDB, JWT, Razorpay.

## Getting started

1. Install dependencies in both `client/` and `server/` with `npm install`.
2. Configure the server’s local environment and database settings without committing credentials.
3. Start the server with `npm start` from `server/`, then start the client with `npm start` from `client/`.

## Notes

The server folder contains a committed `.env` file. Review it for credentials, move any real values to secret configuration, and rotate them if they were exposed. Use payment test credentials only in a sandbox.
