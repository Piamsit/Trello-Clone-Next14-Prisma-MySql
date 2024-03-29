# Trello-Clone-Next14-Prisma-MySql

## Getting Started

### Cloning the repository

```shell
git clone https://github.com/AntonioErdeljac/next13-trello.git
```

### Install packages

```shell
npm i
```

### Setup .env file


```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=

DATABASE_URL=

NEXT_PUBLIC_UNSPLASH_ACCESS_KEY=

STRIPE_API_KEY=

NEXT_PUBLIC_APP_URL=

STRIPE_WEBHOOK_SECRET=
```

### Setup Prisma

Add MySQL Database (I used PlanetScale)

```shell
npx prisma generate
npx prisma db push

```

### Start the app

```shell
npm run dev
```

## Acknowledgment

This project drew inspiration or guidance from the YouTube video [Link to Video](https://www.youtube.com/watch?v=pRybm9lXW2c&t=4997s). Special thanks to the creator for their valuable insights.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
