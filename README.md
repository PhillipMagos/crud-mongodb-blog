https://www.youtube.com/watch?v=wNWyMsrpbz0&t=250s

npm i mongoose react-icons

RAqDV3pY488AE0zp
phillipmagos

Connect to MongoDB
1. 
Create your DB in MongoDB. Do all the UI stuff on their website.
From there, generate your username and password.

2. 
Create a .env file
Enter the MONGODB_URI inside the .env file

3. 
Create a new folder called libs
Create a fild called mongodb.js inside the same folder
Import mongoose, code up a try catch block to process the mongodb_uri and export the file

4. 
Create a new folder called models
Create a new file called topic.js inside the same folder.
Import mongoose and the Schema
define the data types aka schema

Note: Even if you restart your server, it still won't console log whether mongodb is connected or not

24:50 - Write the code to perform the CRUD operations
All the CRUD functionality seems to live inside the api folder.
create folder called api
create folder called topics inside the api folder
create file called route.js inside the topics folder

create folder called [id] inside the topics folder
create a file called route.js inside the [id] folder

38:44 - Connecting the backend to frontend

TopicsList.jsx





This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
