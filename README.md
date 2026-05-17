# 🦷 DentPay — Cross-Border Dental Payments via AUDD on Solana

> Instant, zero-fee dental payments between Australian patients and CIS clinics — powered by AUDD stablecoin on Solana.

## 🌏 The Problem

Australian patients travel to Kazakhstan for dental treatment that costs 3–5x less than in Sydney. But paying across borders is broken:

| Method | Fee | Time |
|--------|-----|------|
| SWIFT transfer | ~A$35–50 | 3–5 days |
| Cash | FX loss | Risky |
| **DentPay (AUDD)** | **< $0.001** | **< 1 second** |

## ✅ The Solution

DentPay is a payment widget for dental clinics serving international patients.

1. Clinic enters amount → generates QR code
2. Patient scans with Phantom wallet → approves
3. Clinic receives AUDD instantly on Solana

## 🏗️ Tech Stack

- Next.js + Solana Web3.js
- Solana Pay protocol
- AUDD SPL Token
- Phantom / Backpack / Solflare wallet adapters
- Helius RPC for real-time confirmation

## 🗺️ Roadmap

| Phase | Timeline | Milestone |
|-------|----------|-----------|
| 1 | ✅ Done | Interactive demo, grant proposal |
| 2 | Weeks 1–2 | Solana Pay + AUDD SPL integration |
| 3 | Weeks 3–4 | Embeddable clinic widget |
| 4 | Weeks 5–6 | Mobile patient payment flow |
| 5 | Weeks 7–8 | Pilot with 1 clinic in Shymkent |

## 👨‍⚕️ About

Built by a 5th-year dental student from Kazakhstan. I see this problem firsthand — clinics in Shymkent already treat international patients but have no modern payment infrastructure.

- Domain expertise: dental workflows, patient psychology
- Blockchain: DentPay (Base), DENTALINK (Solana Blinks)
- Development: AI-assisted solo building (Claude + Cursor)

## 📄 License

MIT
