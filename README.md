# Taskify

<img src="public/Screenshot (117).png"/>
<img src="public/Screenshot (137).png"/>

Key Features:

- Real-time database  🔗 
- Authentication 🔐 
- Full mobile responsiveness 📱
- Landing page 🛬


### Prerequisites

**Node version 18.x.x**

### Install packages

```shell
npm i
```

### Setup .env file


```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=""
CLERK_SECRET_KEY=""
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/
DATABASE_URL=""
```

### Setup Convex

```shell
npx convex dev

```

### Start the app

```shell
npm run dev
```
