# Discord Clone: Discordd

Credits: [Antonio Erdeljac](https://github.com/AntonioErdeljac)
Live: [Vercel](https://discordd-vert.vercel.app)
    : [Rendrer](https://discordd-9bc5.onrender.com)

Features:

- Client form validation and handling using react-hook-form
- POST, DELETE, and GET routes in route handlers (app/api & pages)
- Real-time messaging using Socket.io
- Send attachments as messages using UploadThing
- Delete & Edit messages in real time for all users
- Create Text, Audio and Video call Channels
- 1:1 conversation between members
- 1:1 video calls between members
- Member management (Kick, Role change Guest / Moderator)
- Unique invite link generation & full working invite system
- Infinite loading for messages in batches of 10 (tanstack/query)
- Server creation and customization
- Beautiful UI using TailwindCSS and ShadcnUI
- Full responsivity and mobile UI
- Light / Dark mode
- Websocket fallback: Polling with alerts
- ORM using Prisma
- MySQL database using Planetscale
- Authentication with Clerk


### Cloning the repository

```shell
git clone https://github.com/anurag2204-k/discordd.git
```

### Install packages

```shell
npm i
```

### Rename .env.example to  .env file
  -fill the required

### Setup Prisma

I have used neonDb

```shell
npx prisma generate
npx prisma db push
```
OR
```shell
npx prisma generate
npx prisma migrate dev --name init
```

### Start the app

```shell
npm run dev
```

