# STACKSWORTH Infinity  
### 10″ Touchscreen Bitcoin Node & Hub Dashboard

**STACKSWORTH Infinity** is the flagship 10-inch model in the StacksWorth lineup — a self-contained Bitcoin node and BitAxe hub running on a Raspberry Pi 4 or 5 with a full-color capacitive touchscreen display.  
It unites **StacksWorth’s signature dashboard UI**, **local data services**, and **BitAxe integration** into one powerful, always-on Bitcoin appliance.

---

## ⚡ Vision

Infinity is designed to be the **heart of your Bitcoin environment** — a local, sovereign hub that runs a full node, connects to your BitAxe miners, and broadcasts Bitcoin’s live pulse through the same StacksWorth UI used across Spark and Matrix devices.

Every metric, visual, and animation you see is powered locally by your own node and presented in a futuristic touch dashboard experience.

---

## 🧠 System Overview

| Layer | Purpose |
|-------|----------|
| **StacksWorth Hub (`stx-hub`)** | Local Python FastAPI service exposing unified JSON endpoints for price, block, fees, miner, BitAxe, and system health. |
| **StacksWorth UI (dashboard)** | Responsive HTML / CSS / JS interface rendered fullscreen in Chromium kiosk mode. |
| **Bitcoin Node** | Native bitcoind running on SSD; source of all blockchain data and mempool metrics. |
| **BitA**
