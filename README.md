# PQC Prototype & Attack Simulation (Phase 1)

This Phase 1 prototype lets you:
- Generate post-quantum keypairs (Kyber KEM, Dilithium signatures) via an HTTP API  
- Simulate a tampering attack against Kyber ciphertexts and confirm decryption fails  
- Collect test results in JSON for later analysis

---

## Prerequisites

- **Windows 10** with **WSL2** (Ubuntu 22.04) enabled  
- **Node.js** (v18+) & **npm** installed in WSL2  

---

## 1. Backend Setup

```bash
# from project root
cd backend
npm install
# start the API on http://localhost:3001
npm start


# PQC Prototype & Attack Simulation (Phase 1)

…  

## 3. Frontend Setup

This React app lets you enter a `userId`, request PQC keys, and display the returned public keys.

```bash
# in a new shell, from project root
cd frontend
npm install
npm start
