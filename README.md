# FlowStable  
### Liquidity, Bridging, and DeFi Infrastructure for StableChain  
#### Built by FlowStable Labs

---

## Overview

FlowStable is a modular ecosystem designed for the StableChain network.  
It provides liquidity tools, bridging pipelines, and DeFi primitives that allow users and developers to interact with StableChain efficiently.

---

# Vision

**To establish the foundational liquidity, mobility, and DeFi infrastructure for the StableChain ecosystem.**

FlowStable serves as the entry layer for users, developers, and protocols who want to onboard onto StableChain with minimal friction.

---

## What This Repository Contains

This repository hosts the **official FlowStable website** deployed at:

```
https://flowstable.in
```

The site introduces the ecosystem and provides access to our testnet products.

---

# Product Modules

## 1. Bridge & Unwrap  
### (Live)

Move testnet tokens from **Sepolia → StableChain** and unwrap them using the FlowStable protocol.

```
- Dual-contract architecture (L1 lock → L2 mint/unlock)
- Settlement powered by gUSDT liquidity
- Fully integrated into the FlowStable UI
```

---

## 2. Spot Trading (DEX)  
### (Coming Soon)

A fully featured AMM DEX offering StableChain-native trading.

```
- FST/gUSDT core pools
- Clean, professional trading interface
- Price routing and liquidity analytics
```

---

## 3. Supply, Lend & Stake  
### (Coming Soon)

A lending and staking layer designed around isolated market risk.

```
- gUSDT-backed collateral models
- Incentivized lending pools
- Network-native staking primitives
```

---

# Technology Stack

```
HTML5  
CSS3  
JavaScript  
Vercel Deployment  
Static Site Architecture  
Route Rewrites for Multi-repo Integration  
```

---

# Routing Structure

### Website Architecture

```
/                    → Landing Page  
/bridge-testnet      → Proxied to Bridge UI repo  
/dex                 → Coming soon  
/lend                → Coming soon  
/stake               → Coming soon  
```

This is managed through:

```
vercel.json
```

which rewrites incoming routes to their respective deployments.

---

# Deployment

The website is deployed through **Vercel** with automatic builds on push.

```
git push origin main  
→ triggers auto-deployment  
```

Manual deployment:

```
vercel deploy --prod
```

---

# Roadmap

```
▪ FlowStable Wallet (Android)  
▪ Full DEX launch  
▪ Analytics dashboards  
▪ Multi-asset liquidity pools  
▪ StableChain-native staking suite  
▪ FlowStable Token (FST) integration  
```

---

# About FlowStable Labs

FlowStable Labs builds infrastructure around StableChain, enabling:

```
- Scalable bridging  
- Native AMM liquidity  
- Protocol-level DeFi modules  
- Developer-friendly RPC integrations  
```

Purpose-built for the Stable.xyz ecosystem.

---

### Contact

For collaborations, integrations, or contributions:  
**FlowStable Labs**  
```
flowstable.in
```

---
