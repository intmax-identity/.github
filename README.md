# 🛡️ IntMax identity

![image](https://github.com/user-attachments/assets/2577e5ec-01bf-4242-9689-c994b817386b)

**Privacy-preserving identity verification for IntMax deposits and withdrawals using zero-knowledge proofs.**

IntMax Identity main use case: users scan their passport and generate a ZK proof that they are **not** on a blacklist — without revealing their identity.

## 🚀 Tech Stack

- Noir (UltraPlonk)
- TypeScript
- Kotlin

## User flow of getting whitelisted

1. Connect MetaMask to IntMax Identity app
2. Login with IntMax
3. Generate a QR code containing your IntMax address
4. Scan it with the mobile app
5. Read your passport security data with the NFC module on your device and verify it with a ZK proof
6. Broadcast the proof on-chain
7. IntMax identity contract will verify the proof on-chain and get you whitelisted!

## Full pasport verification schema

![image](https://github.com/user-attachments/assets/a2401325-5449-40b3-b693-2d10869e0ce8)

## Proof of blacklist non-inclusion schema

![image](https://github.com/user-attachments/assets/d8a99eeb-e239-4b07-a2a5-4fd18ef3b9d3)
