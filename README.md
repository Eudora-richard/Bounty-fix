# BountyFix 🚀

**Discover bounties. Showcase your skills. Get rewarded for your work.**

BountyFix is a bounty platform designed to connect builders, designers, and developers with opportunities to contribute their skills to projects and communities. Users can explore available bounties, submit proposals, and manage bounty applications through a simple interface.

## ✨ Features

- **Browse Bounties** — Explore available opportunities across different categories and regions.
- **Search and Filter** — Find bounties using keywords and location filters.
- **Create Bounties** — Publish new bounty opportunities.
- **Submit Applications** — Send proposals and portfolio links to showcase your work.
- **Owner Dashboard** — Review applications and track their statuses.
- **Application Management** — Mark applications as Pending, Accepted, or Rejected.
- **Wallet Integration** — Connect a supported wallet through Pollar.
- **Responsive Interface** — Access the platform through a modern web interface.

## 🛠️ Tech Stack

- **Framework:** Next.js
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **Wallet Integration:** Pollar
- **Database:** Supabase (planned integration)

## 🚧 Project Status

BountyFix is currently under development.

The current version includes bounty browsing, bounty creation, application submission, and an owner dashboard. Some data is stored in the browser's local storage, meaning it is not yet shared between users or devices.

Supabase integration is planned to provide shared data storage. Additional work will be needed for user authentication, access permissions, and production-ready bounty management.

## 🚀 Getting Started

### Prerequisites

Make sure you have installed:

- Node.js
- npm
- Git (optional)

### 1. Clone the repository

```bash
git clone YOUR_REPOSITORY_URL
```

Replace `YOUR_REPOSITORY_URL` with your actual repository URL.

### 2. Open the project

```bash
cd bountyfix
```

### 3. Install dependencies

```bash
npm install
```

### 4. Configure environment variables

Create a `.env.local` file in the project root and add the environment variables required by your integrations.

For example:

```env
NEXT_PUBLIC_POLLAR_PUBLISHABLE_KEY=your_publishable_key
```

Use the exact variable name expected by your existing Pollar integration. Never commit private keys, database passwords, or service-role secrets.

### 5. Start the development server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## 📁 Project Structure

```text
bountyfix/
├── app/
│   ├── bounty/
│   │   └── page.tsx
│   ├── components/
│   │   └── WalletConnect.tsx
│   ├── create/
│   │   └── page.tsx
│   ├── dashboard/
│   │   └── page.tsx
│   ├── layout.tsx
│   └── page.tsx
├── public/
├── .env.local
├── package.json
├── tsconfig.json
└── README.md
```

## 🗺️ Roadmap

- [x] Build the homepage and bounty listings
- [x] Add bounty creation
- [x] Implement application submissions
- [x] Create an application management dashboard
- [x] Add application status tracking
- [x] Integrate wallet connection
- [ ] Connect Supabase for shared data storage
- [ ] Add user authentication and account profiles
- [ ] Implement role-based access for builders and bounty owners
- [ ] Add secure bounty funding and reward distribution
- [ ] Prepare the platform for production deployment

## 🔐 Security

BountyFix is still in development. Before production use, the platform needs appropriate authentication, database access policies, input validation, and secure handling of bounty funds.

Never expose secret API keys or private wallet credentials in client-side code.

## 🤝 Contributing

Contributions, feedback, and ideas are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Make your changes.
4. Submit a pull request describing your improvements.

## 📄 License

No license has been selected yet. Add a license before distributing or accepting contributions under specific reuse terms.

---

Built with 🚀 by the BountyFix team.
