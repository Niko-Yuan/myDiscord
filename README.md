# Fullstack myDiscord: Next.js 13, React, Socket.io, Prisma, Tailwind, MySQL

## Demo
- **URL**: [myDiscord Demo](https://mydiscord-production.up.railway.app)
- **Demo Email ID**: demoUser@gmail.com
- **Demo Password**: demoUser

## Features

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

## How to Build

To build and run the project, follow these steps:

```shell
npm i
npx prisma generate
npx prisma db push
