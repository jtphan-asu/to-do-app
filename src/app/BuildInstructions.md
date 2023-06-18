## Author: Jonathan Phan
## GitHub: https://github.com/jtphan-asu

--Create App Using Next.j,Prisma, and Typescript

npx create-next-app to-do-app --use-npm --ts

## Install Prisma to set up for PostgreSQL Database
npx prisma init --datasource-provider postgresql

    This creates:
    ✔ Your Prisma schema was created at prisma/schema.prisma

    Next steps:
    1. Set the DATABASE_URL in the .env file to point to your existing database. If your database has no tables yet, read https://pris.ly/d/getting-started

    2. Run npx prisma db pull to turn your database schema into a Prisma schema.

    3. Run npx prisma generate to generate the Prisma Client. You can then start querying your database.
