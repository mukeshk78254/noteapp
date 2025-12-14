# Solana Note App

A decentralized note-taking application built on Solana blockchain.

## 🚀 Live Demo

**Deployed Application:** [https://noteapp-xqd5.vercel.app/](https://noteapp-xqd5.vercel.app/)

## 📋 Project Details

### Smart Contract
- **Program ID:** `De4iRbmkeGWDR7b1dEKDXrgQSm1iE2YRLUZdDF4Y8chZ`
- **Network:** Solana Devnet
- **Explorer:** [View on Solana Explorer](https://explorer.solana.com/address/De4iRbmkeGWDR7b1dEKDXrgQSm1iE2YRLUZdDF4Y8chZ?cluster=devnet)

### Features
- 🔐 Wallet authentication (Phantom, Solflare)
- 👤 User profile creation
- 📝 Create, read, update, and delete notes
- 🔗 All data stored on Solana blockchain
- ⚡ Built with Next.js 14 and Anchor Framework

## 🛠️ Tech Stack

### Frontend
- Next.js 14.2.5
- React 18
- TypeScript
- Tailwind CSS
- Solana Wallet Adapter

### Backend
- Anchor Framework 0.30.1
- Rust (Solana Program)
- Solana Web3.js

## 📦 Installation

```bash
cd note-app-frontend
npm install --legacy-peer-deps
npm run dev
```

## 🌐 Environment Variables

```env
NEXT_PUBLIC_SOLANA_NETWORK=devnet
NEXT_PUBLIC_PROGRAM_ID=De4iRbmkeGWDR7b1dEKDXrgQSm1iE2YRLUZdDF4Y8chZ
```

## 📝 Program Instructions

1. **createUser(username)** - Create a user profile
2. **createNote(title, content)** - Create a new note
3. **updateNote(noteId, content)** - Update existing note
4. **deleteNote(noteId)** - Delete a note

## 🔗 Links

- **Live App:** https://noteapp-xqd5.vercel.app/
- **GitHub:** https://github.com/mukeshk78254/noteapp
- **Solana Explorer:** https://explorer.solana.com/address/De4iRbmkeGWDR7b1dEKDXrgQSm1iE2YRLUZdDF4Y8chZ?cluster=devnet

## 👨‍💻 Developer

Built by mukeshk78254
