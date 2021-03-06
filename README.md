# Auth API (Mongoose)

## What is this?
An authentication API with JWTs using Express, TypeScript, and Zod.

This version uses MongoDB/Mongoose/TypeGoose for the database. I also built the same app but using Postgres/Prisma. You can find that [here](https://github.com/c-ehrlich/auth-api-prisma).

The MongoDB version is based on this video: [Build an Authentication API with Node.js, TypeScript, Typegoose, ExpressJS & Zod](https://www.youtube.com/watch?v=qylGaki0JhY)

## What did I learn?
The main point was to build a well structured boilerplate that I could base future projects on. I believe it was quite successful in that regard.

## What is missing?
* The biggest issue is that there currently isn't a real mailserver - it's just using nodemailer to send the "emails" to the terminal. Other than that it's fully functional.
* The password reset codes are currently not time limited - in a real version I would add a reset expiration data so that each code can only be used for 15 minutes, or whatever amount of time is deemed appropriate.
