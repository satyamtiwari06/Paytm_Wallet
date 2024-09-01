<h1>🚀 Paytm Wallet Clone</h1>
<p>Welcome to the Paytm Wallet Clone — a seamless digital wallet solution built with Next.js! This application allows users to manage their wallet balance with ease, featuring on-ramp transactions and person-to-person transfers.</p>

<ul>
<li><h2>🌟 Features</h2></li>
    <ul>
<li><h3>🔒 Secure Authentication: Hassle-free registration and login with JWT-based security.</h3></li>
<li><h3>💸 On-Ramp Transactions: Easily fund your wallet from external sources like bank accounts or credit cards.</h3></li>
<li><h3>🤝 Person-to-Person Transfers: Instant money transfers between users within the app.</h3></li>
<li><h3>📊 Transaction History: View a detailed history of your wallet transactions at any time.</h3></li>
<li><h3>⚡ Real-Time Balance: Stay updated with your balance in real-time after every transaction.</h3></li>
<li><h3>📱 Responsive Design: Optimized for all devices — from desktops to mobile screens.</h3></li>
    </ul>
<li><h2>🛠️ Tech Stack</h2></li>
    <ul>
<li><h3>Frontend: Next.js, React, Tailwind CSS</h3></li>
<li><h3>Backend: Node.js, Express.js</h3></li>
<li><h3>Database: PostgressSQL</h3></li>
<li><h3>Authentication: JWT (JSON Web Tokens)</h3></li>
    </ul>
</ul>
- Clone the repo

```jsx

```

- npm install
- Run postgres either locally or on the cloud

```jsx
docker run  -e POSTGRES_PASSWORD=mysecretpassword -d -p 5432:5432 postgres
```

- Copy over all .env.example files to .env
- Update .env files everywhere with the right db url
- Go to `packages/db`
    - npx prisma migrate dev
    - npx prisma db seed
- Go to `apps/user-app` , run `npm run dev`
- Try logging in using phone - 1111111111 , password - alice (See `seed.ts`)
