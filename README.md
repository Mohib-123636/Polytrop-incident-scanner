# polytrop-incident-scanner

polytrop-incident-scanner is an advanced on-chain security incident and forensic intelligence web application designed to track stolen cryptocurrency funds, multi-hop transaction trails, and risk-exposure metrics across Bitcoin, Ethereum/EVM, Tron, and Solana.

Website link: https://polytrop-incident-scanner.vercel.app

## 🚀 Features

* **Global Search & Investigation Engine:** Instantly search wallet addresses or transaction hashes to trace asset movement hop-by-hop from initial drains to exchange deposits.
* **Live Incident Directory:** Comprehensive tracking tables covering major exploits (such as Solana DEX Oracle Manipulation, Bybit Cold Wallet Drain, WazirX Multisig Exploit, and DMM Bitcoin Theft) with real-time status indicators (*Live*, *Contained*, *Archived*).
* **Propagation Hop Explorer:** Detailed data tables tracking top flagged transfers with multi-chain filter toggles (BTC, Tron, EVM, Solana) and transaction size filtering (`> $50K`, `> $500K`, `> $2M`).
* **Forensic Metrics Overview:** High-level summary cards tracking total incident volume, traced capital, wallets under watch, reached services, and issuer-frozen asset totals.
* **Data & API Access Hub:** Dedicated download triggers and API reference tools for exporting forensic intelligence data.

## 🛠️ Tech Stack

* **Frontend:** Next.js (App Router), React, TypeScript
* **Styling & UI:** Tailwind CSS, Lucide React (Icons)
* **Data Handling:** TanStack Table for high-performance sorting, filtering, and pagination of large tainted-address datasets

## 📁 Project Structure

```text
polytrop-incident-scanner/
│
├── app/              # Next.js App Router pages & scanner routes
├── components/       # Reusable UI components (Search bar, Incident tables, Hop explorer)
├── data/             # Mock forensic datasets, exploit incident metadata, and transaction trees
├── public/           # Static assets, chain icons, and branding
└── styles/           # Global Tailwind CSS configurations & themes
