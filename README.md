# Issue Tracker is a Next.js Project with Tailwind, Radix UI, and Prisma

[Next.js Projects: Build a Full-stack App with Next.js, Tailwind, Radix UI, and Prisma](https://www.youtube.com/watch?v=J9sfR6HN6BY)

Autres dependencies :

- react-icons
- classnames
- prisma
- @prisma/client
- zod
- @radix-ui/themes
- easymde
- react-simplemde-editor
- axios
- react-hook-form
- @hookform/resolvers

## Docker (postgresql)

Container name : issue-tracker-db
Host port : 5432 => 5432
Volume : D:/VSC_Workspace/issue-tracker/.data => /var/lib/postgresql/data
Environment variables :

- POSTGRES_DB = issue-tracker
- POSTGRES_USER = postgres
- POSTGRES_PASSWORD = passw0rd

Commande :

- docker run -d -p 5432:5432 -v /d/VSC_Workspace/issue-tracker/.data:/var/lib/postgresql/data -e POSTGRES_DB:issue-tracker -e POSTGRES_USER:postgres -e POSTGRES_PASSWORD:passw0rd --name issue-tracker-db postgres:12.19-alpine3.20

## NextJS

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
